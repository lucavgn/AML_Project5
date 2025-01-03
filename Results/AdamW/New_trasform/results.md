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
| A1     | 150    | 64         | 0.9  | 5e-4         | 5e-4          | Val Acc: 45.94% |

The best result of validation accuracy that we got is S6 test.

## Compromise between SGDM and AdamW

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

### Final data augmentation technique

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
