# ADM_Project5

## Distributed Learning - Track A

### Step 1 - Centralized training baseline

#### 1. Steps to Tune Hyperparameters

- Start with a Baseline (common default values):
  |Baseline||
  |-|-|
  |Learning Rate| 0.001 (AdamW) or 0.01 (SGDM)|
  |Batch Size| 64|
  |Epochs| 150 (fixed)|
  |Momentum| 0.9|
  |Weight Decay| 1e-4|

- Learning rate
  - Too high: Instability, divergence.
  - Too low: Slow convergence.
  - Experiment with values like: 0.001, 0.01, 0.05, 0.1
- Batch size
  - Larger batch sizes may speed up training but require more memory.
  - Smaller batch sizes may lead to more noise and slower convergence.
  - Typical batch sizes: 32, 64, 128
- Momentum
  - Controls how past gradients affect current updates.
  - Try values like: 0.8, 0.9, 0.99
- Weight decay
  - Helps reduce overfitting by penalizing large weights.
  - Test values like: 1e-4, 1e-5, 1e-6
- Cosine annealing scheduler
  - Tuning for the learning rate scheduler can improve performance.
  - Ensure to test different T_max values (e.g., 100, 150, 200).

#### 1.1 AdamW

##### Finding the best hyperparameters

Based on the results:

| Test # | Epochs | batch_size | beta | weight_decay | learning_rate | results         |
| ------ | ------ | ---------- | ---- | ------------ | ------------- | --------------- |
| L1     | 150    | 64         | 0.9  | 0            | 5e-4          | Val Acc: 49.21% |
| L2     | 150    | 64         | 0.9  | 0            | 1e-3          | Val Acc: 47.39% |
| L3     | 150    | 128        | 0.9  | 0            | 1e-3          | Val Acc: 48.13% |
| S1     | 150    | 64         | 0.9  | 1e-5         | 1e-3          | Val Acc: 46.67% |
| S2     | 150    | 128        | 0.9  | 1e-4         | 1e-3          | Val Acc: 44.80% |
| S3     | 150    | 128        | 0.9  | 1e-4         | 1e-3          | Val Acc: 46.53% |
| S4     | 150    | 128        | 0.9  | 1e-4         | 5e-4          | Val Acc: 48.38% |
| S5     | 150    | 128        | 0.9  | 0            | 5e-4          | Val Acc: 48.80% |
| S6     | 150    | 64         | 0.9  | 4e-4         | 5e-4          | Val Acc: 49.95% |
| A1     | 150    | 64         | 0.9  | 5e-4         | 5e-4          | Val Acc: 45.94% |

The best result of validation accuracy that we got is S6 test.

#### 1.2 SGDM

##### Finding the best hyperparameters

Based on the results:

- batch size:
- momentum:
- weight decay:
- learing rate: 0.01

### 2. Compromise between SGDM and AdamW

To use the same data augmentation for both AdamW and SGDM we had to find a compromise:

- SGDM requires a more complex data augmentation technique
- AdamW requires a less complex one

These are the results of trying to invert the data augmentation technique for the two optimizer:

| Test #     | Epochs | batch_size | momentum/beta | weight_decay | learning_rate | results           |
| ---------- | ------ | ---------- | ------------- | ------------ | ------------- | ----------------- |
| V7 (AdamW) | 150    | 64         | 0.9           | 4e-4         | 1e-3          | Val Acc: 42.83%   |
| V8 (SGDM)  | 150    | 64         | 0.9           | 4e-4         | 1e-2          | The model overfit |

To get the best results for AdamW we have used:

```python
train_transform = transforms.Compose([
  transforms.RandomHorizontalFlip(0.5),
  transforms.RandomCrop(32,4),
  transforms.ColorJitter(brightness=0.2, contrast=0.2, saturation=0.2, hue=0.1),
  transforms.ToTensor(),
  transforms.Normalize((0.5, 0.5, 0.5), (0.5, 0.5, 0.5))
])
```

While for SGDM we have used:

```python
train_transform = transforms.Compose([
  transforms.RandomHorizontalFlip(),
  transforms.RandomRotation(15),
  transforms.RandomCrop(32, padding=4),
  transforms.RandomAffine(degrees=0, translate=(0.1, 0.1)),
  transforms.RandomPerspective(distortion_scale=0.2, p=0.5),
  transforms.ColorJitter(brightness=0.3, contrast=0.3, saturation=0.3, hue=0.2),
  transforms.ToTensor(),
  transforms.Normalize((0.5, 0.5, 0.5), (0.5, 0.5, 0.5))
])
```

#### 2.1 Final data augmentation technique

Starting from the SGDM transforms we got:

```python
train_transform = transforms.Compose([
  transforms.RandomHorizontalFlip(),
  transforms.RandomRotation(15),
  transforms.RandomCrop(32, padding=4),
  # transforms.RandomAffine(degrees=0, translate=(0.1, 0.1)),
  transforms.RandomPerspective(distortion_scale=0.2, p=0.5),
  transforms.ColorJitter(brightness=0.3, contrast=0.3, saturation=0.3, hue=0.2),
  transforms.ToTensor(),
  transforms.Normalize((0.5, 0.5, 0.5), (0.5, 0.5, 0.5))
])
```

Results:

| Test #     | Epochs | batch_size | beta | weight_decay | learning_rate | results         |
| ---------- | ------ | ---------- | ---- | ------------ | ------------- | --------------- |
| A1 (AdamW) | 150    | 64         | 0.9  | 5e-4         | 5e-4          | Val Acc: 45.94% |
| A1 (SGDM)  | 150    | 64         | 0.9  | 4e-4         | 1e-2          | Val Acc: 53.38% |

### Step 2 - Large batch optimizer

#### How does the code works?

#### 1. AdamW

#### 2. SGDM

#### 3. **LARS** (Layerwise Adaptive Rate Scaling)

- **Adaptive Learning Rate Mechanism**: LARS dynamically scales the learning rate based on the norm of weights and gradients from different layers.
- **Operation**:  
  The update rule in LARS can be expressed as:

  ```python
  x_t+1 = x_t - ηt * (g_t / ||g_t||) * φ(||x_t||)
  ```

  Where:

  - `x_t` is the parameter.
  - `g_t` is the gradient.
  - `ηt` is the adaptive learning rate.
  - `φ(||x_t||)` is a scaling function based on the norm of the parameters.

  Essentially, LARS adjusts the learning rate based on the norm of the parameters and gradients, eliminating the need for traditional schedulers.

---

#### 4. **LAMB** (Layer-wise Adaptive Moments Based Optimizer)

- **Adaptive Learning Rate Mechanism**: LAMB dynamically adjusts the learning rate for each layer. It uses exponential estimates of the mean and variance of gradients to scale the learning rate.
- **Operation**:  
  The adaptive learning rate in LAMB is calculated as:

  ```python
  x_t+1 = x_t - ηt * m_t / (sqrt(v_t) + ε)
  ```

  Where:

  - `m_t` and `v_t` are exponential estimates of mean and variance of gradients.
  - `ηt` is the adaptive learning rate.
  - `ε` is a regularization term to avoid division by zero.

  Like LARS, LAMB does not rely on conventional schedulers but instead dynamically adjusts the learning rate for each parameter.

---

### Step 3 - Switch to Local Methods
