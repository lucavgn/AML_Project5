# Train with AdamW

These tests have been performed with different data augmentation parameters and functions in order to provide the best results for the LeNet-5 model.

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

The best results we got is S6 test