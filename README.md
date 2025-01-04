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
| S7     | 150    | 64         | 0.9  | 4e-4         | 5e-4          | Val Acc: 47.38% |
| S8     | 150    | 64         | 0.9  | 1e-2         | 5e-4          | Val Acc: 50%    |

The best result of validation accuracy that we got is S8 test.

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

If we invert the data augmentation technique for the two optimizer:

- SGDM: the model overfit
- AdamW: the validation accuracy drop down to 42.83%

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

#### Final data augmentation technique

Starting from the SGDM transforms we got:

```python
train_transform = transforms.Compose([
  transforms.RandomHorizontalFlip(),
  # transforms.RandomRotation(15),
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
| S8 (AdamW) | 150    | 64         | 0.9  | 1e-2         | 5e-4          | Val Acc: 50.00% |
| A3 (SGDM)  | 150    | 64         | 0.9  | 4e-4         | 1e-2          | Val Acc: 54.09% |

### Step 2 - Large batch optimizer

#### 1. AdamW

#### 2. SGDM

Here’s an updated and accurate description of the LARS algorithm based on the provided image:

---

#### 3. **LARS** (Layerwise Adaptive Rate Scaling)

- **Adaptive Learning Rate Mechanism**:  
  LARS dynamically adjusts the learning rate for each layer by scaling it according to the ratio of the norm of the weights and the norm of the gradients, ensuring consistent scaling across layers.

- **Operation**:  
  The algorithm consists of the following steps:

  1. **Gradient Computation**:  
     Compute the gradient \( g*t \) as the mean over a batch \( S_t \):  
     \[
     g_t = \frac{1}{|S_t|} \sum*{s_t \in S_t} \nabla \ell(x_t, s_t)
     \]

  2. **Momentum Update**:  
     Update the momentum term \( m*t \):  
     \[
     m_t = \beta_1 m*{t-1} + (1 - \beta_1) (g_t + \lambda x_t)
     \]

  - \( \lambda \): A weight decay term for regularization.

  3. **Normalized Update**:  
     Update the parameters using a normalized update rule:  
     \[
     x\_{t+1}^{(i)} = x_t^{(i)} - \eta_t \cdot \phi(\|x_t^{(i)}\|) \cdot \frac{m_t^{(i)}}{\|m_t^{(i)}\|}
     \]

  - \( \eta_t \): The global learning rate.
  - \(\phi(\|x_t\|)\) is a scaling function based on the norm of the parameters.

- **Advantages**:  
  LARS ensures that each layer's updates are scaled appropriately, improving optimization stability, particularly in large-scale models. By scaling updates based on the norm of parameters and gradients, it eliminates the reliance on traditional learning rate schedulers and ensures effective training across varying parameter scales.

---

#### 4. **LAMB** (Layer-wise Adaptive Moments Based Optimizer)

- **Adaptive Learning Rate Mechanism**: LAMB dynamically adjusts the update step's scale for each layer based on the norms of the weights and gradients. It also utilizes exponential moving averages of the mean (\(m_t\)) and variance (\(v_t\)) of the gradients.

- **Operation**:  
  The algorithm follows these steps:

  1. Compute the gradient \(g*t\) as the mean over a batch \(S_t\):  
     \[
     g_t = \frac{1}{|S_t|} \sum*{s_t \in S_t} \nabla \ell(x_t, s_t)
     \]

  2. Update the moments:  
     \[
     m*t = \beta_1 m*{t-1} + (1 - \beta*1) g_t, \quad v_t = \beta_2 v*{t-1} + (1 - \beta_2) g_t^2
     \]
     And apply bias correction:  
     \[
     m_t = \frac{m_t}{1 - \beta_1^t}, \quad v_t = \frac{v_t}{1 - \beta_2^t}
     \]

  3. Compute \(r_t\):  
     \[
     r_t = \frac{m_t}{\sqrt{v_t} + \epsilon}
     \]

  4. Calculate the normalized update step:  
     \[
     x\_{t+1} = x_t - \eta_t \cdot \phi(\|x_t\|) \cdot \frac{r_t + \lambda x_t}{\|r_t + \lambda x_t\|}
     \]

  Where:

  - \(\phi(\|x_t\|)\) is a scaling function that depends on the \(L2\) norm of the weights \(x_t\).
  - \(\eta_t\) is the global learning rate.
  - \(\lambda\) is an additional regularization term.

- **Advantages**:  
  Similar to LARS, LAMB does not rely exclusively on conventional schedulers but dynamically adjusts the update step's scale for each parameter, improving convergence, especially in large-scale model.

---

### Step 3 - Switch to Local Methods
