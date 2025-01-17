# Train with AdamW

## Train Loss

| #   | batch_size  | beta | weight_decay | learning_rate | train loss                                                         |
| --- | ----------- | ---- | ------------ | ------------- | ------------------------------------------------------------------ |
| 1   | 128         | 0.9  | 1e-2         | 1e-3          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-2/train_loss.png)  |
| 2   | 128         | 0.9  | 1e-4         | 1e-3          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-4/train_loss.png)  |
| 3   | 128         | 0.9  | 1e-5         | 1e-3          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-5/train_loss.png)  |
| 4   | 128         | 0.9  | 5e-4         | 1e-3          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=5e-4/train_loss.png)  |
| 5   | 128         | 0.9  | 1e-2         | 1e-4          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-4_wd=1e-2/train_loss.png)  |
| 6   | 128         | 0.9  | 1e-4         | 1e-4          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-4_wd=1e-4/train_loss.png)  |
| 7   | 64          | 0.9  | 1e-4         | 1e-3          | ![Plot](./Plot/e=150_bs=64_b=0.9_lr=1e-3_wd=1e-4/train_loss.png)   |
| 8   | 128         | 0.95 | 1e-4         | 1e-3          | ![Plot](./Plot/e=100_bs=128_b=0.95_lr=1e-3_wd=1e-4/train_loss.png) |
| 9   | 128         | 0.8  | 1e-4         | 1e-3          | ![Plot](./Plot/e=100_bs=128_b=0.8_lr=1e-3_wd=1e-4/train_loss.png)  |
| 10  | 128 dropout | 0.95 | 1e-4         | 1e-3          | ![Plot](./Plot/with_dropout_0.5/train_loss.png)                    |
| 11   | 128         | 0.95 | 1e-4         | 1e-3          | ![Plot](./Plot/new_trasform/train_loss.png)  |
|     |             |      |              |               |                                                                    |

## Validation Loss

| #   | batch_size  | beta | weight_decay | learning_rate | validation loss                                                  |
| --- | ----------- | ---- | ------------ | ------------- | ---------------------------------------------------------------- |
| 1   | 128         | 0.9  | 1e-2         | 1e-3          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-2/val_loss.png)  |
| 2   | 128         | 0.9  | 1e-4         | 1e-3          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-4/val_loss.png)  |
| 3   | 128         | 0.9  | 1e-5         | 1e-3          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-5/val_loss.png)  |
| 4   | 128         | 0.9  | 5e-4         | 1e-3          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=5e-4/val_loss.png)  |
| 5   | 128         | 0.9  | 1e-2         | 1e-4          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-4_wd=1e-2/val_loss.png)  |
| 6   | 128         | 0.9  | 1e-4         | 1e-4          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-4_wd=1e-4/val_loss.png)  |
| 7   | 64          | 0.9  | 1e-4         | 1e-3          | ![Plot](./Plot/e=150_bs=64_b=0.9_lr=1e-3_wd=1e-4/val_loss.png)   |
| 8   | 128         | 0.95 | 1e-4         | 1e-3          | ![Plot](./Plot/e=100_bs=128_b=0.95_lr=1e-3_wd=1e-4/val_loss.png) |
| 9   | 128         | 0.8  | 1e-4         | 1e-3          | ![Plot](./Plot/e=100_bs=128_b=0.8_lr=1e-3_wd=1e-4/val_loss.png)  |
| 10  | 128 dropout | 0.95 | 1e-4         | 1e-3          | ![Plot](./Plot/with_dropout_0.5/val_loss.png)                    |
| 11   | 128         | 0.95 | 1e-4         | 1e-3          | ![Plot](./Plot/new_trasform/val_loss.png)  |
|     |             |      |              |               |                                                                  |

## Test Loss

| #   | batch_size  | beta | weight_decay | learning_rate | test loss                                                         |
| --- | ----------- | ---- | ------------ | ------------- | ----------------------------------------------------------------- |
| 1   | 128         | 0.9  | 1e-2         | 1e-3          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-2/test_loss.png)  |
| 2   | 128         | 0.9  | 1e-4         | 1e-3          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-4/test_loss.png)  |
| 3   | 128         | 0.9  | 1e-5         | 1e-3          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-5/test_loss.png)  |
| 4   | 128         | 0.9  | 5e-4         | 1e-3          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=5e-4/test_loss.png)  |
| 5   | 128         | 0.9  | 1e-2         | 1e-4          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-4_wd=1e-2/test_loss.png)  |
| 6   | 128         | 0.9  | 1e-4         | 1e-4          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-4_wd=1e-4/test_loss.png)  |
| 7   | 64          | 0.9  | 1e-4         | 1e-3          | ![Plot](./Plot/e=150_bs=64_b=0.9_lr=1e-3_wd=1e-4/test_loss.png)   |
| 8   | 128         | 0.95 | 1e-4         | 1e-3          | ![Plot](./Plot/e=100_bs=128_b=0.95_lr=1e-3_wd=1e-4/test_loss.png) |
| 9   | 128         | 0.8  | 1e-4         | 1e-3          | ![Plot](./Plot/e=100_bs=128_b=0.8_lr=1e-3_wd=1e-4/test_loss.png)  |
| 10  | 128 dropout | 0.95 | 1e-4         | 1e-3          | ![Plot](./Plot/with_dropout_0.5/test_loss.png)                    |
| 11   | 128         | 0.95 | 1e-4         | 1e-3          | ![Plot](./Plot/new_trasform/test_loss.png)  |
|     |             |      |              |               |                                                                   |

## Train Accuracy

| #   | batch_size  | beta | weight_decay | learning_rate | train accuracy                                                         |
| --- | ----------- | ---- | ------------ | ------------- | ---------------------------------------------------------------------- |
| 1   | 128         | 0.9  | 1e-2         | 1e-3          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-2/train_accuracy.png)  |
| 2   | 128         | 0.9  | 1e-4         | 1e-3          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-4/train_accuracy.png)  |
| 3   | 128         | 0.9  | 1e-5         | 1e-3          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-5/train_accuracy.png)  |
| 4   | 128         | 0.9  | 5e-4         | 1e-3          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=5e-4/train_accuracy.png)  |
| 5   | 128         | 0.9  | 1e-2         | 1e-4          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-4_wd=1e-2/train_accuracy.png)  |
| 6   | 128         | 0.9  | 1e-4         | 1e-4          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-4_wd=1e-4/train_accuracy.png)  |
| 7   | 64          | 0.9  | 1e-4         | 1e-3          | ![Plot](./Plot/e=150_bs=64_b=0.9_lr=1e-3_wd=1e-4/train_accuracy.png)   |
| 8   | 128         | 0.95 | 1e-4         | 1e-3          | ![Plot](./Plot/e=100_bs=128_b=0.95_lr=1e-3_wd=1e-4/train_accuracy.png) |
| 9   | 128         | 0.8  | 1e-4         | 1e-3          | ![Plot](./Plot/e=100_bs=128_b=0.8_lr=1e-3_wd=1e-4/train_accuracy.png)  |
| 10  | 128 dropout | 0.95 | 1e-4         | 1e-3          | ![Plot](./Plot/with_dropout_0.5/train_accuracy.png)                    |
| 11   | 128         | 0.95 | 1e-4         | 1e-3          | ![Plot](./Plot/new_trasform/train_accuracy.png)  |
|     |             |      |              |               |                                                                        |

## Validation Accuracy

| #   | batch_size  | beta | weight_decay | learning_rate | validation accuracy                                                  |
| --- | ----------- | ---- | ------------ | ------------- | -------------------------------------------------------------------- |
| 1   | 128         | 0.9  | 1e-2         | 1e-3          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-2/val_accuracy.png)  |
| 2   | 128         | 0.9  | 1e-4         | 1e-3          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-4/val_accuracy.png)  |
| 3   | 128         | 0.9  | 1e-5         | 1e-3          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-5/val_accuracy.png)  |
| 4   | 128         | 0.9  | 5e-4         | 1e-3          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=5e-4/val_accuracy.png)  |
| 5   | 128         | 0.9  | 1e-2         | 1e-4          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-4_wd=1e-2/val_accuracy.png)  |
| 6   | 128         | 0.9  | 1e-4         | 1e-4          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-4_wd=1e-4/val_accuracy.png)  |
| 7   | 64          | 0.9  | 1e-4         | 1e-3          | ![Plot](./Plot/e=150_bs=64_b=0.9_lr=1e-3_wd=1e-4/val_accuracy.png)   |
| 8   | 128         | 0.95 | 1e-4         | 1e-3          | ![Plot](./Plot/e=100_bs=128_b=0.95_lr=1e-3_wd=1e-4/val_accuracy.png) |
| 9   | 128         | 0.8  | 1e-4         | 1e-3          | ![Plot](./Plot/e=100_bs=128_b=0.8_lr=1e-3_wd=1e-4/val_accuracy.png)  |
| 10  | 128 dropout | 0.95 | 1e-4         | 1e-3          | ![Plot](./Plot/with_dropout_0.5/val_accuracy.png)                    |
| 11   | 128         | 0.95 | 1e-4         | 1e-3          | ![Plot](./Plot/new_trasform/val_accuracy.png)  |
|     |             |      |              |               |                                                                      |

## Test Accuracy

| #   | batch_size  | beta | weight_decay | learning_rate | test accuracy                                                         |
| --- | ----------- | ---- | ------------ | ------------- | --------------------------------------------------------------------- |
| 1   | 128         | 0.9  | 1e-2         | 1e-3          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-2/test_accuracy.png)  |
| 2   | 128         | 0.9  | 1e-4         | 1e-3          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-4/test_accuracy.png)  |
| 3   | 128         | 0.9  | 1e-5         | 1e-3          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-5/test_accuracy.png)  |
| 4   | 128         | 0.9  | 5e-4         | 1e-3          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=5e-4/test_accuracy.png)  |
| 5   | 128         | 0.9  | 1e-2         | 1e-4          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-4_wd=1e-2/test_accuracy.png)  |
| 6   | 128         | 0.9  | 1e-4         | 1e-4          | ![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-4_wd=1e-4/test_accuracy.png)  |
| 7   | 64          | 0.9  | 1e-4         | 1e-3          | ![Plot](./Plot/e=150_bs=64_b=0.9_lr=1e-3_wd=1e-4/test_accuracy.png)   |
| 8   | 128         | 0.95 | 1e-4         | 1e-3          | ![Plot](./Plot/e=100_bs=128_b=0.95_lr=1e-3_wd=1e-4/test_accuracy.png) |
| 9   | 128         | 0.8  | 1e-4         | 1e-3          | ![Plot](./Plot/e=100_bs=128_b=0.8_lr=1e-3_wd=1e-4/test_accuracy.png)  |
| 10  | 128 dropout | 0.95 | 1e-4         | 1e-3          | ![Plot](./Plot/with_dropout_0.5/test_accuracy.png)                    |
| 11   | 128         | 0.95 | 1e-4         | 1e-3          | ![Plot](./Plot/new_trasform/test_accuracy.png)  |
|     |             |      |              |               |                                                                       |
