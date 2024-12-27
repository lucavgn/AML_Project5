# ADM_Project5

## Distributed Learning - Track A

### Step 1 - Centralized training baseline

#### Steps to Tune Hyperparameters

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

#### AdamW

##### Finding the best hyperparameters

Based on the results:

- batch size:
- momentum:
- weight decay: 
  - between 1e-4 and 1e-2 ...
- learing rate: 
  - 1e-2 causes instability
  - betqween 1e-4 and 1e-3 ...

#### SGDM

##### Finding the best hyperparameters

Based on the results:

- batch size:
- momentum:
- weight decay:
- learing rate: 0.01

### Step 2 - Large batch optimizer

#### AdamW

#### SGDM

#### LAMB

#### LARS

### Step 3 - Switch to Local Methods
