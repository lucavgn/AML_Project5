# Hyperparameters tuning

- Batch Size: 128 -> 64 (We want to exclude a lower batch as it should increase the noise)
- Momentum: 0.9 -> 08 Should increase the past gradients effect
- Learning Rate: 1e-3
- Weigth Decay:
    
    - 1e-4 -> 5e-4
    - 1e-4 -> 1e-3
    - 1e-4 -> 1e-5 a smaller value should reduce overfitting between training accuracy and validation accuracy