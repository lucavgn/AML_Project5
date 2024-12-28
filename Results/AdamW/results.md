# Train with AdamW without the seed

| Epochs | batch_size | beta | weight_decay | learning_rate |
| ------ | ---------- | ---- | ------------ | ------------- |
| 150    | 128        | 0.9  | 1e-4         | 1e-2          |
#### Results log

- Epoch 1/150, Loss: 4.3285, Train Acc: 4.33%, Val Acc: 7.18%
- Epoch 2/150, Loss: 4.0047, Train Acc: 8.98%, Val Acc: 10.55%
- Epoch 3/150, Loss: 3.8485, Train Acc: 11.25%, Val Acc: 11.94%
- Epoch 4/150, Loss: 3.7448, Train Acc: 12.93%, Val Acc: 14.42%
- Epoch 5/150, Loss: 3.6495, Train Acc: 14.53%, Val Acc: 14.88%
- Epoch 6/150, Loss: 3.5583, Train Acc: 16.08%, Val Acc: 16.24%
- Epoch 7/150, Loss: 3.4883, Train Acc: 17.40%, Val Acc: 17.71%
- Epoch 8/150, Loss: 3.4288, Train Acc: 18.61%, Val Acc: 18.19%
- Epoch 9/150, Loss: 3.3776, Train Acc: 19.40%, Val Acc: 19.12%
- Epoch 10/150, Loss: 3.3297, Train Acc: 20.05%, Val Acc: 20.01%
- Epoch 11/150, Loss: 3.2820, Train Acc: 20.95%, Val Acc: 20.61%
- Epoch 12/150, Loss: 3.2486, Train Acc: 21.61%, Val Acc: 21.71%
- Epoch 13/150, Loss: 3.2117, Train Acc: 22.30%, Val Acc: 22.14%
- Epoch 14/150, Loss: 3.1810, Train Acc: 23.21%, Val Acc: 22.78%
- Epoch 15/150, Loss: 3.1449, Train Acc: 23.51%, Val Acc: 23.39%
- Epoch 16/150, Loss: 3.1031, Train Acc: 24.25%, Val Acc: 24.09%
- Epoch 17/150, Loss: 3.0822, Train Acc: 24.50%, Val Acc: 24.22%
- Epoch 18/150, Loss: 3.0494, Train Acc: 25.25%, Val Acc: 24.63%
- Epoch 19/150, Loss: 3.0150, Train Acc: 26.04%, Val Acc: 25.43%
- Epoch 20/150, Loss: 2.9939, Train Acc: 26.34%, Val Acc: 25.44%
- Epoch 21/150, Loss: 2.9513, Train Acc: 27.13%, Val Acc: 25.82%
- Epoch 22/150, Loss: 2.9404, Train Acc: 27.48%, Val Acc: 26.50%
- Epoch 23/150, Loss: 2.9024, Train Acc: 27.84%, Val Acc: 26.24%
- Epoch 24/150, Loss: 2.8853, Train Acc: 28.46%, Val Acc: 27.84%
- Epoch 25/150, Loss: 2.8563, Train Acc: 29.15%, Val Acc: 27.93%
- Epoch 26/150, Loss: 2.8308, Train Acc: 29.27%, Val Acc: 27.43%
- Epoch 27/150, Loss: 2.8103, Train Acc: 30.04%, Val Acc: 28.15%
- Epoch 28/150, Loss: 2.7925, Train Acc: 30.19%, Val Acc: 29.25%
- Epoch 29/150, Loss: 2.7645, Train Acc: 30.80%, Val Acc: 29.44%
- Epoch 30/150, Loss: 2.7512, Train Acc: 30.94%, Val Acc: 29.70%
- Epoch 31/150, Loss: 2.7237, Train Acc: 31.67%, Val Acc: 29.65%
- Epoch 32/150, Loss: 2.7034, Train Acc: 32.00%, Val Acc: 30.17%
- Epoch 33/150, Loss: 2.6878, Train Acc: 32.02%, Val Acc: 30.00%
- Epoch 34/150, Loss: 2.6744, Train Acc: 32.44%, Val Acc: 30.20%
- Epoch 35/150, Loss: 2.6531, Train Acc: 33.05%, Val Acc: 30.68%
- Epoch 36/150, Loss: 2.6318, Train Acc: 33.47%, Val Acc: 31.34%
- Epoch 37/150, Loss: 2.6188, Train Acc: 33.87%, Val Acc: 31.46%
- Epoch 38/150, Loss: 2.6040, Train Acc: 33.90%, Val Acc: 31.64%
- Epoch 39/150, Loss: 2.5936, Train Acc: 34.17%, Val Acc: 31.53%
- Epoch 40/150, Loss: 2.5743, Train Acc: 34.81%, Val Acc: 32.18%
- Epoch 41/150, Loss: 2.5608, Train Acc: 34.97%, Val Acc: 32.90%
- Epoch 42/150, Loss: 2.5531, Train Acc: 35.28%, Val Acc: 32.19%
- Epoch 43/150, Loss: 2.5340, Train Acc: 35.52%, Val Acc: 32.34%
- Epoch 44/150, Loss: 2.5383, Train Acc: 35.40%, Val Acc: 32.97%
- Epoch 45/150, Loss: 2.5124, Train Acc: 35.89%, Val Acc: 33.05%
- Epoch 46/150, Loss: 2.4982, Train Acc: 36.44%, Val Acc: 32.71%
- Epoch 47/150, Loss: 2.4945, Train Acc: 36.25%, Val Acc: 33.34%
- Epoch 48/150, Loss: 2.4845, Train Acc: 36.79%, Val Acc: 33.53%
- Epoch 49/150, Loss: 2.4745, Train Acc: 36.63%, Val Acc: 34.09%
- Epoch 50/150, Loss: 2.4679, Train Acc: 37.05%, Val Acc: 33.71%
- Epoch 51/150, Loss: 2.4521, Train Acc: 37.41%, Val Acc: 33.84%
- Epoch 52/150, Loss: 2.4410, Train Acc: 37.34%, Val Acc: 33.90%
- Epoch 53/150, Loss: 2.4312, Train Acc: 37.71%, Val Acc: 34.64%
- Epoch 54/150, Loss: 2.4191, Train Acc: 37.90%, Val Acc: 34.43%
- Epoch 55/150, Loss: 2.4120, Train Acc: 38.07%, Val Acc: 34.41%
- Epoch 56/150, Loss: 2.4019, Train Acc: 38.32%, Val Acc: 35.03%
- Epoch 57/150, Loss: 2.3891, Train Acc: 38.37%, Val Acc: 35.35%
- Epoch 58/150, Loss: 2.3862, Train Acc: 38.59%, Val Acc: 34.79%
- Epoch 59/150, Loss: 2.3748, Train Acc: 38.71%, Val Acc: 34.94%
- Epoch 60/150, Loss: 2.3663, Train Acc: 39.07%, Val Acc: 34.92%
- Epoch 61/150, Loss: 2.3595, Train Acc: 39.34%, Val Acc: 35.26%
- Epoch 62/150, Loss: 2.3576, Train Acc: 39.12%, Val Acc: 35.52%
- Epoch 63/150, Loss: 2.3503, Train Acc: 39.45%, Val Acc: 35.57%
- Epoch 64/150, Loss: 2.3394, Train Acc: 39.56%, Val Acc: 35.16%
- Epoch 65/150, Loss: 2.3321, Train Acc: 39.58%, Val Acc: 35.66%
- Epoch 66/150, Loss: 2.3190, Train Acc: 40.23%, Val Acc: 35.92%
- Epoch 67/150, Loss: 2.3079, Train Acc: 40.27%, Val Acc: 36.16%
- Epoch 68/150, Loss: 2.3058, Train Acc: 40.35%, Val Acc: 35.57%
- Epoch 69/150, Loss: 2.2979, Train Acc: 40.09%, Val Acc: 35.77%
- Epoch 70/150, Loss: 2.2960, Train Acc: 40.79%, Val Acc: 35.78%
- Epoch 71/150, Loss: 2.2912, Train Acc: 40.66%, Val Acc: 36.08%
- Epoch 72/150, Loss: 2.2810, Train Acc: 40.56%, Val Acc: 35.77%
- Epoch 73/150, Loss: 2.2701, Train Acc: 41.29%, Val Acc: 36.24%
- Epoch 74/150, Loss: 2.2697, Train Acc: 41.32%, Val Acc: 36.16%
- Epoch 75/150, Loss: 2.2596, Train Acc: 41.26%, Val Acc: 35.98%
- Epoch 76/150, Loss: 2.2482, Train Acc: 41.57%, Val Acc: 37.02%
- Epoch 77/150, Loss: 2.2406, Train Acc: 41.86%, Val Acc: 36.69%
- Epoch 78/150, Loss: 2.2405, Train Acc: 41.60%, Val Acc: 36.78%
- Epoch 79/150, Loss: 2.2316, Train Acc: 41.88%, Val Acc: 36.83%
- Epoch 80/150, Loss: 2.2285, Train Acc: 42.07%, Val Acc: 36.76%
- Epoch 81/150, Loss: 2.2281, Train Acc: 41.84%, Val Acc: 36.80%
- Epoch 82/150, Loss: 2.2128, Train Acc: 42.17%, Val Acc: 37.25%
- Epoch 83/150, Loss: 2.2159, Train Acc: 42.35%, Val Acc: 37.48%
- Epoch 84/150, Loss: 2.2069, Train Acc: 42.67%, Val Acc: 37.32%
- Epoch 85/150, Loss: 2.2069, Train Acc: 42.35%, Val Acc: 37.59%
- Epoch 86/150, Loss: 2.1941, Train Acc: 42.84%, Val Acc: 37.39%
- Epoch 87/150, Loss: 2.1997, Train Acc: 42.70%, Val Acc: 37.73%
- Epoch 88/150, Loss: 2.1881, Train Acc: 42.93%, Val Acc: 36.86%
- Epoch 89/150, Loss: 2.1856, Train Acc: 42.97%, Val Acc: 37.23%
- Epoch 90/150, Loss: 2.1818, Train Acc: 42.95%, Val Acc: 37.77%
- Epoch 91/150, Loss: 2.1694, Train Acc: 43.25%, Val Acc: 37.87%
- Epoch 92/150, Loss: 2.1725, Train Acc: 43.13%, Val Acc: 37.49%
- Epoch 93/150, Loss: 2.1667, Train Acc: 43.45%, Val Acc: 38.06%
- Epoch 94/150, Loss: 2.1678, Train Acc: 43.10%, Val Acc: 38.20%
- Epoch 95/150, Loss: 2.1651, Train Acc: 43.77%, Val Acc: 37.93%
- Epoch 96/150, Loss: 2.1526, Train Acc: 43.66%, Val Acc: 37.81%
- Epoch 97/150, Loss: 2.1527, Train Acc: 43.69%, Val Acc: 37.86%
- Epoch 98/150, Loss: 2.1455, Train Acc: 43.55%, Val Acc: 37.73%
- Epoch 99/150, Loss: 2.1509, Train Acc: 43.96%, Val Acc: 37.89%
- Epoch 100/150, Loss: 2.1441, Train Acc: 43.95%, Val Acc: 38.20%
- Epoch 101/150, Loss: 2.1397, Train Acc: 43.94%, Val Acc: 38.87%
- Epoch 102/150, Loss: 2.1308, Train Acc: 44.25%, Val Acc: 38.59%
- Epoch 103/150, Loss: 2.1321, Train Acc: 44.11%, Val Acc: 37.54%
- Epoch 104/150, Loss: 2.1334, Train Acc: 44.02%, Val Acc: 38.25%
- Epoch 105/150, Loss: 2.1197, Train Acc: 44.58%, Val Acc: 37.96%
- Epoch 106/150, Loss: 2.1228, Train Acc: 44.44%, Val Acc: 38.30%
- Epoch 107/150, Loss: 2.1226, Train Acc: 44.24%, Val Acc: 38.62%
- Epoch 108/150, Loss: 2.1245, Train Acc: 44.37%, Val Acc: 38.55%
- Epoch 109/150, Loss: 2.1184, Train Acc: 44.51%, Val Acc: 38.41%
- Epoch 110/150, Loss: 2.1135, Train Acc: 44.40%, Val Acc: 38.89%
- Epoch 111/150, Loss: 2.1094, Train Acc: 44.63%, Val Acc: 38.82%
- Epoch 112/150, Loss: 2.1084, Train Acc: 44.82%, Val Acc: 37.80%
- Epoch 113/150, Loss: 2.1049, Train Acc: 45.17%, Val Acc: 38.95%
- Epoch 114/150, Loss: 2.1021, Train Acc: 44.59%, Val Acc: 38.25%
- Epoch 115/150, Loss: 2.0970, Train Acc: 44.88%, Val Acc: 38.50%
- Epoch 116/150, Loss: 2.0999, Train Acc: 44.90%, Val Acc: 38.27%
- Epoch 117/150, Loss: 2.0882, Train Acc: 45.12%, Val Acc: 38.69%
- Epoch 118/150, Loss: 2.0944, Train Acc: 44.93%, Val Acc: 38.29%
- Epoch 119/150, Loss: 2.0895, Train Acc: 45.01%, Val Acc: 39.11%
- Epoch 120/150, Loss: 2.0888, Train Acc: 44.91%, Val Acc: 38.85%
- Epoch 121/150, Loss: 2.0911, Train Acc: 44.69%, Val Acc: 38.56%
- Epoch 122/150, Loss: 2.0922, Train Acc: 45.05%, Val Acc: 38.41%
- Epoch 123/150, Loss: 2.0860, Train Acc: 45.15%, Val Acc: 39.08%
- Epoch 124/150, Loss: 2.0876, Train Acc: 45.03%, Val Acc: 38.49%
- Epoch 125/150, Loss: 2.0890, Train Acc: 45.12%, Val Acc: 38.50%
- Epoch 126/150, Loss: 2.0800, Train Acc: 45.44%, Val Acc: 38.75%
- Epoch 127/150, Loss: 2.0777, Train Acc: 45.67%, Val Acc: 38.96%
- Epoch 128/150, Loss: 2.0813, Train Acc: 45.38%, Val Acc: 38.46%
- Epoch 129/150, Loss: 2.0778, Train Acc: 45.44%, Val Acc: 38.56%
- Epoch 130/150, Loss: 2.0781, Train Acc: 45.50%, Val Acc: 39.01%
- Epoch 131/150, Loss: 2.0724, Train Acc: 45.33%, Val Acc: 38.68%
- Epoch 132/150, Loss: 2.0789, Train Acc: 45.22%, Val Acc: 39.29%
- Epoch 133/150, Loss: 2.0730, Train Acc: 45.82%, Val Acc: 39.26%
- Epoch 134/150, Loss: 2.0821, Train Acc: 45.23%, Val Acc: 39.06%
- Epoch 135/150, Loss: 2.0685, Train Acc: 45.58%, Val Acc: 38.93%
- Epoch 136/150, Loss: 2.0757, Train Acc: 45.58%, Val Acc: 39.18%
- Epoch 137/150, Loss: 2.0706, Train Acc: 45.71%, Val Acc: 38.40%
- Epoch 138/150, Loss: 2.0753, Train Acc: 45.45%, Val Acc: 38.20%
- Epoch 139/150, Loss: 2.0707, Train Acc: 45.34%, Val Acc: 38.86%
- Epoch 140/150, Loss: 2.0709, Train Acc: 45.49%, Val Acc: 39.62%
- Epoch 141/150, Loss: 2.0716, Train Acc: 45.45%, Val Acc: 38.71%
- Epoch 142/150, Loss: 2.0705, Train Acc: 45.46%, Val Acc: 38.53%
- Epoch 143/150, Loss: 2.0706, Train Acc: 45.66%, Val Acc: 39.13%
- Epoch 144/150, Loss: 2.0771, Train Acc: 45.12%, Val Acc: 39.20%
- Epoch 145/150, Loss: 2.0710, Train Acc: 45.60%, Val Acc: 38.84%
- Epoch 146/150, Loss: 2.0688, Train Acc: 45.66%, Val Acc: 39.64%
- Epoch 147/150, Loss: 2.0628, Train Acc: 45.67%, Val Acc: 38.76%
- Epoch 148/150, Loss: 2.0719, Train Acc: 45.42%, Val Acc: 39.50%
- Epoch 149/150, Loss: 2.0720, Train Acc: 45.42%, Val Acc: 38.83%
- Epoch 150/150, Loss: 2.0793, Train Acc: 45.28%, Val Acc: 38.31%

#### Plots

![Plot Loss](./Plot/Train_Validation_Loss_epochs%20=%20150%20_batch_size%20=%20128%20_momentum%20=%200.9%20_weight_decay%20=%201e-2%20_lr=%201e-4.PNG)

![Plot Accuracy](./Plot/Train_Validation_Accuracy_epochs%20=%20150%20_batch_size%20=%20128%20_momentum%20=%200.9%20_weight_decay%20=%201e-2%20_lr=%201e-4.PNG)

# Train with AdamW

| Epochs | batch_size | beta | weight_decay | learning_rate |
| ------ | ---------- | ---- | ------------ | ------------- |
| 150    | 128        | 0.9  | 1e-2         | 1e-4          |

#### Results log

Epoch 1/150, Loss: 4.3241, Train Acc: 4.59%, Val Acc: 7.46%, Test Acc: 6.63%  
Epoch 2/150, Loss: 4.0331, Train Acc: 8.63%, Val Acc: 9.92%, Test Acc: 10.21%  
Epoch 3/150, Loss: 3.9021, Train Acc: 10.69%, Val Acc: 11.16%, Test Acc: 11.26%  
Epoch 4/150, Loss: 3.7939, Train Acc: 12.26%, Val Acc: 13.43%, Test Acc: 13.50%  
Epoch 5/150, Loss: 3.6964, Train Acc: 13.81%, Val Acc: 14.98%, Test Acc: 14.76%  
Epoch 6/150, Loss: 3.6096, Train Acc: 15.23%, Val Acc: 15.52%, Test Acc: 15.56%  
Epoch 7/150, Loss: 3.5380, Train Acc: 16.58%, Val Acc: 17.12%, Test Acc: 16.39%  
Epoch 8/150, Loss: 3.4715, Train Acc: 17.53%, Val Acc: 17.46%, Test Acc: 18.16%  
Epoch 9/150, Loss: 3.4195, Train Acc: 18.55%, Val Acc: 19.07%, Test Acc: 18.58%  
Checkpoint saved at epoch 10
Epoch 10/150, Loss: 3.3717, Train Acc: 19.55%, Val Acc: 19.37%, Test Acc: 19.51%  
Epoch 11/150, Loss: 3.3299, Train Acc: 20.20%, Val Acc: 20.33%, Test Acc: 20.15%  
Epoch 12/150, Loss: 3.2878, Train Acc: 21.07%, Val Acc: 20.69%, Test Acc: 21.46%  
Epoch 13/150, Loss: 3.2533, Train Acc: 21.38%, Val Acc: 21.15%, Test Acc: 21.32%  
Epoch 14/150, Loss: 3.2143, Train Acc: 22.40%, Val Acc: 21.28%, Test Acc: 22.31%  
Epoch 15/150, Loss: 3.1878, Train Acc: 22.86%, Val Acc: 22.24%, Test Acc: 22.56%  
Epoch 16/150, Loss: 3.1580, Train Acc: 23.25%, Val Acc: 23.23%, Test Acc: 22.91%  
Epoch 17/150, Loss: 3.1281, Train Acc: 24.07%, Val Acc: 23.20%, Test Acc: 22.99%  
Epoch 18/150, Loss: 3.0953, Train Acc: 24.40%, Val Acc: 23.66%, Test Acc: 24.26%  
Epoch 19/150, Loss: 3.0726, Train Acc: 24.97%, Val Acc: 24.11%, Test Acc: 24.43%  
Checkpoint saved at epoch 20
Epoch 20/150, Loss: 3.0480, Train Acc: 25.38%, Val Acc: 24.75%, Test Acc: 25.24%  
Epoch 21/150, Loss: 3.0223, Train Acc: 25.77%, Val Acc: 24.72%, Test Acc: 24.86%  
Epoch 22/150, Loss: 2.9918, Train Acc: 26.36%, Val Acc: 26.04%, Test Acc: 25.49%  
Epoch 23/150, Loss: 2.9606, Train Acc: 27.04%, Val Acc: 26.13%, Test Acc: 26.47%  
Epoch 24/150, Loss: 2.9369, Train Acc: 27.61%, Val Acc: 27.19%, Test Acc: 26.67%  
Epoch 25/150, Loss: 2.9143, Train Acc: 28.20%, Val Acc: 27.13%, Test Acc: 27.10%  
Epoch 26/150, Loss: 2.8918, Train Acc: 28.47%, Val Acc: 27.28%, Test Acc: 27.14%  
Epoch 27/150, Loss: 2.8609, Train Acc: 28.92%, Val Acc: 28.35%, Test Acc: 28.03%  
Epoch 28/150, Loss: 2.8401, Train Acc: 29.43%, Val Acc: 28.23%, Test Acc: 28.54%  
Epoch 29/150, Loss: 2.8105, Train Acc: 29.95%, Val Acc: 28.49%, Test Acc: 28.92%  
Checkpoint saved at epoch 30
Epoch 30/150, Loss: 2.7920, Train Acc: 30.20%, Val Acc: 28.78%, Test Acc: 29.59%  
Epoch 31/150, Loss: 2.7665, Train Acc: 30.84%, Val Acc: 29.23%, Test Acc: 29.72%  
Epoch 32/150, Loss: 2.7479, Train Acc: 31.11%, Val Acc: 29.19%, Test Acc: 30.35%  
Epoch 33/150, Loss: 2.7289, Train Acc: 31.52%, Val Acc: 29.81%, Test Acc: 30.44%  
Epoch 34/150, Loss: 2.7118, Train Acc: 32.15%, Val Acc: 30.74%, Test Acc: 30.69%  
Epoch 35/150, Loss: 2.6982, Train Acc: 32.24%, Val Acc: 29.90%, Test Acc: 30.32%  
Epoch 36/150, Loss: 2.6787, Train Acc: 32.81%, Val Acc: 29.70%, Test Acc: 29.98%  
Epoch 37/150, Loss: 2.6634, Train Acc: 32.91%, Val Acc: 30.56%, Test Acc: 31.35%  
Epoch 38/150, Loss: 2.6493, Train Acc: 33.11%, Val Acc: 31.35%, Test Acc: 32.10%  
Epoch 39/150, Loss: 2.6314, Train Acc: 33.45%, Val Acc: 31.77%, Test Acc: 32.07%  
Checkpoint saved at epoch 40
Epoch 40/150, Loss: 2.6186, Train Acc: 33.87%, Val Acc: 31.78%, Test Acc: 32.40%  
Epoch 41/150, Loss: 2.5994, Train Acc: 34.26%, Val Acc: 31.83%, Test Acc: 32.25%  
Epoch 42/150, Loss: 2.5864, Train Acc: 34.40%, Val Acc: 32.38%, Test Acc: 32.15%  
Epoch 43/150, Loss: 2.5801, Train Acc: 34.94%, Val Acc: 31.51%, Test Acc: 32.45%  
Epoch 44/150, Loss: 2.5625, Train Acc: 35.11%, Val Acc: 31.77%, Test Acc: 32.92%  
Epoch 45/150, Loss: 2.5535, Train Acc: 35.32%, Val Acc: 32.67%, Test Acc: 33.04%  
Epoch 46/150, Loss: 2.5379, Train Acc: 35.63%, Val Acc: 33.04%, Test Acc: 33.42%  
Epoch 47/150, Loss: 2.5238, Train Acc: 35.85%, Val Acc: 32.75%, Test Acc: 33.26%  
Epoch 48/150, Loss: 2.5145, Train Acc: 35.68%, Val Acc: 33.06%, Test Acc: 33.62%  
Epoch 49/150, Loss: 2.5013, Train Acc: 36.23%, Val Acc: 32.84%, Test Acc: 33.97%  
Checkpoint saved at epoch 50
Epoch 50/150, Loss: 2.4973, Train Acc: 36.35%, Val Acc: 33.25%, Test Acc: 34.21%  
Epoch 51/150, Loss: 2.4818, Train Acc: 36.31%, Val Acc: 33.80%, Test Acc: 33.67%  
Epoch 52/150, Loss: 2.4706, Train Acc: 36.94%, Val Acc: 33.32%, Test Acc: 33.93%  
Epoch 53/150, Loss: 2.4668, Train Acc: 36.91%, Val Acc: 34.12%, Test Acc: 34.69%  
Epoch 54/150, Loss: 2.4512, Train Acc: 37.38%, Val Acc: 34.08%, Test Acc: 34.12%  
Epoch 55/150, Loss: 2.4476, Train Acc: 37.27%, Val Acc: 34.25%, Test Acc: 35.00%  
Epoch 56/150, Loss: 2.4350, Train Acc: 37.68%, Val Acc: 34.35%, Test Acc: 34.78%  
Epoch 57/150, Loss: 2.4260, Train Acc: 37.61%, Val Acc: 34.41%, Test Acc: 35.02%  
Epoch 58/150, Loss: 2.4172, Train Acc: 38.16%, Val Acc: 34.13%, Test Acc: 35.02%  
Epoch 59/150, Loss: 2.4119, Train Acc: 37.94%, Val Acc: 34.85%, Test Acc: 35.37%  
Checkpoint saved at epoch 60
Epoch 60/150, Loss: 2.3938, Train Acc: 38.45%, Val Acc: 34.68%, Test Acc: 34.79%  
Epoch 61/150, Loss: 2.3932, Train Acc: 38.45%, Val Acc: 35.17%, Test Acc: 35.44%  
Epoch 62/150, Loss: 2.3789, Train Acc: 38.89%, Val Acc: 34.57%, Test Acc: 35.58%  
Epoch 63/150, Loss: 2.3797, Train Acc: 38.70%, Val Acc: 34.90%, Test Acc: 35.60%  
Epoch 64/150, Loss: 2.3684, Train Acc: 39.10%, Val Acc: 35.03%, Test Acc: 35.39%  
Epoch 65/150, Loss: 2.3623, Train Acc: 39.34%, Val Acc: 35.26%, Test Acc: 35.46%  
Epoch 66/150, Loss: 2.3507, Train Acc: 39.38%, Val Acc: 35.30%, Test Acc: 35.77%  
Epoch 67/150, Loss: 2.3378, Train Acc: 39.63%, Val Acc: 35.27%, Test Acc: 35.59%  
Epoch 68/150, Loss: 2.3469, Train Acc: 39.62%, Val Acc: 35.07%, Test Acc: 36.05%  
Epoch 69/150, Loss: 2.3266, Train Acc: 40.05%, Val Acc: 35.15%, Test Acc: 36.18%  
Checkpoint saved at epoch 70
Epoch 70/150, Loss: 2.3202, Train Acc: 39.97%, Val Acc: 35.49%, Test Acc: 36.26%  
Epoch 71/150, Loss: 2.3206, Train Acc: 39.99%, Val Acc: 35.90%, Test Acc: 36.42%  
Epoch 72/150, Loss: 2.3116, Train Acc: 40.42%, Val Acc: 35.31%, Test Acc: 36.80%  
Epoch 73/150, Loss: 2.3008, Train Acc: 40.35%, Val Acc: 35.82%, Test Acc: 36.60%  
Epoch 74/150, Loss: 2.2972, Train Acc: 40.45%, Val Acc: 36.46%, Test Acc: 36.84%  
Epoch 75/150, Loss: 2.2815, Train Acc: 41.12%, Val Acc: 36.54%, Test Acc: 36.87%  
Epoch 76/150, Loss: 2.2886, Train Acc: 40.64%, Val Acc: 36.51%, Test Acc: 36.13%  
Epoch 77/150, Loss: 2.2792, Train Acc: 41.22%, Val Acc: 36.75%, Test Acc: 36.74%  
Epoch 78/150, Loss: 2.2731, Train Acc: 41.19%, Val Acc: 36.71%, Test Acc: 36.78%  
Epoch 79/150, Loss: 2.2655, Train Acc: 41.43%, Val Acc: 36.38%, Test Acc: 37.01%  
Checkpoint saved at epoch 80
Epoch 80/150, Loss: 2.2625, Train Acc: 41.37%, Val Acc: 36.16%, Test Acc: 37.03%  
Epoch 81/150, Loss: 2.2602, Train Acc: 41.45%, Val Acc: 37.11%, Test Acc: 37.20%  
Epoch 82/150, Loss: 2.2549, Train Acc: 41.58%, Val Acc: 36.17%, Test Acc: 37.64%  
Epoch 83/150, Loss: 2.2465, Train Acc: 41.84%, Val Acc: 36.47%, Test Acc: 37.02%  
Epoch 84/150, Loss: 2.2421, Train Acc: 41.55%, Val Acc: 36.58%, Test Acc: 37.10%  
Epoch 85/150, Loss: 2.2369, Train Acc: 42.03%, Val Acc: 36.47%, Test Acc: 37.69%  
Epoch 86/150, Loss: 2.2294, Train Acc: 42.02%, Val Acc: 36.56%, Test Acc: 37.21%  
Epoch 87/150, Loss: 2.2262, Train Acc: 42.28%, Val Acc: 36.93%, Test Acc: 37.26%  
Epoch 88/150, Loss: 2.2251, Train Acc: 42.25%, Val Acc: 36.52%, Test Acc: 37.38%  
Epoch 89/150, Loss: 2.2134, Train Acc: 42.43%, Val Acc: 36.88%, Test Acc: 37.95%  
Checkpoint saved at epoch 90
Epoch 90/150, Loss: 2.2118, Train Acc: 42.40%, Val Acc: 37.03%, Test Acc: 37.69%  
Epoch 91/150, Loss: 2.2114, Train Acc: 42.53%, Val Acc: 37.48%, Test Acc: 37.50%  
Epoch 92/150, Loss: 2.2049, Train Acc: 42.80%, Val Acc: 37.19%, Test Acc: 37.64%  
Epoch 93/150, Loss: 2.2045, Train Acc: 42.38%, Val Acc: 36.83%, Test Acc: 37.29%  
Epoch 94/150, Loss: 2.1985, Train Acc: 42.84%, Val Acc: 37.50%, Test Acc: 38.07%  
Epoch 95/150, Loss: 2.1923, Train Acc: 42.92%, Val Acc: 36.87%, Test Acc: 37.72%  
Epoch 96/150, Loss: 2.1888, Train Acc: 43.03%, Val Acc: 37.46%, Test Acc: 37.97%  
Epoch 97/150, Loss: 2.1822, Train Acc: 43.01%, Val Acc: 37.35%, Test Acc: 38.52%  
Epoch 98/150, Loss: 2.1894, Train Acc: 43.14%, Val Acc: 37.84%, Test Acc: 37.61%  
Epoch 99/150, Loss: 2.1776, Train Acc: 43.11%, Val Acc: 37.50%, Test Acc: 38.32%  
Checkpoint saved at epoch 100
Epoch 100/150, Loss: 2.1755, Train Acc: 43.40%, Val Acc: 37.73%, Test Acc: 38.10%  
Epoch 101/150, Loss: 2.1743, Train Acc: 43.66%, Val Acc: 38.22%, Test Acc: 38.14%  
Epoch 102/150, Loss: 2.1660, Train Acc: 43.19%, Val Acc: 37.24%, Test Acc: 37.79%  
Epoch 103/150, Loss: 2.1691, Train Acc: 43.33%, Val Acc: 37.77%, Test Acc: 38.58%  
Epoch 104/150, Loss: 2.1611, Train Acc: 43.66%, Val Acc: 37.66%, Test Acc: 38.47%  
Epoch 105/150, Loss: 2.1597, Train Acc: 43.76%, Val Acc: 37.85%, Test Acc: 37.90%  
Epoch 106/150, Loss: 2.1560, Train Acc: 43.83%, Val Acc: 37.87%, Test Acc: 38.37%  
Epoch 107/150, Loss: 2.1627, Train Acc: 43.65%, Val Acc: 37.08%, Test Acc: 38.48%  
Epoch 108/150, Loss: 2.1569, Train Acc: 43.73%, Val Acc: 37.74%, Test Acc: 38.46%  
Epoch 109/150, Loss: 2.1477, Train Acc: 44.14%, Val Acc: 37.83%, Test Acc: 38.65%  
Checkpoint saved at epoch 110
Epoch 110/150, Loss: 2.1498, Train Acc: 43.97%, Val Acc: 37.87%, Test Acc: 38.25%  
Epoch 111/150, Loss: 2.1561, Train Acc: 44.01%, Val Acc: 37.95%, Test Acc: 38.96%  
Epoch 112/150, Loss: 2.1409, Train Acc: 43.95%, Val Acc: 37.65%, Test Acc: 38.39%  
Epoch 113/150, Loss: 2.1502, Train Acc: 43.88%, Val Acc: 38.23%, Test Acc: 38.74%  
Epoch 114/150, Loss: 2.1380, Train Acc: 43.94%, Val Acc: 37.90%, Test Acc: 38.56%  
Epoch 115/150, Loss: 2.1372, Train Acc: 43.98%, Val Acc: 37.57%, Test Acc: 38.55%  
Epoch 116/150, Loss: 2.1412, Train Acc: 44.03%, Val Acc: 38.08%, Test Acc: 38.85%  
Epoch 117/150, Loss: 2.1336, Train Acc: 44.56%, Val Acc: 37.63%, Test Acc: 38.24%  
Epoch 118/150, Loss: 2.1349, Train Acc: 44.30%, Val Acc: 38.24%, Test Acc: 38.54%  
Epoch 119/150, Loss: 2.1341, Train Acc: 44.13%, Val Acc: 38.24%, Test Acc: 38.40%  
Checkpoint saved at epoch 120
Epoch 120/150, Loss: 2.1257, Train Acc: 44.34%, Val Acc: 38.01%, Test Acc: 38.27%  
Epoch 121/150, Loss: 2.1291, Train Acc: 44.17%, Val Acc: 38.90%, Test Acc: 38.56%  
Epoch 122/150, Loss: 2.1248, Train Acc: 44.61%, Val Acc: 38.06%, Test Acc: 38.12%  
Epoch 123/150, Loss: 2.1244, Train Acc: 44.50%, Val Acc: 37.92%, Test Acc: 38.56%  
Epoch 124/150, Loss: 2.1275, Train Acc: 44.34%, Val Acc: 38.28%, Test Acc: 38.75%  
Epoch 125/150, Loss: 2.1271, Train Acc: 44.62%, Val Acc: 38.39%, Test Acc: 38.76%  
Epoch 126/150, Loss: 2.1212, Train Acc: 44.73%, Val Acc: 38.16%, Test Acc: 38.98%  
Epoch 127/150, Loss: 2.1206, Train Acc: 44.36%, Val Acc: 37.43%, Test Acc: 38.64%  
Epoch 128/150, Loss: 2.1176, Train Acc: 44.58%, Val Acc: 37.79%, Test Acc: 38.29%  
Epoch 129/150, Loss: 2.1159, Train Acc: 44.68%, Val Acc: 38.66%, Test Acc: 37.95%  
Checkpoint saved at epoch 130
Epoch 130/150, Loss: 2.1193, Train Acc: 44.47%, Val Acc: 38.37%, Test Acc: 39.00%  
Epoch 131/150, Loss: 2.1184, Train Acc: 44.60%, Val Acc: 38.20%, Test Acc: 38.77%  
Epoch 132/150, Loss: 2.1134, Train Acc: 44.80%, Val Acc: 37.92%, Test Acc: 38.71%  
Epoch 133/150, Loss: 2.1157, Train Acc: 44.83%, Val Acc: 38.44%, Test Acc: 38.49%  
Epoch 134/150, Loss: 2.1133, Train Acc: 44.76%, Val Acc: 38.17%, Test Acc: 38.98%  
Epoch 135/150, Loss: 2.1137, Train Acc: 44.80%, Val Acc: 38.16%, Test Acc: 38.69%  
Epoch 136/150, Loss: 2.1008, Train Acc: 45.09%, Val Acc: 38.04%, Test Acc: 38.82%  
Epoch 137/150, Loss: 2.1129, Train Acc: 45.03%, Val Acc: 38.28%, Test Acc: 39.26%  
Epoch 138/150, Loss: 2.1186, Train Acc: 44.62%, Val Acc: 38.23%, Test Acc: 38.95%  
Epoch 139/150, Loss: 2.1131, Train Acc: 44.90%, Val Acc: 38.72%, Test Acc: 38.44%  
Checkpoint saved at epoch 140
Epoch 140/150, Loss: 2.1127, Train Acc: 44.60%, Val Acc: 38.85%, Test Acc: 38.91%  
Epoch 141/150, Loss: 2.1034, Train Acc: 44.98%, Val Acc: 37.89%, Test Acc: 38.85%  
Epoch 142/150, Loss: 2.1133, Train Acc: 44.62%, Val Acc: 38.30%, Test Acc: 38.86%  
Epoch 143/150, Loss: 2.1096, Train Acc: 44.84%, Val Acc: 38.10%, Test Acc: 38.94%  
Epoch 144/150, Loss: 2.1084, Train Acc: 44.77%, Val Acc: 37.96%, Test Acc: 38.93%  
Epoch 145/150, Loss: 2.1104, Train Acc: 44.95%, Val Acc: 38.00%, Test Acc: 40.05%  
Epoch 146/150, Loss: 2.1067, Train Acc: 44.80%, Val Acc: 38.25%, Test Acc: 38.86%  
Epoch 147/150, Loss: 2.1166, Train Acc: 44.75%, Val Acc: 38.40%, Test Acc: 38.79%  
Epoch 148/150, Loss: 2.1043, Train Acc: 44.85%, Val Acc: 38.25%, Test Acc: 39.04%  
Epoch 149/150, Loss: 2.1076, Train Acc: 45.02%, Val Acc: 38.57%, Test Acc: 39.14%  
Checkpoint saved at epoch 150
Epoch 150/150, Loss: 2.1099, Train Acc: 44.81%, Val Acc: 38.14%, Test Acc: 39.00%

#### Plots

![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-4_wd=1e-2/train_loss.png)
![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-4_wd=1e-2/val_loss.png)
![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-4_wd=1e-2/test_loss.png)
![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-4_wd=1e-2/train_accuracy.png)
![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-4_wd=1e-2/val_accuracy.png)
![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-4_wd=1e-2/test_accuracy.png)

# Train with AdamW

| Epochs | batch_size | beta | weight_decay | learning_rate |
| ------ | ---------- | ---- | ------------ | ------------- |
| 150    | 128        | 0.9  | 1e-4         | 1e-3          |

#### Results log

Epoch 1/150, Loss: 4.1229, Train Acc: 6.71%, Val Acc: 10.65%, Test Acc: 10.13%  
Epoch 2/150, Loss: 3.6939, Train Acc: 12.91%, Val Acc: 15.00%, Test Acc: 14.66%  
Epoch 3/150, Loss: 3.4032, Train Acc: 17.88%, Val Acc: 18.87%, Test Acc: 19.48%  
Epoch 4/150, Loss: 3.2129, Train Acc: 21.29%, Val Acc: 22.70%, Test Acc: 22.56%  
Epoch 5/150, Loss: 3.0576, Train Acc: 23.95%, Val Acc: 23.55%, Test Acc: 23.74%  
Epoch 6/150, Loss: 2.9382, Train Acc: 26.32%, Val Acc: 26.66%, Test Acc: 26.95%  
Epoch 7/150, Loss: 2.8241, Train Acc: 29.12%, Val Acc: 25.80%, Test Acc: 25.80%  
Epoch 8/150, Loss: 2.7507, Train Acc: 30.26%, Val Acc: 29.22%, Test Acc: 29.19%  
Epoch 9/150, Loss: 2.6865, Train Acc: 31.61%, Val Acc: 29.04%, Test Acc: 29.97%  
Checkpoint saved at epoch 10
Epoch 10/150, Loss: 2.6269, Train Acc: 32.71%, Val Acc: 30.41%, Test Acc: 30.24%  
Epoch 11/150, Loss: 2.5900, Train Acc: 33.37%, Val Acc: 31.97%, Test Acc: 32.55%  
Epoch 12/150, Loss: 2.5404, Train Acc: 34.57%, Val Acc: 32.54%, Test Acc: 32.75%  
Epoch 13/150, Loss: 2.5036, Train Acc: 35.19%, Val Acc: 33.43%, Test Acc: 33.99%  
Epoch 14/150, Loss: 2.4611, Train Acc: 36.38%, Val Acc: 33.21%, Test Acc: 33.70%  
Epoch 15/150, Loss: 2.4344, Train Acc: 36.68%, Val Acc: 33.89%, Test Acc: 33.83%  
Epoch 16/150, Loss: 2.4084, Train Acc: 37.04%, Val Acc: 34.52%, Test Acc: 35.16%  
Epoch 17/150, Loss: 2.3777, Train Acc: 37.73%, Val Acc: 33.96%, Test Acc: 33.31%  
Epoch 18/150, Loss: 2.3539, Train Acc: 38.70%, Val Acc: 35.63%, Test Acc: 35.95%  
Epoch 19/150, Loss: 2.3330, Train Acc: 38.99%, Val Acc: 34.41%, Test Acc: 34.63%  
Checkpoint saved at epoch 20
Epoch 20/150, Loss: 2.3100, Train Acc: 39.44%, Val Acc: 35.16%, Test Acc: 35.54%  
Epoch 21/150, Loss: 2.2829, Train Acc: 39.68%, Val Acc: 35.20%, Test Acc: 35.11%  
Epoch 22/150, Loss: 2.2615, Train Acc: 40.43%, Val Acc: 36.60%, Test Acc: 36.51%  
Epoch 23/150, Loss: 2.2358, Train Acc: 40.88%, Val Acc: 36.81%, Test Acc: 36.79%  
Epoch 24/150, Loss: 2.2228, Train Acc: 41.16%, Val Acc: 36.99%, Test Acc: 36.84%  
Epoch 25/150, Loss: 2.2103, Train Acc: 41.32%, Val Acc: 37.40%, Test Acc: 36.61%  
Epoch 26/150, Loss: 2.1919, Train Acc: 42.29%, Val Acc: 37.10%, Test Acc: 37.59%  
Epoch 27/150, Loss: 2.1712, Train Acc: 42.48%, Val Acc: 37.35%, Test Acc: 37.43%  
Epoch 28/150, Loss: 2.1609, Train Acc: 42.28%, Val Acc: 37.13%, Test Acc: 37.19%  
Epoch 29/150, Loss: 2.1464, Train Acc: 42.62%, Val Acc: 36.57%, Test Acc: 37.07%  
Checkpoint saved at epoch 30
Epoch 30/150, Loss: 2.1277, Train Acc: 43.01%, Val Acc: 37.61%, Test Acc: 38.28%  
Epoch 31/150, Loss: 2.1086, Train Acc: 43.80%, Val Acc: 37.24%, Test Acc: 37.27%  
Epoch 32/150, Loss: 2.0931, Train Acc: 43.99%, Val Acc: 37.44%, Test Acc: 38.59%  
Epoch 33/150, Loss: 2.0853, Train Acc: 44.10%, Val Acc: 38.31%, Test Acc: 37.89%  
Epoch 34/150, Loss: 2.0702, Train Acc: 44.59%, Val Acc: 38.51%, Test Acc: 39.04%  
Epoch 35/150, Loss: 2.0662, Train Acc: 44.58%, Val Acc: 38.29%, Test Acc: 38.28%  
Epoch 36/150, Loss: 2.0484, Train Acc: 44.52%, Val Acc: 37.19%, Test Acc: 37.90%  
Epoch 37/150, Loss: 2.0384, Train Acc: 45.10%, Val Acc: 38.71%, Test Acc: 38.83%  
Epoch 38/150, Loss: 2.0308, Train Acc: 45.23%, Val Acc: 39.11%, Test Acc: 39.79%  
Epoch 39/150, Loss: 2.0161, Train Acc: 45.60%, Val Acc: 39.00%, Test Acc: 39.54%  
Checkpoint saved at epoch 40
Epoch 40/150, Loss: 2.0130, Train Acc: 45.73%, Val Acc: 38.24%, Test Acc: 38.68%  
Epoch 41/150, Loss: 2.0038, Train Acc: 45.79%, Val Acc: 38.87%, Test Acc: 39.96%  
Epoch 42/150, Loss: 1.9833, Train Acc: 46.23%, Val Acc: 39.24%, Test Acc: 39.11%  
Epoch 43/150, Loss: 1.9718, Train Acc: 46.66%, Val Acc: 38.60%, Test Acc: 39.48%  
Epoch 44/150, Loss: 1.9624, Train Acc: 46.98%, Val Acc: 39.01%, Test Acc: 39.03%  
Epoch 45/150, Loss: 1.9545, Train Acc: 47.16%, Val Acc: 39.74%, Test Acc: 39.88%  
Epoch 46/150, Loss: 1.9464, Train Acc: 47.11%, Val Acc: 39.64%, Test Acc: 40.07%  
Epoch 47/150, Loss: 1.9349, Train Acc: 47.75%, Val Acc: 39.43%, Test Acc: 40.32%  
Epoch 48/150, Loss: 1.9204, Train Acc: 47.73%, Val Acc: 39.66%, Test Acc: 40.11%  
Epoch 49/150, Loss: 1.9083, Train Acc: 48.24%, Val Acc: 40.17%, Test Acc: 41.23%  
Checkpoint saved at epoch 50
Epoch 50/150, Loss: 1.9151, Train Acc: 48.03%, Val Acc: 39.62%, Test Acc: 39.89%  
Epoch 51/150, Loss: 1.8990, Train Acc: 48.42%, Val Acc: 40.22%, Test Acc: 39.91%  
Epoch 52/150, Loss: 1.9013, Train Acc: 48.00%, Val Acc: 39.91%, Test Acc: 39.95%  
Epoch 53/150, Loss: 1.8740, Train Acc: 48.93%, Val Acc: 39.72%, Test Acc: 40.44%  
Epoch 54/150, Loss: 1.8606, Train Acc: 49.21%, Val Acc: 40.23%, Test Acc: 40.44%  
Epoch 55/150, Loss: 1.8658, Train Acc: 49.01%, Val Acc: 40.05%, Test Acc: 41.32%  
Epoch 56/150, Loss: 1.8494, Train Acc: 49.40%, Val Acc: 40.04%, Test Acc: 40.06%  
Epoch 57/150, Loss: 1.8461, Train Acc: 49.54%, Val Acc: 40.90%, Test Acc: 41.41%  
Epoch 58/150, Loss: 1.8313, Train Acc: 49.91%, Val Acc: 41.11%, Test Acc: 40.62%  
Epoch 59/150, Loss: 1.8404, Train Acc: 49.68%, Val Acc: 40.64%, Test Acc: 40.45%  
Checkpoint saved at epoch 60
Epoch 60/150, Loss: 1.8104, Train Acc: 50.37%, Val Acc: 39.87%, Test Acc: 41.03%  
Epoch 61/150, Loss: 1.8200, Train Acc: 49.98%, Val Acc: 40.74%, Test Acc: 40.83%  
Epoch 62/150, Loss: 1.8136, Train Acc: 50.17%, Val Acc: 40.14%, Test Acc: 40.79%  
Epoch 63/150, Loss: 1.8023, Train Acc: 50.38%, Val Acc: 40.39%, Test Acc: 40.60%  
Epoch 64/150, Loss: 1.7918, Train Acc: 50.74%, Val Acc: 40.91%, Test Acc: 40.84%  
Epoch 65/150, Loss: 1.7837, Train Acc: 50.77%, Val Acc: 39.62%, Test Acc: 40.67%  
Epoch 66/150, Loss: 1.7704, Train Acc: 51.51%, Val Acc: 40.73%, Test Acc: 41.65%  
Epoch 67/150, Loss: 1.7609, Train Acc: 51.50%, Val Acc: 41.06%, Test Acc: 40.70%  
Epoch 68/150, Loss: 1.7686, Train Acc: 51.45%, Val Acc: 39.16%, Test Acc: 39.66%  
Epoch 69/150, Loss: 1.7502, Train Acc: 51.90%, Val Acc: 40.87%, Test Acc: 41.71%  
Checkpoint saved at epoch 70
Epoch 70/150, Loss: 1.7520, Train Acc: 51.45%, Val Acc: 41.49%, Test Acc: 40.61%  
Epoch 71/150, Loss: 1.7462, Train Acc: 51.89%, Val Acc: 41.59%, Test Acc: 41.98%  
Epoch 72/150, Loss: 1.7314, Train Acc: 52.45%, Val Acc: 41.19%, Test Acc: 41.86%  
Epoch 73/150, Loss: 1.7236, Train Acc: 52.37%, Val Acc: 41.71%, Test Acc: 41.96%  
Epoch 74/150, Loss: 1.7155, Train Acc: 52.39%, Val Acc: 40.89%, Test Acc: 41.56%  
Epoch 75/150, Loss: 1.7089, Train Acc: 52.85%, Val Acc: 41.26%, Test Acc: 41.54%  
Epoch 76/150, Loss: 1.6990, Train Acc: 52.88%, Val Acc: 42.06%, Test Acc: 42.32%  
Epoch 77/150, Loss: 1.6903, Train Acc: 52.85%, Val Acc: 40.84%, Test Acc: 42.14%  
Epoch 78/150, Loss: 1.6869, Train Acc: 53.22%, Val Acc: 40.97%, Test Acc: 41.85%  
Epoch 79/150, Loss: 1.6790, Train Acc: 53.51%, Val Acc: 41.41%, Test Acc: 42.85%  
Checkpoint saved at epoch 80
Epoch 80/150, Loss: 1.6724, Train Acc: 53.48%, Val Acc: 41.49%, Test Acc: 42.65%  
Epoch 81/150, Loss: 1.6664, Train Acc: 53.77%, Val Acc: 41.88%, Test Acc: 42.64%  
Epoch 82/150, Loss: 1.6604, Train Acc: 53.84%, Val Acc: 41.84%, Test Acc: 42.33%  
Epoch 83/150, Loss: 1.6522, Train Acc: 54.22%, Val Acc: 41.40%, Test Acc: 42.32%  
Epoch 84/150, Loss: 1.6408, Train Acc: 54.42%, Val Acc: 42.27%, Test Acc: 42.67%  
Epoch 85/150, Loss: 1.6332, Train Acc: 54.40%, Val Acc: 42.11%, Test Acc: 42.53%  
Epoch 86/150, Loss: 1.6345, Train Acc: 54.61%, Val Acc: 41.43%, Test Acc: 42.56%  
Epoch 87/150, Loss: 1.6322, Train Acc: 54.25%, Val Acc: 42.40%, Test Acc: 43.12%  
Epoch 88/150, Loss: 1.6174, Train Acc: 54.93%, Val Acc: 42.37%, Test Acc: 42.85%  
Epoch 89/150, Loss: 1.6093, Train Acc: 55.15%, Val Acc: 42.51%, Test Acc: 43.32%  
Checkpoint saved at epoch 90
Epoch 90/150, Loss: 1.5993, Train Acc: 55.51%, Val Acc: 42.31%, Test Acc: 42.69%  
Epoch 91/150, Loss: 1.6023, Train Acc: 55.19%, Val Acc: 42.59%, Test Acc: 42.55%  
Epoch 92/150, Loss: 1.5953, Train Acc: 55.41%, Val Acc: 41.76%, Test Acc: 43.21%  
Epoch 93/150, Loss: 1.5809, Train Acc: 55.49%, Val Acc: 42.88%, Test Acc: 42.35%  
Epoch 94/150, Loss: 1.5871, Train Acc: 55.74%, Val Acc: 43.15%, Test Acc: 42.83%  
Epoch 95/150, Loss: 1.5768, Train Acc: 55.76%, Val Acc: 42.78%, Test Acc: 42.80%  
Epoch 96/150, Loss: 1.5727, Train Acc: 56.09%, Val Acc: 42.53%, Test Acc: 43.45%  
Epoch 97/150, Loss: 1.5677, Train Acc: 55.95%, Val Acc: 42.27%, Test Acc: 42.67%  
Epoch 98/150, Loss: 1.5590, Train Acc: 56.27%, Val Acc: 42.87%, Test Acc: 43.25%  
Epoch 99/150, Loss: 1.5445, Train Acc: 56.53%, Val Acc: 43.08%, Test Acc: 43.62%  
Checkpoint saved at epoch 100
Epoch 100/150, Loss: 1.5430, Train Acc: 56.73%, Val Acc: 43.06%, Test Acc: 43.17%  
Epoch 101/150, Loss: 1.5395, Train Acc: 57.01%, Val Acc: 43.60%, Test Acc: 43.34%  
Epoch 102/150, Loss: 1.5314, Train Acc: 56.75%, Val Acc: 42.85%, Test Acc: 42.94%  
Epoch 103/150, Loss: 1.5304, Train Acc: 57.09%, Val Acc: 42.69%, Test Acc: 42.93%  
Epoch 104/150, Loss: 1.5263, Train Acc: 57.07%, Val Acc: 42.71%, Test Acc: 42.77%  
Epoch 105/150, Loss: 1.5251, Train Acc: 57.36%, Val Acc: 43.25%, Test Acc: 43.08%  
Epoch 106/150, Loss: 1.5160, Train Acc: 57.50%, Val Acc: 43.28%, Test Acc: 43.92%  
Epoch 107/150, Loss: 1.5134, Train Acc: 57.56%, Val Acc: 42.98%, Test Acc: 43.45%  
Epoch 108/150, Loss: 1.5135, Train Acc: 57.45%, Val Acc: 43.01%, Test Acc: 43.49%  
Epoch 109/150, Loss: 1.5032, Train Acc: 57.99%, Val Acc: 42.94%, Test Acc: 43.53%  
Checkpoint saved at epoch 110
Epoch 110/150, Loss: 1.4904, Train Acc: 58.02%, Val Acc: 43.43%, Test Acc: 43.83%  
Epoch 111/150, Loss: 1.5014, Train Acc: 57.47%, Val Acc: 42.99%, Test Acc: 44.13%  
Epoch 112/150, Loss: 1.4896, Train Acc: 58.04%, Val Acc: 43.42%, Test Acc: 42.92%  
Epoch 113/150, Loss: 1.4911, Train Acc: 57.91%, Val Acc: 42.99%, Test Acc: 43.38%  
Epoch 114/150, Loss: 1.4709, Train Acc: 58.31%, Val Acc: 42.94%, Test Acc: 43.48%  
Epoch 115/150, Loss: 1.4752, Train Acc: 58.25%, Val Acc: 43.65%, Test Acc: 44.14%  
Epoch 116/150, Loss: 1.4698, Train Acc: 58.42%, Val Acc: 43.40%, Test Acc: 44.15%  
Epoch 117/150, Loss: 1.4714, Train Acc: 58.35%, Val Acc: 42.90%, Test Acc: 43.45%  
Epoch 118/150, Loss: 1.4692, Train Acc: 58.46%, Val Acc: 43.40%, Test Acc: 43.25%  
Epoch 119/150, Loss: 1.4621, Train Acc: 58.73%, Val Acc: 42.98%, Test Acc: 43.16%  
Checkpoint saved at epoch 120
Epoch 120/150, Loss: 1.4649, Train Acc: 58.52%, Val Acc: 43.31%, Test Acc: 43.76%  
Epoch 121/150, Loss: 1.4582, Train Acc: 59.12%, Val Acc: 43.31%, Test Acc: 44.75%  
Epoch 122/150, Loss: 1.4490, Train Acc: 58.90%, Val Acc: 43.62%, Test Acc: 43.80%  
Epoch 123/150, Loss: 1.4523, Train Acc: 58.59%, Val Acc: 43.36%, Test Acc: 44.36%  
Epoch 124/150, Loss: 1.4519, Train Acc: 59.06%, Val Acc: 43.00%, Test Acc: 43.96%  
Epoch 125/150, Loss: 1.4506, Train Acc: 59.15%, Val Acc: 44.38%, Test Acc: 44.41%  
Epoch 126/150, Loss: 1.4361, Train Acc: 59.49%, Val Acc: 43.25%, Test Acc: 43.85%  
Epoch 127/150, Loss: 1.4359, Train Acc: 59.31%, Val Acc: 44.19%, Test Acc: 44.44%  
Epoch 128/150, Loss: 1.4257, Train Acc: 59.57%, Val Acc: 43.77%, Test Acc: 44.03%  
Epoch 129/150, Loss: 1.4388, Train Acc: 59.35%, Val Acc: 43.72%, Test Acc: 43.51%  
Checkpoint saved at epoch 130
Epoch 130/150, Loss: 1.4354, Train Acc: 59.32%, Val Acc: 44.06%, Test Acc: 43.88%  
Epoch 131/150, Loss: 1.4190, Train Acc: 59.95%, Val Acc: 43.95%, Test Acc: 44.35%  
Epoch 132/150, Loss: 1.4306, Train Acc: 59.44%, Val Acc: 43.55%, Test Acc: 44.18%  
Epoch 133/150, Loss: 1.4309, Train Acc: 59.59%, Val Acc: 44.03%, Test Acc: 44.56%  
Epoch 134/150, Loss: 1.4123, Train Acc: 59.91%, Val Acc: 43.90%, Test Acc: 44.54%  
Epoch 135/150, Loss: 1.4192, Train Acc: 59.59%, Val Acc: 43.71%, Test Acc: 43.65%  
Epoch 136/150, Loss: 1.4168, Train Acc: 59.91%, Val Acc: 44.09%, Test Acc: 43.87%  
Epoch 137/150, Loss: 1.4173, Train Acc: 59.82%, Val Acc: 44.03%, Test Acc: 43.83%  
Epoch 138/150, Loss: 1.4237, Train Acc: 59.60%, Val Acc: 44.18%, Test Acc: 44.20%  
Epoch 139/150, Loss: 1.4238, Train Acc: 59.68%, Val Acc: 43.50%, Test Acc: 44.30%  
Checkpoint saved at epoch 140
Epoch 140/150, Loss: 1.4132, Train Acc: 60.09%, Val Acc: 44.47%, Test Acc: 44.57%  
Epoch 141/150, Loss: 1.4124, Train Acc: 60.01%, Val Acc: 44.09%, Test Acc: 43.88%  
Epoch 142/150, Loss: 1.4093, Train Acc: 60.20%, Val Acc: 44.42%, Test Acc: 43.99%  
Epoch 143/150, Loss: 1.4174, Train Acc: 59.93%, Val Acc: 43.82%, Test Acc: 44.50%  
Epoch 144/150, Loss: 1.4086, Train Acc: 59.97%, Val Acc: 43.78%, Test Acc: 44.48%  
Epoch 145/150, Loss: 1.4075, Train Acc: 60.12%, Val Acc: 44.03%, Test Acc: 44.48%  
Epoch 146/150, Loss: 1.4143, Train Acc: 59.84%, Val Acc: 44.17%, Test Acc: 44.64%  
Epoch 147/150, Loss: 1.4123, Train Acc: 60.07%, Val Acc: 44.21%, Test Acc: 44.02%  
Epoch 148/150, Loss: 1.4056, Train Acc: 59.86%, Val Acc: 43.65%, Test Acc: 44.56%  
Epoch 149/150, Loss: 1.4056, Train Acc: 60.19%, Val Acc: 43.97%, Test Acc: 44.26%  
Checkpoint saved at epoch 150
Epoch 150/150, Loss: 1.4159, Train Acc: 59.93%, Val Acc: 44.39%, Test Acc: 44.82%

#### Plots

![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-4/train_loss.png)
![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-4/val_loss.png)
![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-4/test_loss.png)
![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-4/train_accuracy.png)
![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-4/val_accuracy.png)
![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-4/test_accuracy.png)

# Train with AdamW

| Epochs | batch_size | beta | weight_decay | learning_rate |
| ------ | ---------- | ---- | ------------ | ------------- |
| 150    | 128        | 0.9  | 1e-4         | 1e-4          |

#### Results log

Epoch 1/150, Loss: 4.3211, Train Acc: 4.74%, Val Acc: 7.30%, Test Acc: 6.71%  
Epoch 2/150, Loss: 4.0381, Train Acc: 8.49%, Val Acc: 9.90%, Test Acc: 10.22%  
Epoch 3/150, Loss: 3.9088, Train Acc: 10.66%, Val Acc: 10.97%, Test Acc: 11.23%  
Epoch 4/150, Loss: 3.8020, Train Acc: 12.04%, Val Acc: 13.09%, Test Acc: 13.05%  
Epoch 5/150, Loss: 3.7049, Train Acc: 13.72%, Val Acc: 14.73%, Test Acc: 14.48%  
Epoch 6/150, Loss: 3.6183, Train Acc: 14.95%, Val Acc: 15.44%, Test Acc: 15.77%  
Epoch 7/150, Loss: 3.5454, Train Acc: 16.32%, Val Acc: 16.70%, Test Acc: 16.33%  
Epoch 8/150, Loss: 3.4807, Train Acc: 17.46%, Val Acc: 17.66%, Test Acc: 18.36%  
Epoch 9/150, Loss: 3.4278, Train Acc: 18.49%, Val Acc: 18.98%, Test Acc: 18.39%  
Checkpoint saved at epoch 10
Epoch 10/150, Loss: 3.3788, Train Acc: 19.54%, Val Acc: 19.12%, Test Acc: 18.85%  
Epoch 11/150, Loss: 3.3390, Train Acc: 20.14%, Val Acc: 19.94%, Test Acc: 19.99%  
Epoch 12/150, Loss: 3.2933, Train Acc: 20.91%, Val Acc: 20.71%, Test Acc: 20.71%  
Epoch 13/150, Loss: 3.2608, Train Acc: 21.32%, Val Acc: 21.01%, Test Acc: 20.95%  
Epoch 14/150, Loss: 3.2224, Train Acc: 22.31%, Val Acc: 21.75%, Test Acc: 21.71%  
Epoch 15/150, Loss: 3.1951, Train Acc: 22.71%, Val Acc: 21.83%, Test Acc: 22.73%  
Epoch 16/150, Loss: 3.1687, Train Acc: 23.06%, Val Acc: 22.56%, Test Acc: 22.87%  
Epoch 17/150, Loss: 3.1385, Train Acc: 23.68%, Val Acc: 23.12%, Test Acc: 23.10%  
Epoch 18/150, Loss: 3.1068, Train Acc: 24.27%, Val Acc: 23.67%, Test Acc: 24.34%  
Epoch 19/150, Loss: 3.0836, Train Acc: 24.57%, Val Acc: 23.75%, Test Acc: 24.21%  
Checkpoint saved at epoch 20
Epoch 20/150, Loss: 3.0586, Train Acc: 25.21%, Val Acc: 24.25%, Test Acc: 25.25%  
Epoch 21/150, Loss: 3.0356, Train Acc: 25.53%, Val Acc: 24.67%, Test Acc: 24.71%  
Epoch 22/150, Loss: 3.0077, Train Acc: 25.99%, Val Acc: 25.90%, Test Acc: 25.42%  
Epoch 23/150, Loss: 2.9757, Train Acc: 26.99%, Val Acc: 26.16%, Test Acc: 26.33%  
Epoch 24/150, Loss: 2.9512, Train Acc: 27.24%, Val Acc: 27.02%, Test Acc: 26.72%  
Epoch 25/150, Loss: 2.9320, Train Acc: 27.58%, Val Acc: 26.71%, Test Acc: 27.07%  
Epoch 26/150, Loss: 2.9092, Train Acc: 28.30%, Val Acc: 26.72%, Test Acc: 27.12%  
Epoch 27/150, Loss: 2.8800, Train Acc: 28.74%, Val Acc: 27.90%, Test Acc: 27.47%  
Epoch 28/150, Loss: 2.8614, Train Acc: 28.88%, Val Acc: 27.91%, Test Acc: 27.94%  
Epoch 29/150, Loss: 2.8298, Train Acc: 29.55%, Val Acc: 27.76%, Test Acc: 28.48%  
Checkpoint saved at epoch 30
Epoch 30/150, Loss: 2.8126, Train Acc: 30.07%, Val Acc: 28.28%, Test Acc: 28.81%  
Epoch 31/150, Loss: 2.7888, Train Acc: 30.42%, Val Acc: 29.38%, Test Acc: 29.17%  
Epoch 32/150, Loss: 2.7663, Train Acc: 30.92%, Val Acc: 28.65%, Test Acc: 29.41%  
Epoch 33/150, Loss: 2.7474, Train Acc: 30.89%, Val Acc: 29.16%, Test Acc: 29.61%  
Epoch 34/150, Loss: 2.7266, Train Acc: 31.92%, Val Acc: 30.17%, Test Acc: 30.21%  
Epoch 35/150, Loss: 2.7105, Train Acc: 31.92%, Val Acc: 29.94%, Test Acc: 30.31%  
Epoch 36/150, Loss: 2.6946, Train Acc: 32.10%, Val Acc: 29.96%, Test Acc: 29.82%  
Epoch 37/150, Loss: 2.6768, Train Acc: 32.84%, Val Acc: 30.19%, Test Acc: 30.74%  
Epoch 38/150, Loss: 2.6643, Train Acc: 32.97%, Val Acc: 30.85%, Test Acc: 31.30%  
Epoch 39/150, Loss: 2.6437, Train Acc: 33.33%, Val Acc: 31.71%, Test Acc: 31.15%  
Checkpoint saved at epoch 40
Epoch 40/150, Loss: 2.6317, Train Acc: 33.35%, Val Acc: 31.27%, Test Acc: 32.40%  
Epoch 41/150, Loss: 2.6115, Train Acc: 34.07%, Val Acc: 30.96%, Test Acc: 31.63%  
Epoch 42/150, Loss: 2.5952, Train Acc: 34.04%, Val Acc: 31.81%, Test Acc: 32.32%  
Epoch 43/150, Loss: 2.5891, Train Acc: 34.47%, Val Acc: 31.58%, Test Acc: 31.87%  
Epoch 44/150, Loss: 2.5745, Train Acc: 34.72%, Val Acc: 31.20%, Test Acc: 32.64%  
Epoch 45/150, Loss: 2.5615, Train Acc: 35.01%, Val Acc: 32.00%, Test Acc: 32.80%  
Epoch 46/150, Loss: 2.5515, Train Acc: 35.30%, Val Acc: 32.66%, Test Acc: 32.85%  
Epoch 47/150, Loss: 2.5365, Train Acc: 35.57%, Val Acc: 32.59%, Test Acc: 33.44%  
Epoch 48/150, Loss: 2.5258, Train Acc: 35.76%, Val Acc: 32.68%, Test Acc: 32.88%  
Epoch 49/150, Loss: 2.5141, Train Acc: 36.26%, Val Acc: 33.11%, Test Acc: 33.31%  
Checkpoint saved at epoch 50
Epoch 50/150, Loss: 2.5086, Train Acc: 36.08%, Val Acc: 32.76%, Test Acc: 34.08%  
Epoch 51/150, Loss: 2.4908, Train Acc: 36.53%, Val Acc: 32.94%, Test Acc: 32.86%  
Epoch 52/150, Loss: 2.4807, Train Acc: 36.62%, Val Acc: 32.92%, Test Acc: 33.68%  
Epoch 53/150, Loss: 2.4716, Train Acc: 36.74%, Val Acc: 33.91%, Test Acc: 34.17%  
Epoch 54/150, Loss: 2.4635, Train Acc: 37.05%, Val Acc: 33.23%, Test Acc: 33.73%  
Epoch 55/150, Loss: 2.4566, Train Acc: 37.12%, Val Acc: 33.74%, Test Acc: 34.89%  
Epoch 56/150, Loss: 2.4407, Train Acc: 37.66%, Val Acc: 33.97%, Test Acc: 34.68%  
Epoch 57/150, Loss: 2.4344, Train Acc: 37.73%, Val Acc: 34.01%, Test Acc: 34.31%  
Epoch 58/150, Loss: 2.4266, Train Acc: 37.67%, Val Acc: 34.29%, Test Acc: 34.85%  
Epoch 59/150, Loss: 2.4208, Train Acc: 37.99%, Val Acc: 35.02%, Test Acc: 35.44%  
Checkpoint saved at epoch 60
Epoch 60/150, Loss: 2.4010, Train Acc: 38.35%, Val Acc: 34.36%, Test Acc: 34.88%  
Epoch 61/150, Loss: 2.4035, Train Acc: 38.22%, Val Acc: 34.34%, Test Acc: 34.79%  
Epoch 62/150, Loss: 2.3893, Train Acc: 38.64%, Val Acc: 34.15%, Test Acc: 34.74%  
Epoch 63/150, Loss: 2.3888, Train Acc: 38.60%, Val Acc: 34.70%, Test Acc: 35.59%  
Epoch 64/150, Loss: 2.3723, Train Acc: 39.09%, Val Acc: 35.11%, Test Acc: 35.50%  
Epoch 65/150, Loss: 2.3735, Train Acc: 39.12%, Val Acc: 35.28%, Test Acc: 35.80%  
Epoch 66/150, Loss: 2.3571, Train Acc: 39.03%, Val Acc: 34.97%, Test Acc: 35.53%  
Epoch 67/150, Loss: 2.3453, Train Acc: 39.46%, Val Acc: 35.69%, Test Acc: 35.11%  
Epoch 68/150, Loss: 2.3524, Train Acc: 39.30%, Val Acc: 35.38%, Test Acc: 35.61%  
Epoch 69/150, Loss: 2.3354, Train Acc: 39.78%, Val Acc: 35.33%, Test Acc: 36.00%  
Checkpoint saved at epoch 70
Epoch 70/150, Loss: 2.3287, Train Acc: 40.17%, Val Acc: 35.50%, Test Acc: 35.65%  
Epoch 71/150, Loss: 2.3284, Train Acc: 40.09%, Val Acc: 36.12%, Test Acc: 35.91%  
Epoch 72/150, Loss: 2.3152, Train Acc: 40.30%, Val Acc: 35.27%, Test Acc: 36.05%  
Epoch 73/150, Loss: 2.3038, Train Acc: 40.40%, Val Acc: 35.59%, Test Acc: 35.97%  
Epoch 74/150, Loss: 2.3045, Train Acc: 40.37%, Val Acc: 36.02%, Test Acc: 36.89%  
Epoch 75/150, Loss: 2.2926, Train Acc: 40.71%, Val Acc: 36.35%, Test Acc: 36.22%  
Epoch 76/150, Loss: 2.2960, Train Acc: 40.56%, Val Acc: 36.35%, Test Acc: 36.61%  
Epoch 77/150, Loss: 2.2842, Train Acc: 41.16%, Val Acc: 36.83%, Test Acc: 36.92%  
Epoch 78/150, Loss: 2.2817, Train Acc: 40.82%, Val Acc: 36.18%, Test Acc: 36.53%  
Epoch 79/150, Loss: 2.2741, Train Acc: 41.45%, Val Acc: 36.07%, Test Acc: 36.58%  
Checkpoint saved at epoch 80
Epoch 80/150, Loss: 2.2702, Train Acc: 41.40%, Val Acc: 35.87%, Test Acc: 37.01%  
Epoch 81/150, Loss: 2.2612, Train Acc: 41.39%, Val Acc: 36.22%, Test Acc: 36.92%  
Epoch 82/150, Loss: 2.2633, Train Acc: 41.35%, Val Acc: 36.54%, Test Acc: 36.82%  
Epoch 83/150, Loss: 2.2520, Train Acc: 41.60%, Val Acc: 36.24%, Test Acc: 37.12%  
Epoch 84/150, Loss: 2.2450, Train Acc: 41.63%, Val Acc: 36.46%, Test Acc: 37.31%  
Epoch 85/150, Loss: 2.2444, Train Acc: 41.78%, Val Acc: 36.47%, Test Acc: 37.03%  
Epoch 86/150, Loss: 2.2344, Train Acc: 41.83%, Val Acc: 36.52%, Test Acc: 36.82%  
Epoch 87/150, Loss: 2.2324, Train Acc: 42.09%, Val Acc: 36.72%, Test Acc: 36.90%  
Epoch 88/150, Loss: 2.2332, Train Acc: 42.23%, Val Acc: 36.45%, Test Acc: 37.98%  
Epoch 89/150, Loss: 2.2208, Train Acc: 42.27%, Val Acc: 36.29%, Test Acc: 37.44%  
Checkpoint saved at epoch 90
Epoch 90/150, Loss: 2.2162, Train Acc: 42.49%, Val Acc: 37.37%, Test Acc: 37.11%  
Epoch 91/150, Loss: 2.2166, Train Acc: 42.42%, Val Acc: 37.03%, Test Acc: 37.18%  
Epoch 92/150, Loss: 2.2078, Train Acc: 42.52%, Val Acc: 36.94%, Test Acc: 37.39%  
Epoch 93/150, Loss: 2.2080, Train Acc: 42.57%, Val Acc: 36.83%, Test Acc: 36.87%  
Epoch 94/150, Loss: 2.2029, Train Acc: 42.64%, Val Acc: 37.61%, Test Acc: 38.40%  
Epoch 95/150, Loss: 2.2024, Train Acc: 42.65%, Val Acc: 36.41%, Test Acc: 37.62%  
Epoch 96/150, Loss: 2.1944, Train Acc: 42.82%, Val Acc: 37.06%, Test Acc: 37.68%  
Epoch 97/150, Loss: 2.1870, Train Acc: 42.86%, Val Acc: 37.67%, Test Acc: 37.80%  
Epoch 98/150, Loss: 2.1958, Train Acc: 42.75%, Val Acc: 37.39%, Test Acc: 38.18%  
Epoch 99/150, Loss: 2.1843, Train Acc: 43.17%, Val Acc: 37.58%, Test Acc: 37.86%  
Checkpoint saved at epoch 100
Epoch 100/150, Loss: 2.1793, Train Acc: 43.21%, Val Acc: 37.46%, Test Acc: 37.88%  
Epoch 101/150, Loss: 2.1829, Train Acc: 43.22%, Val Acc: 37.60%, Test Acc: 38.42%  
Epoch 102/150, Loss: 2.1713, Train Acc: 43.17%, Val Acc: 37.17%, Test Acc: 37.83%  
Epoch 103/150, Loss: 2.1716, Train Acc: 43.28%, Val Acc: 37.09%, Test Acc: 38.28%  
Epoch 104/150, Loss: 2.1635, Train Acc: 43.52%, Val Acc: 37.20%, Test Acc: 37.86%  
Epoch 105/150, Loss: 2.1675, Train Acc: 43.41%, Val Acc: 37.97%, Test Acc: 37.91%  
Epoch 106/150, Loss: 2.1634, Train Acc: 43.64%, Val Acc: 37.54%, Test Acc: 38.15%  
Epoch 107/150, Loss: 2.1648, Train Acc: 43.62%, Val Acc: 37.38%, Test Acc: 38.17%  
Epoch 108/150, Loss: 2.1644, Train Acc: 43.51%, Val Acc: 37.65%, Test Acc: 38.01%  
Epoch 109/150, Loss: 2.1568, Train Acc: 43.85%, Val Acc: 37.74%, Test Acc: 38.03%  
Checkpoint saved at epoch 110
Epoch 110/150, Loss: 2.1517, Train Acc: 43.85%, Val Acc: 38.03%, Test Acc: 37.51%  
Epoch 111/150, Loss: 2.1625, Train Acc: 43.59%, Val Acc: 37.67%, Test Acc: 38.54%  
Epoch 112/150, Loss: 2.1432, Train Acc: 44.11%, Val Acc: 37.95%, Test Acc: 38.43%  
Epoch 113/150, Loss: 2.1536, Train Acc: 43.74%, Val Acc: 37.68%, Test Acc: 38.50%  
Epoch 114/150, Loss: 2.1426, Train Acc: 44.02%, Val Acc: 37.76%, Test Acc: 38.24%  
Epoch 115/150, Loss: 2.1403, Train Acc: 43.80%, Val Acc: 37.49%, Test Acc: 39.10%  
Epoch 116/150, Loss: 2.1455, Train Acc: 44.20%, Val Acc: 37.65%, Test Acc: 38.80%  
Epoch 117/150, Loss: 2.1409, Train Acc: 44.02%, Val Acc: 37.37%, Test Acc: 37.74%  
Epoch 118/150, Loss: 2.1357, Train Acc: 44.13%, Val Acc: 38.33%, Test Acc: 37.85%  
Epoch 119/150, Loss: 2.1367, Train Acc: 44.16%, Val Acc: 38.23%, Test Acc: 38.14%  
Checkpoint saved at epoch 120
Epoch 120/150, Loss: 2.1303, Train Acc: 44.27%, Val Acc: 37.98%, Test Acc: 38.72%  
Epoch 121/150, Loss: 2.1309, Train Acc: 44.37%, Val Acc: 37.92%, Test Acc: 38.35%  
Epoch 122/150, Loss: 2.1313, Train Acc: 44.32%, Val Acc: 38.26%, Test Acc: 38.34%  
Epoch 123/150, Loss: 2.1269, Train Acc: 44.51%, Val Acc: 37.75%, Test Acc: 38.63%  
Epoch 124/150, Loss: 2.1324, Train Acc: 44.13%, Val Acc: 38.31%, Test Acc: 39.04%  
Epoch 125/150, Loss: 2.1264, Train Acc: 44.58%, Val Acc: 37.75%, Test Acc: 38.46%  
Epoch 126/150, Loss: 2.1220, Train Acc: 44.68%, Val Acc: 37.96%, Test Acc: 38.81%  
Epoch 127/150, Loss: 2.1263, Train Acc: 44.38%, Val Acc: 37.91%, Test Acc: 38.36%  
Epoch 128/150, Loss: 2.1187, Train Acc: 44.53%, Val Acc: 37.97%, Test Acc: 37.93%  
Epoch 129/150, Loss: 2.1158, Train Acc: 44.88%, Val Acc: 38.61%, Test Acc: 38.14%  
Checkpoint saved at epoch 130
Epoch 130/150, Loss: 2.1257, Train Acc: 44.46%, Val Acc: 38.12%, Test Acc: 39.26%  
Epoch 131/150, Loss: 2.1239, Train Acc: 44.59%, Val Acc: 37.51%, Test Acc: 38.51%  
Epoch 132/150, Loss: 2.1191, Train Acc: 44.73%, Val Acc: 37.66%, Test Acc: 38.30%  
Epoch 133/150, Loss: 2.1184, Train Acc: 44.63%, Val Acc: 38.16%, Test Acc: 38.34%  
Epoch 134/150, Loss: 2.1136, Train Acc: 44.73%, Val Acc: 38.11%, Test Acc: 38.46%  
Epoch 135/150, Loss: 2.1189, Train Acc: 44.54%, Val Acc: 38.20%, Test Acc: 38.80%  
Epoch 136/150, Loss: 2.1086, Train Acc: 44.87%, Val Acc: 38.60%, Test Acc: 38.42%  
Epoch 137/150, Loss: 2.1149, Train Acc: 44.87%, Val Acc: 38.52%, Test Acc: 39.39%  
Epoch 138/150, Loss: 2.1195, Train Acc: 44.58%, Val Acc: 37.78%, Test Acc: 38.26%  
Epoch 139/150, Loss: 2.1193, Train Acc: 44.86%, Val Acc: 38.16%, Test Acc: 38.61%  
Checkpoint saved at epoch 140
Epoch 140/150, Loss: 2.1164, Train Acc: 44.85%, Val Acc: 38.89%, Test Acc: 39.03%  
Epoch 141/150, Loss: 2.1100, Train Acc: 44.68%, Val Acc: 38.21%, Test Acc: 38.99%  
Epoch 142/150, Loss: 2.1141, Train Acc: 44.56%, Val Acc: 38.25%, Test Acc: 38.72%  
Epoch 143/150, Loss: 2.1155, Train Acc: 44.63%, Val Acc: 38.58%, Test Acc: 39.00%  
Epoch 144/150, Loss: 2.1072, Train Acc: 45.00%, Val Acc: 37.66%, Test Acc: 39.01%  
Epoch 145/150, Loss: 2.1145, Train Acc: 44.76%, Val Acc: 38.30%, Test Acc: 39.05%  
Epoch 146/150, Loss: 2.1172, Train Acc: 44.90%, Val Acc: 37.88%, Test Acc: 38.37%  
Epoch 147/150, Loss: 2.1209, Train Acc: 44.58%, Val Acc: 38.12%, Test Acc: 38.42%  
Epoch 148/150, Loss: 2.1093, Train Acc: 44.66%, Val Acc: 37.86%, Test Acc: 39.10%  
Epoch 149/150, Loss: 2.1103, Train Acc: 44.87%, Val Acc: 38.62%, Test Acc: 39.07%  
Checkpoint saved at epoch 150
Epoch 150/150, Loss: 2.1109, Train Acc: 44.81%, Val Acc: 38.31%, Test Acc: 38.47%

#### Plots

![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-4_wd=1e-4/train_loss.png)
![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-4_wd=1e-4/val_loss.png)
![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-4_wd=1e-4/test_loss.png)
![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-4_wd=1e-4/train_accuracy.png)
![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-4_wd=1e-4/val_accuracy.png)
![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-4_wd=1e-4/test_accuracy.png)

# Train with AdamW

| Epochs | batch_size | beta | weight_decay | learning_rate |
| ------ | ---------- | ---- | ------------ | ------------- |
| 150    | 128        | 0.9  | 1e-2         | 1e-3          |

#### Results log

Epoch 1/150, Loss: 4.1172, Train Acc: 6.76%, Val Acc: 10.69%, Test Acc: 10.53%  
Epoch 2/150, Loss: 3.6816, Train Acc: 12.86%, Val Acc: 15.77%, Test Acc: 15.20%  
Epoch 3/150, Loss: 3.4008, Train Acc: 17.88%, Val Acc: 19.93%, Test Acc: 20.53%  
Epoch 4/150, Loss: 3.2111, Train Acc: 21.34%, Val Acc: 22.76%, Test Acc: 23.04%  
Epoch 5/150, Loss: 3.0624, Train Acc: 24.06%, Val Acc: 23.62%, Test Acc: 23.55%  
Epoch 6/150, Loss: 2.9283, Train Acc: 26.82%, Val Acc: 27.07%, Test Acc: 27.27%  
Epoch 7/150, Loss: 2.8264, Train Acc: 28.87%, Val Acc: 27.01%, Test Acc: 27.03%  
Epoch 8/150, Loss: 2.7578, Train Acc: 30.10%, Val Acc: 28.78%, Test Acc: 29.75%  
Epoch 9/150, Loss: 2.6904, Train Acc: 31.46%, Val Acc: 29.90%, Test Acc: 30.45%  
Checkpoint saved at epoch 10
Epoch 10/150, Loss: 2.6390, Train Acc: 32.53%, Val Acc: 31.13%, Test Acc: 31.54%  
Epoch 11/150, Loss: 2.5928, Train Acc: 33.48%, Val Acc: 31.90%, Test Acc: 31.71%  
Epoch 12/150, Loss: 2.5318, Train Acc: 34.80%, Val Acc: 32.58%, Test Acc: 32.94%  
Epoch 13/150, Loss: 2.5020, Train Acc: 35.52%, Val Acc: 33.20%, Test Acc: 32.98%  
Epoch 14/150, Loss: 2.4730, Train Acc: 36.17%, Val Acc: 34.00%, Test Acc: 33.85%  
Epoch 15/150, Loss: 2.4403, Train Acc: 36.85%, Val Acc: 33.79%, Test Acc: 34.26%  
Epoch 16/150, Loss: 2.4154, Train Acc: 37.33%, Val Acc: 34.25%, Test Acc: 35.06%  
Epoch 17/150, Loss: 2.3725, Train Acc: 38.02%, Val Acc: 34.23%, Test Acc: 34.70%  
Epoch 18/150, Loss: 2.3503, Train Acc: 38.60%, Val Acc: 35.66%, Test Acc: 36.12%  
Epoch 19/150, Loss: 2.3324, Train Acc: 38.98%, Val Acc: 34.42%, Test Acc: 34.56%  
Checkpoint saved at epoch 20
Epoch 20/150, Loss: 2.3060, Train Acc: 39.29%, Val Acc: 35.22%, Test Acc: 36.12%  
Epoch 21/150, Loss: 2.2907, Train Acc: 39.69%, Val Acc: 34.98%, Test Acc: 35.94%  
Epoch 22/150, Loss: 2.2670, Train Acc: 40.26%, Val Acc: 36.35%, Test Acc: 36.36%  
Epoch 23/150, Loss: 2.2467, Train Acc: 41.00%, Val Acc: 36.89%, Test Acc: 36.71%  
Epoch 24/150, Loss: 2.2251, Train Acc: 41.30%, Val Acc: 37.61%, Test Acc: 37.49%  
Epoch 25/150, Loss: 2.2122, Train Acc: 41.52%, Val Acc: 36.24%, Test Acc: 37.44%  
Epoch 26/150, Loss: 2.1876, Train Acc: 42.40%, Val Acc: 37.16%, Test Acc: 37.41%  
Epoch 27/150, Loss: 2.1764, Train Acc: 42.19%, Val Acc: 37.41%, Test Acc: 37.55%  
Epoch 28/150, Loss: 2.1628, Train Acc: 42.30%, Val Acc: 36.30%, Test Acc: 36.26%  
Epoch 29/150, Loss: 2.1334, Train Acc: 43.23%, Val Acc: 36.87%, Test Acc: 36.92%  
Checkpoint saved at epoch 30
Epoch 30/150, Loss: 2.1290, Train Acc: 43.12%, Val Acc: 37.82%, Test Acc: 37.74%  
Epoch 31/150, Loss: 2.1095, Train Acc: 43.65%, Val Acc: 37.56%, Test Acc: 38.14%  
Epoch 32/150, Loss: 2.0933, Train Acc: 44.25%, Val Acc: 38.15%, Test Acc: 37.91%  
Epoch 33/150, Loss: 2.0941, Train Acc: 43.80%, Val Acc: 38.29%, Test Acc: 37.84%  
Epoch 34/150, Loss: 2.0712, Train Acc: 44.32%, Val Acc: 38.78%, Test Acc: 38.27%  
Epoch 35/150, Loss: 2.0641, Train Acc: 44.66%, Val Acc: 38.52%, Test Acc: 39.22%  
Epoch 36/150, Loss: 2.0375, Train Acc: 45.24%, Val Acc: 38.23%, Test Acc: 38.44%  
Epoch 37/150, Loss: 2.0388, Train Acc: 45.22%, Val Acc: 38.26%, Test Acc: 37.78%  
Epoch 38/150, Loss: 2.0246, Train Acc: 45.42%, Val Acc: 39.27%, Test Acc: 39.29%  
Epoch 39/150, Loss: 2.0086, Train Acc: 46.19%, Val Acc: 39.23%, Test Acc: 39.02%  
Checkpoint saved at epoch 40
Epoch 40/150, Loss: 2.0082, Train Acc: 45.97%, Val Acc: 38.42%, Test Acc: 38.67%  
Epoch 41/150, Loss: 1.9880, Train Acc: 46.32%, Val Acc: 38.94%, Test Acc: 39.63%  
Epoch 42/150, Loss: 1.9893, Train Acc: 46.39%, Val Acc: 38.47%, Test Acc: 38.34%  
Epoch 43/150, Loss: 1.9685, Train Acc: 46.98%, Val Acc: 38.62%, Test Acc: 39.70%  
Epoch 44/150, Loss: 1.9580, Train Acc: 46.92%, Val Acc: 38.96%, Test Acc: 39.28%  
Epoch 45/150, Loss: 1.9581, Train Acc: 46.88%, Val Acc: 38.79%, Test Acc: 39.56%  
Epoch 46/150, Loss: 1.9399, Train Acc: 47.33%, Val Acc: 39.85%, Test Acc: 39.54%  
Epoch 47/150, Loss: 1.9364, Train Acc: 47.58%, Val Acc: 40.58%, Test Acc: 40.79%  
Epoch 48/150, Loss: 1.9116, Train Acc: 48.00%, Val Acc: 40.30%, Test Acc: 40.04%  
Epoch 49/150, Loss: 1.9014, Train Acc: 48.13%, Val Acc: 39.89%, Test Acc: 40.54%  
Checkpoint saved at epoch 50
Epoch 50/150, Loss: 1.8996, Train Acc: 48.26%, Val Acc: 40.12%, Test Acc: 40.62%  
Epoch 51/150, Loss: 1.8797, Train Acc: 48.79%, Val Acc: 39.28%, Test Acc: 39.68%  
Epoch 52/150, Loss: 1.8863, Train Acc: 48.47%, Val Acc: 39.93%, Test Acc: 40.11%  
Epoch 53/150, Loss: 1.8674, Train Acc: 48.62%, Val Acc: 40.24%, Test Acc: 40.29%  
Epoch 54/150, Loss: 1.8590, Train Acc: 49.51%, Val Acc: 40.66%, Test Acc: 40.67%  
Epoch 55/150, Loss: 1.8420, Train Acc: 49.33%, Val Acc: 39.94%, Test Acc: 41.13%  
Epoch 56/150, Loss: 1.8335, Train Acc: 49.77%, Val Acc: 40.12%, Test Acc: 40.47%  
Epoch 57/150, Loss: 1.8346, Train Acc: 49.85%, Val Acc: 40.21%, Test Acc: 41.01%  
Epoch 58/150, Loss: 1.8262, Train Acc: 49.61%, Val Acc: 40.09%, Test Acc: 40.57%  
Epoch 59/150, Loss: 1.8193, Train Acc: 49.95%, Val Acc: 40.99%, Test Acc: 41.36%  
Checkpoint saved at epoch 60
Epoch 60/150, Loss: 1.8015, Train Acc: 50.52%, Val Acc: 40.14%, Test Acc: 40.95%  
Epoch 61/150, Loss: 1.8088, Train Acc: 50.44%, Val Acc: 40.82%, Test Acc: 40.62%  
Epoch 62/150, Loss: 1.7916, Train Acc: 50.71%, Val Acc: 41.85%, Test Acc: 42.27%  
Epoch 63/150, Loss: 1.7807, Train Acc: 51.23%, Val Acc: 40.91%, Test Acc: 41.71%  
Epoch 64/150, Loss: 1.7719, Train Acc: 51.12%, Val Acc: 41.23%, Test Acc: 41.19%  
Epoch 65/150, Loss: 1.7648, Train Acc: 51.34%, Val Acc: 40.72%, Test Acc: 41.68%  
Epoch 66/150, Loss: 1.7606, Train Acc: 51.31%, Val Acc: 41.61%, Test Acc: 41.54%  
Epoch 67/150, Loss: 1.7431, Train Acc: 51.89%, Val Acc: 41.63%, Test Acc: 41.52%  
Epoch 68/150, Loss: 1.7527, Train Acc: 51.71%, Val Acc: 41.39%, Test Acc: 41.82%  
Epoch 69/150, Loss: 1.7252, Train Acc: 52.46%, Val Acc: 41.33%, Test Acc: 41.87%  
Checkpoint saved at epoch 70
Epoch 70/150, Loss: 1.7290, Train Acc: 52.03%, Val Acc: 41.97%, Test Acc: 41.90%  
Epoch 71/150, Loss: 1.7219, Train Acc: 52.48%, Val Acc: 41.28%, Test Acc: 42.30%  
Epoch 72/150, Loss: 1.7108, Train Acc: 52.85%, Val Acc: 41.48%, Test Acc: 41.97%  
Epoch 73/150, Loss: 1.6863, Train Acc: 53.20%, Val Acc: 42.23%, Test Acc: 41.91%  
Epoch 74/150, Loss: 1.6873, Train Acc: 53.28%, Val Acc: 41.73%, Test Acc: 42.67%  
Epoch 75/150, Loss: 1.6774, Train Acc: 53.49%, Val Acc: 41.61%, Test Acc: 42.14%  
Epoch 76/150, Loss: 1.6870, Train Acc: 53.15%, Val Acc: 42.72%, Test Acc: 42.79%  
Epoch 77/150, Loss: 1.6652, Train Acc: 54.25%, Val Acc: 42.59%, Test Acc: 42.40%  
Epoch 78/150, Loss: 1.6568, Train Acc: 53.77%, Val Acc: 42.51%, Test Acc: 42.52%  
Epoch 79/150, Loss: 1.6496, Train Acc: 53.86%, Val Acc: 42.39%, Test Acc: 43.19%  
Checkpoint saved at epoch 80
Epoch 80/150, Loss: 1.6368, Train Acc: 54.29%, Val Acc: 42.44%, Test Acc: 42.98%  
Epoch 81/150, Loss: 1.6366, Train Acc: 54.38%, Val Acc: 43.11%, Test Acc: 42.42%  
Epoch 82/150, Loss: 1.6447, Train Acc: 54.08%, Val Acc: 42.48%, Test Acc: 43.31%  
Epoch 83/150, Loss: 1.6313, Train Acc: 54.45%, Val Acc: 42.19%, Test Acc: 42.56%  
Epoch 84/150, Loss: 1.6123, Train Acc: 54.94%, Val Acc: 42.35%, Test Acc: 43.30%  
Epoch 85/150, Loss: 1.6051, Train Acc: 55.04%, Val Acc: 42.57%, Test Acc: 43.67%  
Epoch 86/150, Loss: 1.6069, Train Acc: 55.02%, Val Acc: 42.45%, Test Acc: 43.14%  
Epoch 87/150, Loss: 1.5975, Train Acc: 55.65%, Val Acc: 42.62%, Test Acc: 43.32%  
Epoch 88/150, Loss: 1.5986, Train Acc: 55.62%, Val Acc: 42.68%, Test Acc: 43.39%  
Epoch 89/150, Loss: 1.5879, Train Acc: 55.48%, Val Acc: 43.58%, Test Acc: 43.59%  
Checkpoint saved at epoch 90
Epoch 90/150, Loss: 1.5807, Train Acc: 56.05%, Val Acc: 43.49%, Test Acc: 43.13%  
Epoch 91/150, Loss: 1.5738, Train Acc: 55.98%, Val Acc: 42.78%, Test Acc: 42.81%  
Epoch 92/150, Loss: 1.5713, Train Acc: 55.92%, Val Acc: 42.53%, Test Acc: 43.26%  
Epoch 93/150, Loss: 1.5601, Train Acc: 56.42%, Val Acc: 43.69%, Test Acc: 43.09%  
Epoch 94/150, Loss: 1.5539, Train Acc: 56.44%, Val Acc: 42.95%, Test Acc: 43.26%  
Epoch 95/150, Loss: 1.5524, Train Acc: 56.47%, Val Acc: 43.26%, Test Acc: 44.04%  
Epoch 96/150, Loss: 1.5427, Train Acc: 56.72%, Val Acc: 43.20%, Test Acc: 43.35%  
Epoch 97/150, Loss: 1.5234, Train Acc: 57.05%, Val Acc: 43.95%, Test Acc: 43.65%  
Epoch 98/150, Loss: 1.5242, Train Acc: 57.29%, Val Acc: 43.47%, Test Acc: 44.08%  
Epoch 99/150, Loss: 1.5140, Train Acc: 57.49%, Val Acc: 43.10%, Test Acc: 44.42%  
Checkpoint saved at epoch 100
Epoch 100/150, Loss: 1.5205, Train Acc: 57.48%, Val Acc: 43.41%, Test Acc: 44.60%  
Epoch 101/150, Loss: 1.5150, Train Acc: 57.28%, Val Acc: 43.54%, Test Acc: 43.74%  
Epoch 102/150, Loss: 1.5077, Train Acc: 57.43%, Val Acc: 44.21%, Test Acc: 44.04%  
Epoch 103/150, Loss: 1.4978, Train Acc: 57.89%, Val Acc: 43.43%, Test Acc: 44.02%  
Epoch 104/150, Loss: 1.4873, Train Acc: 58.03%, Val Acc: 43.07%, Test Acc: 43.49%  
Epoch 105/150, Loss: 1.4810, Train Acc: 57.84%, Val Acc: 43.39%, Test Acc: 43.35%  
Epoch 106/150, Loss: 1.4829, Train Acc: 58.05%, Val Acc: 43.55%, Test Acc: 43.81%  
Epoch 107/150, Loss: 1.4801, Train Acc: 58.05%, Val Acc: 43.62%, Test Acc: 43.63%  
Epoch 108/150, Loss: 1.4781, Train Acc: 58.19%, Val Acc: 43.45%, Test Acc: 44.22%  
Epoch 109/150, Loss: 1.4696, Train Acc: 58.66%, Val Acc: 44.28%, Test Acc: 43.57%  
Checkpoint saved at epoch 110
Epoch 110/150, Loss: 1.4582, Train Acc: 58.70%, Val Acc: 43.95%, Test Acc: 44.54%  
Epoch 111/150, Loss: 1.4571, Train Acc: 58.76%, Val Acc: 43.64%, Test Acc: 44.50%  
Epoch 112/150, Loss: 1.4479, Train Acc: 59.11%, Val Acc: 43.91%, Test Acc: 44.07%  
Epoch 113/150, Loss: 1.4505, Train Acc: 59.00%, Val Acc: 43.49%, Test Acc: 44.54%  
Epoch 114/150, Loss: 1.4415, Train Acc: 59.11%, Val Acc: 43.35%, Test Acc: 45.14%  
Epoch 115/150, Loss: 1.4386, Train Acc: 59.23%, Val Acc: 44.51%, Test Acc: 44.64%  
Epoch 116/150, Loss: 1.4324, Train Acc: 59.27%, Val Acc: 43.78%, Test Acc: 45.05%  
Epoch 117/150, Loss: 1.4294, Train Acc: 59.52%, Val Acc: 43.98%, Test Acc: 44.04%  
Epoch 118/150, Loss: 1.4323, Train Acc: 59.58%, Val Acc: 44.22%, Test Acc: 44.07%  
Epoch 119/150, Loss: 1.4207, Train Acc: 59.91%, Val Acc: 43.97%, Test Acc: 43.87%  
Checkpoint saved at epoch 120
Epoch 120/150, Loss: 1.4169, Train Acc: 59.79%, Val Acc: 44.50%, Test Acc: 45.14%  
Epoch 121/150, Loss: 1.4227, Train Acc: 59.85%, Val Acc: 43.98%, Test Acc: 44.55%  
Epoch 122/150, Loss: 1.4149, Train Acc: 59.89%, Val Acc: 44.74%, Test Acc: 44.90%  
Epoch 123/150, Loss: 1.4109, Train Acc: 59.90%, Val Acc: 44.57%, Test Acc: 44.52%  
Epoch 124/150, Loss: 1.4195, Train Acc: 59.85%, Val Acc: 44.12%, Test Acc: 44.61%  
Epoch 125/150, Loss: 1.4055, Train Acc: 60.23%, Val Acc: 44.41%, Test Acc: 44.45%  
Epoch 126/150, Loss: 1.3969, Train Acc: 60.29%, Val Acc: 44.30%, Test Acc: 44.91%  
Epoch 127/150, Loss: 1.3987, Train Acc: 60.77%, Val Acc: 44.52%, Test Acc: 44.23%  
Epoch 128/150, Loss: 1.3918, Train Acc: 60.52%, Val Acc: 44.46%, Test Acc: 45.07%  
Epoch 129/150, Loss: 1.3946, Train Acc: 60.57%, Val Acc: 44.74%, Test Acc: 44.87%  
Checkpoint saved at epoch 130
Epoch 130/150, Loss: 1.3993, Train Acc: 60.70%, Val Acc: 44.30%, Test Acc: 45.22%  
Epoch 131/150, Loss: 1.3910, Train Acc: 60.81%, Val Acc: 45.00%, Test Acc: 44.30%  
Epoch 132/150, Loss: 1.3875, Train Acc: 60.41%, Val Acc: 44.45%, Test Acc: 44.88%  
Epoch 133/150, Loss: 1.3874, Train Acc: 60.81%, Val Acc: 44.54%, Test Acc: 44.72%  
Epoch 134/150, Loss: 1.3839, Train Acc: 60.78%, Val Acc: 44.31%, Test Acc: 44.80%  
Epoch 135/150, Loss: 1.3781, Train Acc: 60.95%, Val Acc: 44.44%, Test Acc: 45.46%  
Epoch 136/150, Loss: 1.3775, Train Acc: 61.00%, Val Acc: 44.71%, Test Acc: 44.54%  
Epoch 137/150, Loss: 1.3739, Train Acc: 60.97%, Val Acc: 44.69%, Test Acc: 45.69%  
Epoch 138/150, Loss: 1.3856, Train Acc: 60.57%, Val Acc: 44.28%, Test Acc: 44.31%  
Epoch 139/150, Loss: 1.3774, Train Acc: 60.98%, Val Acc: 44.83%, Test Acc: 44.90%  
Checkpoint saved at epoch 140
Epoch 140/150, Loss: 1.3701, Train Acc: 61.30%, Val Acc: 45.40%, Test Acc: 45.32%  
Epoch 141/150, Loss: 1.3754, Train Acc: 60.97%, Val Acc: 44.74%, Test Acc: 44.48%  
Epoch 142/150, Loss: 1.3685, Train Acc: 61.12%, Val Acc: 44.45%, Test Acc: 45.41%  
Epoch 143/150, Loss: 1.3789, Train Acc: 61.08%, Val Acc: 44.93%, Test Acc: 45.62%  
Epoch 144/150, Loss: 1.3654, Train Acc: 61.20%, Val Acc: 44.58%, Test Acc: 45.03%  
Epoch 145/150, Loss: 1.3665, Train Acc: 61.26%, Val Acc: 45.27%, Test Acc: 45.49%  
Epoch 146/150, Loss: 1.3673, Train Acc: 61.15%, Val Acc: 44.88%, Test Acc: 44.82%  
Epoch 147/150, Loss: 1.3700, Train Acc: 61.03%, Val Acc: 45.35%, Test Acc: 45.32%  
Epoch 148/150, Loss: 1.3636, Train Acc: 61.27%, Val Acc: 44.73%, Test Acc: 45.26%  
Epoch 149/150, Loss: 1.3628, Train Acc: 61.30%, Val Acc: 45.06%, Test Acc: 44.98%  
Checkpoint saved at epoch 150
Epoch 150/150, Loss: 1.3672, Train Acc: 61.44%, Val Acc: 44.80%, Test Acc: 45.48%

#### Plots

![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-2/train_loss.png)
![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-2/val_loss.png)
![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-2/test_loss.png)
![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-2/train_accuracy.png)
![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-2/val_accuracy.png)
![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-2/test_accuracy.png)

# Train with AdamW

| Epochs | batch_size | beta | weight_decay | learning_rate |
| ------ | ---------- | ---- | ------------ | ------------- |
| 150    | 128        | 0.9  | 1e-3         | 1e-3          |

#### Results log

Epoch 1/150, Loss: 4.1140, Train Acc: 6.88%, Val Acc: 10.60%, Test Acc: 10.12%  
Epoch 2/150, Loss: 3.6661, Train Acc: 13.39%, Val Acc: 16.30%, Test Acc: 15.52%  
Epoch 3/150, Loss: 3.3855, Train Acc: 18.02%, Val Acc: 19.51%, Test Acc: 20.20%  
Epoch 4/150, Loss: 3.2009, Train Acc: 21.59%, Val Acc: 23.21%, Test Acc: 22.94%  
Epoch 5/150, Loss: 3.0487, Train Acc: 24.31%, Val Acc: 24.63%, Test Acc: 24.01%  
Epoch 6/150, Loss: 2.9215, Train Acc: 26.82%, Val Acc: 26.82%, Test Acc: 26.69%  
Epoch 7/150, Loss: 2.8187, Train Acc: 29.09%, Val Acc: 27.09%, Test Acc: 27.46%  
Epoch 8/150, Loss: 2.7396, Train Acc: 30.50%, Val Acc: 29.57%, Test Acc: 29.63%  
Epoch 9/150, Loss: 2.6750, Train Acc: 31.81%, Val Acc: 30.09%, Test Acc: 30.64%  
Checkpoint saved at epoch 10
Epoch 10/150, Loss: 2.6172, Train Acc: 33.09%, Val Acc: 31.42%, Test Acc: 31.59%  
Epoch 11/150, Loss: 2.5690, Train Acc: 33.79%, Val Acc: 32.25%, Test Acc: 32.46%  
Epoch 12/150, Loss: 2.5179, Train Acc: 34.98%, Val Acc: 32.24%, Test Acc: 32.57%  
Epoch 13/150, Loss: 2.4783, Train Acc: 35.84%, Val Acc: 33.88%, Test Acc: 33.28%  
Epoch 14/150, Loss: 2.4433, Train Acc: 36.65%, Val Acc: 33.77%, Test Acc: 33.25%  
Epoch 15/150, Loss: 2.4205, Train Acc: 37.02%, Val Acc: 33.72%, Test Acc: 34.23%  
Epoch 16/150, Loss: 2.3960, Train Acc: 37.55%, Val Acc: 35.58%, Test Acc: 35.55%  
Epoch 17/150, Loss: 2.3497, Train Acc: 38.73%, Val Acc: 35.54%, Test Acc: 35.24%  
Epoch 18/150, Loss: 2.3304, Train Acc: 39.12%, Val Acc: 35.29%, Test Acc: 36.39%  
Epoch 19/150, Loss: 2.3053, Train Acc: 39.40%, Val Acc: 35.57%, Test Acc: 35.77%  
Checkpoint saved at epoch 20
Epoch 20/150, Loss: 2.2911, Train Acc: 39.81%, Val Acc: 35.17%, Test Acc: 36.50%  
Epoch 21/150, Loss: 2.2568, Train Acc: 40.16%, Val Acc: 35.72%, Test Acc: 36.42%  
Epoch 22/150, Loss: 2.2466, Train Acc: 40.71%, Val Acc: 35.85%, Test Acc: 35.92%  
Epoch 23/150, Loss: 2.2205, Train Acc: 41.15%, Val Acc: 37.60%, Test Acc: 37.21%  
Epoch 24/150, Loss: 2.1930, Train Acc: 41.64%, Val Acc: 37.79%, Test Acc: 37.37%  
Epoch 25/150, Loss: 2.1996, Train Acc: 41.71%, Val Acc: 37.46%, Test Acc: 37.05%  
Epoch 26/150, Loss: 2.1674, Train Acc: 42.46%, Val Acc: 37.36%, Test Acc: 37.08%  
Epoch 27/150, Loss: 2.1442, Train Acc: 42.66%, Val Acc: 37.69%, Test Acc: 37.54%  
Epoch 28/150, Loss: 2.1375, Train Acc: 43.17%, Val Acc: 38.06%, Test Acc: 38.14%  
Epoch 29/150, Loss: 2.1202, Train Acc: 43.48%, Val Acc: 37.16%, Test Acc: 37.09%  
Checkpoint saved at epoch 30
Epoch 30/150, Loss: 2.1106, Train Acc: 43.40%, Val Acc: 37.81%, Test Acc: 38.21%  
Epoch 31/150, Loss: 2.0838, Train Acc: 44.01%, Val Acc: 38.65%, Test Acc: 38.22%  
Epoch 32/150, Loss: 2.0734, Train Acc: 44.52%, Val Acc: 39.03%, Test Acc: 38.61%  
Epoch 33/150, Loss: 2.0702, Train Acc: 44.17%, Val Acc: 38.36%, Test Acc: 38.23%  
Epoch 34/150, Loss: 2.0461, Train Acc: 44.82%, Val Acc: 38.97%, Test Acc: 39.56%  
Epoch 35/150, Loss: 2.0293, Train Acc: 45.37%, Val Acc: 38.45%, Test Acc: 39.24%  
Epoch 36/150, Loss: 2.0217, Train Acc: 45.72%, Val Acc: 38.80%, Test Acc: 38.82%  
Epoch 37/150, Loss: 2.0127, Train Acc: 45.56%, Val Acc: 38.44%, Test Acc: 38.65%  
Epoch 38/150, Loss: 2.0135, Train Acc: 45.59%, Val Acc: 39.53%, Test Acc: 39.30%  
Epoch 39/150, Loss: 1.9863, Train Acc: 46.27%, Val Acc: 39.70%, Test Acc: 39.18%  
Checkpoint saved at epoch 40
Epoch 40/150, Loss: 1.9835, Train Acc: 46.20%, Val Acc: 38.79%, Test Acc: 39.05%  
Epoch 41/150, Loss: 1.9721, Train Acc: 46.95%, Val Acc: 39.52%, Test Acc: 40.56%  
Epoch 42/150, Loss: 1.9697, Train Acc: 46.77%, Val Acc: 38.86%, Test Acc: 39.08%  
Epoch 43/150, Loss: 1.9446, Train Acc: 47.34%, Val Acc: 39.90%, Test Acc: 40.48%  
Epoch 44/150, Loss: 1.9429, Train Acc: 47.34%, Val Acc: 39.53%, Test Acc: 39.67%  
Epoch 45/150, Loss: 1.9211, Train Acc: 47.86%, Val Acc: 39.56%, Test Acc: 39.87%  
Epoch 46/150, Loss: 1.9198, Train Acc: 47.99%, Val Acc: 40.06%, Test Acc: 40.24%  
Epoch 47/150, Loss: 1.9126, Train Acc: 48.02%, Val Acc: 40.30%, Test Acc: 40.62%  
Epoch 48/150, Loss: 1.8964, Train Acc: 48.31%, Val Acc: 40.32%, Test Acc: 40.51%  
Epoch 49/150, Loss: 1.8814, Train Acc: 48.97%, Val Acc: 40.32%, Test Acc: 40.68%  
Checkpoint saved at epoch 50
Epoch 50/150, Loss: 1.8837, Train Acc: 48.57%, Val Acc: 40.38%, Test Acc: 40.26%  
Epoch 51/150, Loss: 1.8715, Train Acc: 48.77%, Val Acc: 39.86%, Test Acc: 40.44%  
Epoch 52/150, Loss: 1.8767, Train Acc: 48.68%, Val Acc: 40.12%, Test Acc: 40.25%  
Epoch 53/150, Loss: 1.8535, Train Acc: 49.17%, Val Acc: 40.72%, Test Acc: 40.53%  
Epoch 54/150, Loss: 1.8466, Train Acc: 49.37%, Val Acc: 40.93%, Test Acc: 40.77%  
Epoch 55/150, Loss: 1.8453, Train Acc: 49.39%, Val Acc: 41.46%, Test Acc: 41.70%  
Epoch 56/150, Loss: 1.8283, Train Acc: 50.04%, Val Acc: 40.91%, Test Acc: 40.57%  
Epoch 57/150, Loss: 1.8257, Train Acc: 49.95%, Val Acc: 40.87%, Test Acc: 41.49%  
Epoch 58/150, Loss: 1.8089, Train Acc: 50.28%, Val Acc: 41.41%, Test Acc: 41.63%  
Epoch 59/150, Loss: 1.8177, Train Acc: 50.19%, Val Acc: 41.40%, Test Acc: 41.21%  
Checkpoint saved at epoch 60
Epoch 60/150, Loss: 1.7919, Train Acc: 50.78%, Val Acc: 40.91%, Test Acc: 41.68%  
Epoch 61/150, Loss: 1.7942, Train Acc: 50.72%, Val Acc: 40.89%, Test Acc: 40.72%  
Epoch 62/150, Loss: 1.7806, Train Acc: 51.16%, Val Acc: 41.74%, Test Acc: 41.57%  
Epoch 63/150, Loss: 1.7776, Train Acc: 51.11%, Val Acc: 40.68%, Test Acc: 41.48%  
Epoch 64/150, Loss: 1.7694, Train Acc: 51.13%, Val Acc: 41.71%, Test Acc: 40.79%  
Epoch 65/150, Loss: 1.7546, Train Acc: 51.49%, Val Acc: 41.23%, Test Acc: 41.88%  
Epoch 66/150, Loss: 1.7383, Train Acc: 52.03%, Val Acc: 41.56%, Test Acc: 42.27%  
Epoch 67/150, Loss: 1.7392, Train Acc: 51.72%, Val Acc: 41.76%, Test Acc: 41.39%  
Epoch 68/150, Loss: 1.7440, Train Acc: 51.57%, Val Acc: 41.31%, Test Acc: 42.14%  
Epoch 69/150, Loss: 1.7229, Train Acc: 52.23%, Val Acc: 40.96%, Test Acc: 42.10%  
Checkpoint saved at epoch 70
Epoch 70/150, Loss: 1.7239, Train Acc: 52.11%, Val Acc: 41.90%, Test Acc: 41.91%  
Epoch 71/150, Loss: 1.7156, Train Acc: 52.27%, Val Acc: 42.72%, Test Acc: 42.61%  
Epoch 72/150, Loss: 1.7000, Train Acc: 53.01%, Val Acc: 41.87%, Test Acc: 43.00%  
Epoch 73/150, Loss: 1.6936, Train Acc: 52.91%, Val Acc: 41.79%, Test Acc: 42.69%  
Epoch 74/150, Loss: 1.6871, Train Acc: 53.16%, Val Acc: 42.19%, Test Acc: 42.44%  
Epoch 75/150, Loss: 1.6846, Train Acc: 52.82%, Val Acc: 42.04%, Test Acc: 42.21%  
Epoch 76/150, Loss: 1.6769, Train Acc: 53.31%, Val Acc: 42.90%, Test Acc: 43.31%  
Epoch 77/150, Loss: 1.6554, Train Acc: 53.91%, Val Acc: 42.43%, Test Acc: 42.31%  
Epoch 78/150, Loss: 1.6543, Train Acc: 53.90%, Val Acc: 42.92%, Test Acc: 42.61%  
Epoch 79/150, Loss: 1.6438, Train Acc: 54.23%, Val Acc: 42.66%, Test Acc: 43.65%  
Checkpoint saved at epoch 80
Epoch 80/150, Loss: 1.6470, Train Acc: 54.34%, Val Acc: 41.85%, Test Acc: 43.30%  
Epoch 81/150, Loss: 1.6316, Train Acc: 54.59%, Val Acc: 42.21%, Test Acc: 43.27%  
Epoch 82/150, Loss: 1.6342, Train Acc: 54.53%, Val Acc: 42.49%, Test Acc: 43.63%  
Epoch 83/150, Loss: 1.6172, Train Acc: 54.93%, Val Acc: 42.84%, Test Acc: 42.89%  
interrupted here

# Train with AdamW

| Epochs | batch_size | beta | weight_decay | learning_rate |
| ------ | ---------- | ---- | ------------ | ------------- |
| 150    | 128        | 0.9  | 1e-5         | 1e-3          |

#### Results log

Epoch 1/150, Loss: 4.1199, Train Acc: 6.69%, Val Acc: 10.79%, Test Acc: 10.48%  
Epoch 2/150, Loss: 3.6673, Train Acc: 13.26%, Val Acc: 15.38%, Test Acc: 15.28%  
Epoch 3/150, Loss: 3.3745, Train Acc: 18.26%, Val Acc: 19.23%, Test Acc: 19.48%  
Epoch 4/150, Loss: 3.1980, Train Acc: 21.38%, Val Acc: 23.31%, Test Acc: 23.29%  
Epoch 5/150, Loss: 3.0536, Train Acc: 24.18%, Val Acc: 24.07%, Test Acc: 24.33%  
Epoch 6/150, Loss: 2.9324, Train Acc: 26.55%, Val Acc: 26.85%, Test Acc: 27.10%  
Epoch 7/150, Loss: 2.8273, Train Acc: 28.84%, Val Acc: 26.40%, Test Acc: 26.95%  
Epoch 8/150, Loss: 2.7522, Train Acc: 30.17%, Val Acc: 28.83%, Test Acc: 28.70%  
Epoch 9/150, Loss: 2.6845, Train Acc: 31.35%, Val Acc: 30.30%, Test Acc: 30.47%  
Checkpoint saved at epoch 10
Epoch 10/150, Loss: 2.6208, Train Acc: 32.84%, Val Acc: 30.84%, Test Acc: 30.53%  
Epoch 11/150, Loss: 2.5727, Train Acc: 33.66%, Val Acc: 32.20%, Test Acc: 32.15%  
Epoch 12/150, Loss: 2.5177, Train Acc: 34.90%, Val Acc: 31.70%, Test Acc: 32.30%  
Epoch 13/150, Loss: 2.4828, Train Acc: 35.79%, Val Acc: 34.22%, Test Acc: 33.41%  
Epoch 14/150, Loss: 2.4522, Train Acc: 36.33%, Val Acc: 33.41%, Test Acc: 33.59%  
Epoch 15/150, Loss: 2.4341, Train Acc: 36.86%, Val Acc: 33.81%, Test Acc: 33.73%  
Epoch 16/150, Loss: 2.3890, Train Acc: 37.62%, Val Acc: 34.54%, Test Acc: 35.22%  
Epoch 17/150, Loss: 2.3587, Train Acc: 38.28%, Val Acc: 34.77%, Test Acc: 34.54%  
Epoch 18/150, Loss: 2.3222, Train Acc: 39.23%, Val Acc: 34.94%, Test Acc: 35.56%  
Epoch 19/150, Loss: 2.3047, Train Acc: 39.41%, Val Acc: 34.58%, Test Acc: 34.98%  
Checkpoint saved at epoch 20
Epoch 20/150, Loss: 2.2824, Train Acc: 40.08%, Val Acc: 35.10%, Test Acc: 36.26%  
Epoch 21/150, Loss: 2.2639, Train Acc: 40.13%, Val Acc: 35.63%, Test Acc: 36.84%  
Epoch 22/150, Loss: 2.2411, Train Acc: 40.96%, Val Acc: 36.20%, Test Acc: 36.38%  
Epoch 23/150, Loss: 2.2169, Train Acc: 41.37%, Val Acc: 36.58%, Test Acc: 36.67%  
Epoch 24/150, Loss: 2.2009, Train Acc: 41.85%, Val Acc: 37.43%, Test Acc: 37.14%  
Epoch 25/150, Loss: 2.1908, Train Acc: 41.83%, Val Acc: 37.19%, Test Acc: 37.44%  
Epoch 26/150, Loss: 2.1550, Train Acc: 42.80%, Val Acc: 37.04%, Test Acc: 37.52%  
Epoch 27/150, Loss: 2.1477, Train Acc: 42.74%, Val Acc: 37.72%, Test Acc: 37.25%  
Epoch 28/150, Loss: 2.1390, Train Acc: 42.94%, Val Acc: 37.27%, Test Acc: 37.12%  
Epoch 29/150, Loss: 2.1052, Train Acc: 43.66%, Val Acc: 36.76%, Test Acc: 37.60%  
Checkpoint saved at epoch 30
Epoch 30/150, Loss: 2.0999, Train Acc: 43.80%, Val Acc: 37.38%, Test Acc: 38.61%  
Epoch 31/150, Loss: 2.0861, Train Acc: 44.13%, Val Acc: 37.65%, Test Acc: 37.85%  
Epoch 32/150, Loss: 2.0562, Train Acc: 45.06%, Val Acc: 38.23%, Test Acc: 38.45%  
Epoch 33/150, Loss: 2.0444, Train Acc: 45.30%, Val Acc: 37.93%, Test Acc: 38.24%  
Epoch 34/150, Loss: 2.0367, Train Acc: 45.30%, Val Acc: 38.40%, Test Acc: 38.88%  
Epoch 35/150, Loss: 2.0278, Train Acc: 45.58%, Val Acc: 38.25%, Test Acc: 38.98%  
Epoch 36/150, Loss: 2.0057, Train Acc: 45.73%, Val Acc: 38.82%, Test Acc: 39.44%  
Epoch 37/150, Loss: 1.9997, Train Acc: 45.95%, Val Acc: 38.55%, Test Acc: 39.22%  
Epoch 38/150, Loss: 1.9932, Train Acc: 46.03%, Val Acc: 38.81%, Test Acc: 39.17%  
Epoch 39/150, Loss: 1.9762, Train Acc: 46.83%, Val Acc: 39.50%, Test Acc: 39.38%  
Checkpoint saved at epoch 40
Epoch 40/150, Loss: 1.9704, Train Acc: 46.52%, Val Acc: 38.36%, Test Acc: 39.44%  
Epoch 41/150, Loss: 1.9551, Train Acc: 46.96%, Val Acc: 38.80%, Test Acc: 39.43%  
Epoch 42/150, Loss: 1.9417, Train Acc: 47.52%, Val Acc: 38.87%, Test Acc: 39.96%  
Epoch 43/150, Loss: 1.9341, Train Acc: 47.66%, Val Acc: 39.49%, Test Acc: 39.92%  
Epoch 44/150, Loss: 1.9363, Train Acc: 47.52%, Val Acc: 38.74%, Test Acc: 39.43%  
Epoch 45/150, Loss: 1.9122, Train Acc: 48.00%, Val Acc: 40.16%, Test Acc: 40.36%  
Epoch 46/150, Loss: 1.9010, Train Acc: 48.31%, Val Acc: 39.12%, Test Acc: 40.58%  
Epoch 47/150, Loss: 1.8882, Train Acc: 48.62%, Val Acc: 40.32%, Test Acc: 41.19%  
Epoch 48/150, Loss: 1.8809, Train Acc: 48.74%, Val Acc: 40.09%, Test Acc: 40.17%  
Epoch 49/150, Loss: 1.8712, Train Acc: 48.94%, Val Acc: 40.62%, Test Acc: 40.70%  
Checkpoint saved at epoch 50
Epoch 50/150, Loss: 1.8691, Train Acc: 49.00%, Val Acc: 39.34%, Test Acc: 40.69%  
Epoch 51/150, Loss: 1.8586, Train Acc: 49.19%, Val Acc: 40.34%, Test Acc: 40.27%  
Epoch 52/150, Loss: 1.8479, Train Acc: 49.22%, Val Acc: 40.77%, Test Acc: 40.75%  
Epoch 53/150, Loss: 1.8366, Train Acc: 49.44%, Val Acc: 40.90%, Test Acc: 40.77%  
Epoch 54/150, Loss: 1.8255, Train Acc: 49.85%, Val Acc: 40.32%, Test Acc: 40.98%  
Epoch 55/150, Loss: 1.8190, Train Acc: 50.16%, Val Acc: 40.39%, Test Acc: 40.83%  
Epoch 56/150, Loss: 1.8024, Train Acc: 50.41%, Val Acc: 40.92%, Test Acc: 41.26%  
Epoch 57/150, Loss: 1.7954, Train Acc: 50.91%, Val Acc: 41.11%, Test Acc: 40.91%  
Epoch 58/150, Loss: 1.7868, Train Acc: 50.91%, Val Acc: 41.01%, Test Acc: 40.22%  
Epoch 59/150, Loss: 1.7942, Train Acc: 50.61%, Val Acc: 41.24%, Test Acc: 41.88%  
Checkpoint saved at epoch 60
Epoch 60/150, Loss: 1.7714, Train Acc: 51.27%, Val Acc: 40.57%, Test Acc: 41.65%  
Epoch 61/150, Loss: 1.7647, Train Acc: 51.44%, Val Acc: 40.88%, Test Acc: 41.29%  
Epoch 62/150, Loss: 1.7533, Train Acc: 51.79%, Val Acc: 40.58%, Test Acc: 42.00%  
Epoch 63/150, Loss: 1.7551, Train Acc: 51.56%, Val Acc: 40.55%, Test Acc: 42.44%  
Epoch 64/150, Loss: 1.7449, Train Acc: 51.74%, Val Acc: 41.57%, Test Acc: 42.21%  
Epoch 65/150, Loss: 1.7353, Train Acc: 51.99%, Val Acc: 40.69%, Test Acc: 41.66%  
Epoch 66/150, Loss: 1.7260, Train Acc: 52.34%, Val Acc: 41.84%, Test Acc: 42.07%  
Epoch 67/150, Loss: 1.7205, Train Acc: 52.52%, Val Acc: 42.43%, Test Acc: 41.92%  
Epoch 68/150, Loss: 1.7042, Train Acc: 52.59%, Val Acc: 41.39%, Test Acc: 42.80%  
Epoch 69/150, Loss: 1.6942, Train Acc: 52.87%, Val Acc: 41.54%, Test Acc: 42.34%  
Checkpoint saved at epoch 70
Epoch 70/150, Loss: 1.6916, Train Acc: 53.03%, Val Acc: 42.18%, Test Acc: 42.62%  
Epoch 71/150, Loss: 1.6955, Train Acc: 52.90%, Val Acc: 41.55%, Test Acc: 42.61%  
Epoch 72/150, Loss: 1.6805, Train Acc: 53.29%, Val Acc: 42.00%, Test Acc: 43.01%  
Epoch 73/150, Loss: 1.6709, Train Acc: 53.38%, Val Acc: 42.12%, Test Acc: 42.53%  
Epoch 74/150, Loss: 1.6582, Train Acc: 54.11%, Val Acc: 42.10%, Test Acc: 42.27%  
Epoch 75/150, Loss: 1.6536, Train Acc: 53.71%, Val Acc: 42.63%, Test Acc: 43.15%  
Epoch 76/150, Loss: 1.6382, Train Acc: 54.54%, Val Acc: 42.44%, Test Acc: 42.76%  
Epoch 77/150, Loss: 1.6429, Train Acc: 54.43%, Val Acc: 42.61%, Test Acc: 42.22%  
Epoch 78/150, Loss: 1.6333, Train Acc: 54.49%, Val Acc: 41.79%, Test Acc: 43.00%  
Epoch 79/150, Loss: 1.6224, Train Acc: 54.69%, Val Acc: 42.18%, Test Acc: 42.22%  
Checkpoint saved at epoch 80
Epoch 80/150, Loss: 1.6228, Train Acc: 54.72%, Val Acc: 42.31%, Test Acc: 42.83%  
Epoch 81/150, Loss: 1.6119, Train Acc: 54.94%, Val Acc: 42.54%, Test Acc: 42.78%  
Epoch 82/150, Loss: 1.6100, Train Acc: 54.94%, Val Acc: 42.10%, Test Acc: 43.36%  
Epoch 83/150, Loss: 1.5965, Train Acc: 55.12%, Val Acc: 42.53%, Test Acc: 43.33%  
Epoch 84/150, Loss: 1.5903, Train Acc: 55.42%, Val Acc: 42.73%, Test Acc: 43.52%  
Epoch 85/150, Loss: 1.5835, Train Acc: 55.62%, Val Acc: 43.26%, Test Acc: 43.03%  
Epoch 86/150, Loss: 1.5708, Train Acc: 55.92%, Val Acc: 42.32%, Test Acc: 43.63%  
Epoch 87/150, Loss: 1.5681, Train Acc: 55.81%, Val Acc: 42.13%, Test Acc: 43.23%  
Epoch 88/150, Loss: 1.5688, Train Acc: 56.22%, Val Acc: 42.85%, Test Acc: 43.66%  
Epoch 89/150, Loss: 1.5556, Train Acc: 56.44%, Val Acc: 42.76%, Test Acc: 43.55%  
Checkpoint saved at epoch 90
Epoch 90/150, Loss: 1.5444, Train Acc: 56.78%, Val Acc: 42.63%, Test Acc: 43.49%  
Epoch 91/150, Loss: 1.5453, Train Acc: 56.31%, Val Acc: 43.10%, Test Acc: 42.89%  
Epoch 92/150, Loss: 1.5356, Train Acc: 56.80%, Val Acc: 43.44%, Test Acc: 43.60%  
Epoch 93/150, Loss: 1.5374, Train Acc: 56.68%, Val Acc: 43.38%, Test Acc: 42.85%  
Epoch 94/150, Loss: 1.5228, Train Acc: 57.09%, Val Acc: 43.75%, Test Acc: 44.53%  
Epoch 95/150, Loss: 1.5141, Train Acc: 57.26%, Val Acc: 43.20%, Test Acc: 43.53%  
Epoch 96/150, Loss: 1.5082, Train Acc: 57.42%, Val Acc: 43.43%, Test Acc: 43.60%  
Epoch 97/150, Loss: 1.4938, Train Acc: 57.72%, Val Acc: 43.33%, Test Acc: 43.63%  
Epoch 98/150, Loss: 1.4964, Train Acc: 57.82%, Val Acc: 43.99%, Test Acc: 44.49%  
Epoch 99/150, Loss: 1.4881, Train Acc: 58.06%, Val Acc: 42.86%, Test Acc: 44.15%  
Checkpoint saved at epoch 100
Epoch 100/150, Loss: 1.4828, Train Acc: 58.25%, Val Acc: 42.78%, Test Acc: 43.55%  
Epoch 101/150, Loss: 1.4800, Train Acc: 58.09%, Val Acc: 43.30%, Test Acc: 43.95%  
Epoch 102/150, Loss: 1.4717, Train Acc: 58.12%, Val Acc: 43.99%, Test Acc: 43.36%  
Epoch 103/150, Loss: 1.4641, Train Acc: 58.38%, Val Acc: 43.97%, Test Acc: 43.72%  
Epoch 104/150, Loss: 1.4520, Train Acc: 58.68%, Val Acc: 43.20%, Test Acc: 43.55%  
Epoch 105/150, Loss: 1.4588, Train Acc: 58.55%, Val Acc: 43.79%, Test Acc: 43.96%  
Epoch 106/150, Loss: 1.4454, Train Acc: 59.07%, Val Acc: 44.04%, Test Acc: 44.11%  
Epoch 107/150, Loss: 1.4477, Train Acc: 58.79%, Val Acc: 43.81%, Test Acc: 44.91%  
Epoch 108/150, Loss: 1.4511, Train Acc: 58.76%, Val Acc: 43.33%, Test Acc: 43.65%  
Epoch 109/150, Loss: 1.4444, Train Acc: 59.03%, Val Acc: 43.94%, Test Acc: 43.51%  
Checkpoint saved at epoch 110
Epoch 110/150, Loss: 1.4257, Train Acc: 59.49%, Val Acc: 43.89%, Test Acc: 44.35%  
Epoch 111/150, Loss: 1.4336, Train Acc: 59.20%, Val Acc: 43.29%, Test Acc: 44.87%  
Epoch 112/150, Loss: 1.4265, Train Acc: 59.57%, Val Acc: 44.21%, Test Acc: 44.09%  
Epoch 113/150, Loss: 1.4208, Train Acc: 59.55%, Val Acc: 43.88%, Test Acc: 44.62%  
Epoch 114/150, Loss: 1.4070, Train Acc: 59.77%, Val Acc: 44.06%, Test Acc: 45.15%  
Epoch 115/150, Loss: 1.4049, Train Acc: 60.04%, Val Acc: 43.87%, Test Acc: 44.75%  
Epoch 116/150, Loss: 1.3989, Train Acc: 60.16%, Val Acc: 43.94%, Test Acc: 44.32%  
Epoch 117/150, Loss: 1.3989, Train Acc: 60.14%, Val Acc: 43.60%, Test Acc: 44.25%  
Epoch 118/150, Loss: 1.3952, Train Acc: 60.43%, Val Acc: 44.33%, Test Acc: 44.41%  
Epoch 119/150, Loss: 1.3937, Train Acc: 60.37%, Val Acc: 44.08%, Test Acc: 43.94%  
Checkpoint saved at epoch 120
Epoch 120/150, Loss: 1.3825, Train Acc: 60.53%, Val Acc: 44.45%, Test Acc: 44.45%  
Epoch 121/150, Loss: 1.3848, Train Acc: 60.38%, Val Acc: 44.34%, Test Acc: 45.66%  
Epoch 122/150, Loss: 1.3883, Train Acc: 60.27%, Val Acc: 44.06%, Test Acc: 44.85%  
Epoch 123/150, Loss: 1.3749, Train Acc: 60.61%, Val Acc: 44.10%, Test Acc: 44.16%  
Epoch 124/150, Loss: 1.3781, Train Acc: 60.99%, Val Acc: 44.11%, Test Acc: 44.79%  
Epoch 125/150, Loss: 1.3781, Train Acc: 60.83%, Val Acc: 44.75%, Test Acc: 44.58%  
Epoch 126/150, Loss: 1.3660, Train Acc: 61.24%, Val Acc: 43.69%, Test Acc: 44.92%  
Epoch 127/150, Loss: 1.3676, Train Acc: 60.99%, Val Acc: 43.98%, Test Acc: 44.89%  
Epoch 128/150, Loss: 1.3556, Train Acc: 61.48%, Val Acc: 44.62%, Test Acc: 44.72%  
Epoch 129/150, Loss: 1.3623, Train Acc: 60.97%, Val Acc: 44.77%, Test Acc: 44.50%  
Checkpoint saved at epoch 130
Epoch 130/150, Loss: 1.3579, Train Acc: 61.35%, Val Acc: 43.87%, Test Acc: 44.63%  
Epoch 131/150, Loss: 1.3663, Train Acc: 60.97%, Val Acc: 44.20%, Test Acc: 45.08%  
Epoch 132/150, Loss: 1.3574, Train Acc: 61.28%, Val Acc: 43.96%, Test Acc: 44.83%  
Epoch 133/150, Loss: 1.3585, Train Acc: 61.09%, Val Acc: 44.02%, Test Acc: 44.02%  
Epoch 134/150, Loss: 1.3421, Train Acc: 61.62%, Val Acc: 45.18%, Test Acc: 44.78%  
Epoch 135/150, Loss: 1.3433, Train Acc: 61.60%, Val Acc: 44.84%, Test Acc: 45.71%  
Epoch 136/150, Loss: 1.3406, Train Acc: 61.55%, Val Acc: 44.31%, Test Acc: 44.30%  
Epoch 137/150, Loss: 1.3442, Train Acc: 61.75%, Val Acc: 44.44%, Test Acc: 45.20%  
Epoch 138/150, Loss: 1.3480, Train Acc: 61.61%, Val Acc: 44.47%, Test Acc: 44.97%  
Epoch 139/150, Loss: 1.3412, Train Acc: 61.67%, Val Acc: 44.71%, Test Acc: 44.53%  
Checkpoint saved at epoch 140
Epoch 140/150, Loss: 1.3391, Train Acc: 61.80%, Val Acc: 44.96%, Test Acc: 44.67%  
Epoch 141/150, Loss: 1.3374, Train Acc: 61.77%, Val Acc: 44.50%, Test Acc: 44.93%  
Epoch 142/150, Loss: 1.3387, Train Acc: 61.84%, Val Acc: 44.22%, Test Acc: 44.89%  
Epoch 143/150, Loss: 1.3340, Train Acc: 61.83%, Val Acc: 44.22%, Test Acc: 45.39%  
Epoch 144/150, Loss: 1.3347, Train Acc: 61.73%, Val Acc: 44.67%, Test Acc: 45.16%  
Epoch 145/150, Loss: 1.3346, Train Acc: 61.83%, Val Acc: 45.12%, Test Acc: 44.59%  
Epoch 146/150, Loss: 1.3372, Train Acc: 61.88%, Val Acc: 44.73%, Test Acc: 45.32%  
Epoch 147/150, Loss: 1.3440, Train Acc: 61.42%, Val Acc: 44.53%, Test Acc: 44.96%  
Epoch 148/150, Loss: 1.3231, Train Acc: 62.10%, Val Acc: 44.48%, Test Acc: 45.51%  
Epoch 149/150, Loss: 1.3283, Train Acc: 61.73%, Val Acc: 44.75%, Test Acc: 45.04%  
Checkpoint saved at epoch 150
Epoch 150/150, Loss: 1.3342, Train Acc: 61.98%, Val Acc: 44.36%, Test Acc: 45.61%

#### Plots

![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-5/train_loss.png)
![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-5/val_loss.png)
![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-5/test_loss.png)
![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-5/train_accuracy.png)
![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-5/val_accuracy.png)
![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=1e-5/test_accuracy.png)

# Train with AdamW

| Epochs | batch_size | beta | weight_decay | learning_rate |
| ------ | ---------- | ---- | ------------ | ------------- |
| 150    | 128        | 0.9  | 5e-4         | 1e-3          |

#### Results log

Epoch 1/150, Loss: 4.1238, Train Acc: 6.47%, Val Acc: 10.54%, Test Acc: 9.74%  
Epoch 2/150, Loss: 3.6983, Train Acc: 12.94%, Val Acc: 15.73%, Test Acc: 15.36%  
Epoch 3/150, Loss: 3.3922, Train Acc: 18.11%, Val Acc: 18.99%, Test Acc: 19.29%  
Epoch 4/150, Loss: 3.2078, Train Acc: 21.49%, Val Acc: 22.41%, Test Acc: 22.10%  
Epoch 5/150, Loss: 3.0495, Train Acc: 24.39%, Val Acc: 25.00%, Test Acc: 25.48%  
Epoch 6/150, Loss: 2.9208, Train Acc: 26.95%, Val Acc: 27.06%, Test Acc: 27.43%  
Epoch 7/150, Loss: 2.8208, Train Acc: 28.84%, Val Acc: 27.29%, Test Acc: 27.98%  
Epoch 8/150, Loss: 2.7316, Train Acc: 30.73%, Val Acc: 29.73%, Test Acc: 29.79%  
Epoch 9/150, Loss: 2.6797, Train Acc: 31.59%, Val Acc: 30.68%, Test Acc: 30.89%  
Checkpoint saved at epoch 10
Epoch 10/150, Loss: 2.6169, Train Acc: 32.65%, Val Acc: 31.41%, Test Acc: 31.31%  
Epoch 11/150, Loss: 2.5751, Train Acc: 33.91%, Val Acc: 32.76%, Test Acc: 32.79%  
Epoch 12/150, Loss: 2.5148, Train Acc: 35.26%, Val Acc: 32.33%, Test Acc: 32.67%  
Epoch 13/150, Loss: 2.4833, Train Acc: 35.79%, Val Acc: 34.37%, Test Acc: 34.01%  
Epoch 14/150, Loss: 2.4491, Train Acc: 36.53%, Val Acc: 32.97%, Test Acc: 33.63%  
Epoch 15/150, Loss: 2.4207, Train Acc: 37.21%, Val Acc: 34.01%, Test Acc: 34.37%  
Epoch 16/150, Loss: 2.3940, Train Acc: 37.56%, Val Acc: 34.41%, Test Acc: 34.23%  
Epoch 17/150, Loss: 2.3622, Train Acc: 38.25%, Val Acc: 34.58%, Test Acc: 34.58%  
Epoch 18/150, Loss: 2.3247, Train Acc: 39.08%, Val Acc: 34.65%, Test Acc: 35.47%  
Epoch 19/150, Loss: 2.3199, Train Acc: 38.99%, Val Acc: 35.19%, Test Acc: 35.37%  
Checkpoint saved at epoch 20
Epoch 20/150, Loss: 2.2907, Train Acc: 39.63%, Val Acc: 35.09%, Test Acc: 35.82%  
Epoch 21/150, Loss: 2.2684, Train Acc: 40.11%, Val Acc: 36.59%, Test Acc: 37.00%  
Epoch 22/150, Loss: 2.2449, Train Acc: 40.72%, Val Acc: 35.96%, Test Acc: 36.53%  
Epoch 23/150, Loss: 2.2272, Train Acc: 41.22%, Val Acc: 36.52%, Test Acc: 37.23%  
Epoch 24/150, Loss: 2.1965, Train Acc: 41.61%, Val Acc: 37.37%, Test Acc: 37.35%  
Epoch 25/150, Loss: 2.1920, Train Acc: 41.94%, Val Acc: 36.77%, Test Acc: 37.28%  
Epoch 26/150, Loss: 2.1715, Train Acc: 42.13%, Val Acc: 36.39%, Test Acc: 36.51%  
Epoch 27/150, Loss: 2.1621, Train Acc: 42.56%, Val Acc: 37.47%, Test Acc: 37.26%  
Epoch 28/150, Loss: 2.1405, Train Acc: 43.05%, Val Acc: 38.08%, Test Acc: 37.89%  
Epoch 29/150, Loss: 2.1297, Train Acc: 43.27%, Val Acc: 37.55%, Test Acc: 37.59%  
Checkpoint saved at epoch 30
Epoch 30/150, Loss: 2.1086, Train Acc: 43.82%, Val Acc: 36.78%, Test Acc: 37.82%  
Epoch 31/150, Loss: 2.0974, Train Acc: 44.08%, Val Acc: 37.89%, Test Acc: 38.05%  
Epoch 32/150, Loss: 2.0807, Train Acc: 44.19%, Val Acc: 38.43%, Test Acc: 38.20%  
Epoch 33/150, Loss: 2.0713, Train Acc: 44.20%, Val Acc: 38.40%, Test Acc: 38.29%  
Epoch 34/150, Loss: 2.0602, Train Acc: 44.57%, Val Acc: 38.10%, Test Acc: 38.54%  
Epoch 35/150, Loss: 2.0444, Train Acc: 45.00%, Val Acc: 38.46%, Test Acc: 38.78%  
Epoch 36/150, Loss: 2.0339, Train Acc: 45.22%, Val Acc: 38.11%, Test Acc: 38.85%  
Epoch 37/150, Loss: 2.0264, Train Acc: 45.72%, Val Acc: 38.48%, Test Acc: 39.23%  
Epoch 38/150, Loss: 2.0049, Train Acc: 45.95%, Val Acc: 39.29%, Test Acc: 39.79%  
Epoch 39/150, Loss: 1.9903, Train Acc: 46.29%, Val Acc: 39.58%, Test Acc: 39.71%  
Checkpoint saved at epoch 40
Epoch 40/150, Loss: 1.9956, Train Acc: 46.37%, Val Acc: 38.54%, Test Acc: 38.67%  
Epoch 41/150, Loss: 1.9858, Train Acc: 46.38%, Val Acc: 39.30%, Test Acc: 40.41%  
Epoch 42/150, Loss: 1.9667, Train Acc: 46.93%, Val Acc: 38.85%, Test Acc: 39.06%  
Epoch 43/150, Loss: 1.9509, Train Acc: 47.19%, Val Acc: 39.50%, Test Acc: 39.13%  
Epoch 44/150, Loss: 1.9546, Train Acc: 47.12%, Val Acc: 39.26%, Test Acc: 39.85%  
Epoch 45/150, Loss: 1.9366, Train Acc: 47.55%, Val Acc: 39.34%, Test Acc: 40.38%  
Epoch 46/150, Loss: 1.9269, Train Acc: 47.79%, Val Acc: 40.04%, Test Acc: 39.57%  
Epoch 47/150, Loss: 1.9217, Train Acc: 47.74%, Val Acc: 39.88%, Test Acc: 40.55%  
Epoch 48/150, Loss: 1.8940, Train Acc: 48.47%, Val Acc: 40.30%, Test Acc: 40.36%  
Epoch 49/150, Loss: 1.8825, Train Acc: 48.78%, Val Acc: 40.08%, Test Acc: 40.75%  
Checkpoint saved at epoch 50
Epoch 50/150, Loss: 1.8871, Train Acc: 48.45%, Val Acc: 40.11%, Test Acc: 39.91%  
Epoch 51/150, Loss: 1.8722, Train Acc: 48.91%, Val Acc: 39.50%, Test Acc: 39.06%  
Epoch 52/150, Loss: 1.8701, Train Acc: 48.73%, Val Acc: 40.37%, Test Acc: 39.82%  
Epoch 53/150, Loss: 1.8595, Train Acc: 49.12%, Val Acc: 40.66%, Test Acc: 40.25%  
Epoch 54/150, Loss: 1.8431, Train Acc: 49.81%, Val Acc: 40.73%, Test Acc: 40.60%  
Epoch 55/150, Loss: 1.8439, Train Acc: 49.51%, Val Acc: 40.47%, Test Acc: 40.81%  
Epoch 56/150, Loss: 1.8306, Train Acc: 49.82%, Val Acc: 41.31%, Test Acc: 41.50%  
Epoch 57/150, Loss: 1.8223, Train Acc: 50.24%, Val Acc: 41.40%, Test Acc: 40.92%  
Epoch 58/150, Loss: 1.8105, Train Acc: 50.37%, Val Acc: 41.20%, Test Acc: 41.69%  
Epoch 59/150, Loss: 1.8127, Train Acc: 50.34%, Val Acc: 40.71%, Test Acc: 41.45%  
Checkpoint saved at epoch 60
Epoch 60/150, Loss: 1.7868, Train Acc: 50.59%, Val Acc: 41.29%, Test Acc: 41.26%  
Epoch 61/150, Loss: 1.8028, Train Acc: 50.48%, Val Acc: 39.97%, Test Acc: 40.77%  
Epoch 62/150, Loss: 1.7849, Train Acc: 51.02%, Val Acc: 40.49%, Test Acc: 41.31%  
Epoch 63/150, Loss: 1.7788, Train Acc: 51.03%, Val Acc: 40.99%, Test Acc: 41.05%  
Epoch 64/150, Loss: 1.7731, Train Acc: 51.38%, Val Acc: 41.23%, Test Acc: 41.52%  
Epoch 65/150, Loss: 1.7652, Train Acc: 51.42%, Val Acc: 42.09%, Test Acc: 41.94%  
Epoch 66/150, Loss: 1.7507, Train Acc: 51.64%, Val Acc: 40.80%, Test Acc: 41.93%  
Epoch 67/150, Loss: 1.7347, Train Acc: 52.23%, Val Acc: 41.47%, Test Acc: 41.27%  
Epoch 68/150, Loss: 1.7341, Train Acc: 52.17%, Val Acc: 41.58%, Test Acc: 41.52%  
Epoch 69/150, Loss: 1.7224, Train Acc: 52.27%, Val Acc: 41.19%, Test Acc: 42.08%  
Checkpoint saved at epoch 70
Epoch 70/150, Loss: 1.7215, Train Acc: 52.66%, Val Acc: 41.73%, Test Acc: 42.34%  
Epoch 71/150, Loss: 1.7153, Train Acc: 52.49%, Val Acc: 42.15%, Test Acc: 42.97%  
Epoch 72/150, Loss: 1.7060, Train Acc: 52.75%, Val Acc: 41.33%, Test Acc: 42.15%  
Epoch 73/150, Loss: 1.6901, Train Acc: 52.98%, Val Acc: 41.77%, Test Acc: 42.06%  
Epoch 74/150, Loss: 1.6954, Train Acc: 52.95%, Val Acc: 41.75%, Test Acc: 41.91%  
Epoch 75/150, Loss: 1.6744, Train Acc: 53.38%, Val Acc: 42.24%, Test Acc: 41.99%  
Epoch 76/150, Loss: 1.6797, Train Acc: 53.41%, Val Acc: 42.03%, Test Acc: 42.50%  
Epoch 77/150, Loss: 1.6582, Train Acc: 54.09%, Val Acc: 42.27%, Test Acc: 42.41%  
Epoch 78/150, Loss: 1.6573, Train Acc: 54.05%, Val Acc: 41.15%, Test Acc: 42.10%  
Epoch 79/150, Loss: 1.6433, Train Acc: 54.12%, Val Acc: 41.85%, Test Acc: 42.70%  
Checkpoint saved at epoch 80
Epoch 80/150, Loss: 1.6476, Train Acc: 54.06%, Val Acc: 42.06%, Test Acc: 43.08%  
Epoch 81/150, Loss: 1.6394, Train Acc: 54.26%, Val Acc: 42.04%, Test Acc: 42.56%  
Epoch 82/150, Loss: 1.6363, Train Acc: 54.56%, Val Acc: 42.35%, Test Acc: 42.46%  
Epoch 83/150, Loss: 1.6157, Train Acc: 54.79%, Val Acc: 42.28%, Test Acc: 42.45%  
Epoch 84/150, Loss: 1.6213, Train Acc: 54.71%, Val Acc: 42.63%, Test Acc: 43.05%  
Epoch 85/150, Loss: 1.6089, Train Acc: 54.91%, Val Acc: 42.72%, Test Acc: 42.70%  
Epoch 86/150, Loss: 1.6005, Train Acc: 55.21%, Val Acc: 42.39%, Test Acc: 43.09%  
Epoch 87/150, Loss: 1.5970, Train Acc: 55.38%, Val Acc: 42.55%, Test Acc: 43.88%  
Epoch 88/150, Loss: 1.5873, Train Acc: 55.76%, Val Acc: 42.29%, Test Acc: 43.57%  
Epoch 89/150, Loss: 1.5844, Train Acc: 55.77%, Val Acc: 42.83%, Test Acc: 43.13%  
Checkpoint saved at epoch 90
Epoch 90/150, Loss: 1.5718, Train Acc: 55.84%, Val Acc: 42.85%, Test Acc: 43.30%  
Epoch 91/150, Loss: 1.5830, Train Acc: 55.56%, Val Acc: 42.86%, Test Acc: 43.63%  
Epoch 92/150, Loss: 1.5682, Train Acc: 55.95%, Val Acc: 42.57%, Test Acc: 44.16%  
Epoch 93/150, Loss: 1.5625, Train Acc: 56.25%, Val Acc: 43.19%, Test Acc: 43.21%  
Epoch 94/150, Loss: 1.5592, Train Acc: 56.00%, Val Acc: 43.51%, Test Acc: 42.67%  
Epoch 95/150, Loss: 1.5486, Train Acc: 56.60%, Val Acc: 42.27%, Test Acc: 43.66%  
Epoch 96/150, Loss: 1.5356, Train Acc: 56.97%, Val Acc: 42.51%, Test Acc: 43.29%  
Epoch 97/150, Loss: 1.5374, Train Acc: 56.98%, Val Acc: 43.59%, Test Acc: 43.94%  
Epoch 98/150, Loss: 1.5330, Train Acc: 56.94%, Val Acc: 43.09%, Test Acc: 43.24%  
Epoch 99/150, Loss: 1.5197, Train Acc: 57.34%, Val Acc: 42.97%, Test Acc: 43.78%  
Checkpoint saved at epoch 100
Epoch 100/150, Loss: 1.5205, Train Acc: 57.37%, Val Acc: 43.16%, Test Acc: 43.32%  
Epoch 101/150, Loss: 1.5147, Train Acc: 57.48%, Val Acc: 42.73%, Test Acc: 43.55%  
Epoch 102/150, Loss: 1.5062, Train Acc: 57.48%, Val Acc: 43.17%, Test Acc: 43.58%  
Epoch 103/150, Loss: 1.5034, Train Acc: 57.48%, Val Acc: 43.70%, Test Acc: 43.82%  
Epoch 104/150, Loss: 1.4942, Train Acc: 57.87%, Val Acc: 43.64%, Test Acc: 44.03%  
Epoch 105/150, Loss: 1.4891, Train Acc: 58.21%, Val Acc: 43.85%, Test Acc: 43.61%  
Epoch 106/150, Loss: 1.4821, Train Acc: 58.26%, Val Acc: 43.35%, Test Acc: 43.62%  
Epoch 107/150, Loss: 1.4923, Train Acc: 57.87%, Val Acc: 43.25%, Test Acc: 43.77%  
Epoch 108/150, Loss: 1.4723, Train Acc: 58.41%, Val Acc: 43.41%, Test Acc: 44.49%  
Epoch 109/150, Loss: 1.4754, Train Acc: 58.48%, Val Acc: 43.35%, Test Acc: 44.02%  
Checkpoint saved at epoch 110
Epoch 110/150, Loss: 1.4590, Train Acc: 58.79%, Val Acc: 43.76%, Test Acc: 44.13%  
Epoch 111/150, Loss: 1.4655, Train Acc: 58.80%, Val Acc: 43.12%, Test Acc: 44.10%  
Epoch 112/150, Loss: 1.4567, Train Acc: 58.84%, Val Acc: 43.84%, Test Acc: 43.33%  
Epoch 113/150, Loss: 1.4560, Train Acc: 58.42%, Val Acc: 44.21%, Test Acc: 44.37%  
Epoch 114/150, Loss: 1.4516, Train Acc: 58.65%, Val Acc: 43.94%, Test Acc: 44.52%  
Epoch 115/150, Loss: 1.4424, Train Acc: 59.13%, Val Acc: 43.77%, Test Acc: 44.25%  
Epoch 116/150, Loss: 1.4418, Train Acc: 59.09%, Val Acc: 43.75%, Test Acc: 44.54%  
Epoch 117/150, Loss: 1.4408, Train Acc: 59.39%, Val Acc: 43.38%, Test Acc: 44.14%  
Epoch 118/150, Loss: 1.4282, Train Acc: 59.55%, Val Acc: 43.98%, Test Acc: 44.16%  
Epoch 119/150, Loss: 1.4269, Train Acc: 59.59%, Val Acc: 44.37%, Test Acc: 44.37%  
Checkpoint saved at epoch 120
Epoch 120/150, Loss: 1.4195, Train Acc: 59.69%, Val Acc: 43.59%, Test Acc: 44.30%  
Epoch 121/150, Loss: 1.4227, Train Acc: 59.70%, Val Acc: 44.00%, Test Acc: 44.21%  
Epoch 122/150, Loss: 1.4229, Train Acc: 59.67%, Val Acc: 43.94%, Test Acc: 44.26%  
Epoch 123/150, Loss: 1.4205, Train Acc: 59.91%, Val Acc: 44.16%, Test Acc: 44.22%  
Epoch 124/150, Loss: 1.4154, Train Acc: 59.76%, Val Acc: 44.15%, Test Acc: 44.41%  
Epoch 125/150, Loss: 1.4082, Train Acc: 59.93%, Val Acc: 43.63%, Test Acc: 44.14%  
Epoch 126/150, Loss: 1.4086, Train Acc: 60.24%, Val Acc: 44.39%, Test Acc: 44.39%  
Epoch 127/150, Loss: 1.4026, Train Acc: 60.06%, Val Acc: 44.39%, Test Acc: 44.97%  
Epoch 128/150, Loss: 1.4090, Train Acc: 59.94%, Val Acc: 43.66%, Test Acc: 44.34%  
Epoch 129/150, Loss: 1.4026, Train Acc: 60.17%, Val Acc: 45.16%, Test Acc: 44.44%  
Checkpoint saved at epoch 130
Epoch 130/150, Loss: 1.4066, Train Acc: 60.05%, Val Acc: 44.47%, Test Acc: 44.96%  
Epoch 131/150, Loss: 1.3963, Train Acc: 60.39%, Val Acc: 43.82%, Test Acc: 44.22%  
Epoch 132/150, Loss: 1.3923, Train Acc: 60.30%, Val Acc: 43.97%, Test Acc: 44.70%  
Epoch 133/150, Loss: 1.3992, Train Acc: 60.46%, Val Acc: 44.81%, Test Acc: 44.74%  
Epoch 134/150, Loss: 1.3908, Train Acc: 60.71%, Val Acc: 43.93%, Test Acc: 44.78%  
Epoch 135/150, Loss: 1.3835, Train Acc: 60.92%, Val Acc: 44.06%, Test Acc: 44.93%  
Epoch 136/150, Loss: 1.3854, Train Acc: 60.85%, Val Acc: 44.84%, Test Acc: 44.35%  
Epoch 137/150, Loss: 1.3889, Train Acc: 60.75%, Val Acc: 44.24%, Test Acc: 44.71%  
Epoch 138/150, Loss: 1.3879, Train Acc: 60.74%, Val Acc: 44.18%, Test Acc: 44.76%  
Epoch 139/150, Loss: 1.3819, Train Acc: 60.69%, Val Acc: 44.34%, Test Acc: 44.33%  
Checkpoint saved at epoch 140
Epoch 140/150, Loss: 1.3715, Train Acc: 60.91%, Val Acc: 44.37%, Test Acc: 45.00%  
Epoch 141/150, Loss: 1.3746, Train Acc: 61.12%, Val Acc: 44.10%, Test Acc: 44.86%  
Epoch 142/150, Loss: 1.3777, Train Acc: 60.69%, Val Acc: 44.69%, Test Acc: 44.83%  
Epoch 143/150, Loss: 1.3791, Train Acc: 60.58%, Val Acc: 44.36%, Test Acc: 45.30%  
Epoch 144/150, Loss: 1.3790, Train Acc: 60.65%, Val Acc: 44.97%, Test Acc: 45.51%  
Epoch 145/150, Loss: 1.3818, Train Acc: 60.93%, Val Acc: 44.84%, Test Acc: 45.14%  
Epoch 146/150, Loss: 1.3740, Train Acc: 61.00%, Val Acc: 44.47%, Test Acc: 44.28%  
Epoch 147/150, Loss: 1.3787, Train Acc: 60.91%, Val Acc: 44.91%, Test Acc: 45.18%  
Epoch 148/150, Loss: 1.3679, Train Acc: 61.02%, Val Acc: 44.65%, Test Acc: 45.31%  
Epoch 149/150, Loss: 1.3733, Train Acc: 61.06%, Val Acc: 44.32%, Test Acc: 45.09%  
Checkpoint saved at epoch 150
Epoch 150/150, Loss: 1.3731, Train Acc: 61.13%, Val Acc: 44.48%, Test Acc: 45.11%

#### Plots

![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=5e-4/train_loss.png)
![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=5e-4/val_loss.png)
![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=5e-4/test_loss.png)
![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=5e-4/train_accuracy.png)
![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=5e-4/val_accuracy.png)
![Plot](./Plot/e=150_bs=128_b=0.9_lr=1e-3_wd=5e-4/test_accuracy.png)

# Train with AdamW

| Epochs | batch_size | beta | weight_decay | learning_rate |
| ------ | ---------- | ---- | ------------ | ------------- |
| 150    | 64         | 0.9  | 1e-4         | 1e-3          |

#### Results log

Epoch 1/150, Loss: 4.0944, Train Acc: 6.83%, Val Acc: 11.34%, Test Acc: 11.01%  
Epoch 2/150, Loss: 3.6325, Train Acc: 13.88%, Val Acc: 16.34%, Test Acc: 16.77%  
Epoch 3/150, Loss: 3.3607, Train Acc: 18.71%, Val Acc: 20.38%, Test Acc: 19.91%  
Epoch 4/150, Loss: 3.1978, Train Acc: 21.41%, Val Acc: 22.52%, Test Acc: 22.22%  
Epoch 5/150, Loss: 3.0585, Train Acc: 23.98%, Val Acc: 24.63%, Test Acc: 24.20%  
Epoch 6/150, Loss: 2.9520, Train Acc: 25.93%, Val Acc: 25.77%, Test Acc: 26.37%  
Epoch 7/150, Loss: 2.8632, Train Acc: 27.77%, Val Acc: 27.27%, Test Acc: 26.77%  
Epoch 8/150, Loss: 2.8033, Train Acc: 29.08%, Val Acc: 28.18%, Test Acc: 28.04%  
Epoch 9/150, Loss: 2.7503, Train Acc: 30.18%, Val Acc: 29.68%, Test Acc: 29.52%  
Checkpoint saved at epoch 10
Epoch 10/150, Loss: 2.7021, Train Acc: 31.11%, Val Acc: 28.78%, Test Acc: 28.30%  
Epoch 11/150, Loss: 2.6595, Train Acc: 32.02%, Val Acc: 30.18%, Test Acc: 30.42%  
Epoch 12/150, Loss: 2.6319, Train Acc: 32.38%, Val Acc: 31.26%, Test Acc: 30.72%  
Epoch 13/150, Loss: 2.5984, Train Acc: 33.40%, Val Acc: 32.85%, Test Acc: 31.38%  
Epoch 14/150, Loss: 2.5732, Train Acc: 33.96%, Val Acc: 31.50%, Test Acc: 30.80%  
Epoch 15/150, Loss: 2.5417, Train Acc: 34.66%, Val Acc: 31.93%, Test Acc: 31.73%  
Epoch 16/150, Loss: 2.5222, Train Acc: 35.03%, Val Acc: 32.29%, Test Acc: 31.75%  
Epoch 17/150, Loss: 2.4915, Train Acc: 35.50%, Val Acc: 32.76%, Test Acc: 32.64%  
Epoch 18/150, Loss: 2.4719, Train Acc: 35.76%, Val Acc: 32.65%, Test Acc: 32.50%  
Epoch 19/150, Loss: 2.4519, Train Acc: 36.41%, Val Acc: 33.09%, Test Acc: 32.96%  
Checkpoint saved at epoch 20
Epoch 20/150, Loss: 2.4419, Train Acc: 36.62%, Val Acc: 32.81%, Test Acc: 32.70%  
Epoch 21/150, Loss: 2.4140, Train Acc: 37.22%, Val Acc: 33.62%, Test Acc: 33.54%  
Epoch 22/150, Loss: 2.3999, Train Acc: 37.16%, Val Acc: 34.45%, Test Acc: 33.98%  
Epoch 23/150, Loss: 2.3822, Train Acc: 37.75%, Val Acc: 33.77%, Test Acc: 33.80%  
Epoch 24/150, Loss: 2.3732, Train Acc: 38.10%, Val Acc: 34.45%, Test Acc: 34.12%  
Epoch 25/150, Loss: 2.3659, Train Acc: 38.28%, Val Acc: 33.85%, Test Acc: 33.61%  
Epoch 26/150, Loss: 2.3442, Train Acc: 38.63%, Val Acc: 34.90%, Test Acc: 35.16%  
Epoch 27/150, Loss: 2.3256, Train Acc: 38.97%, Val Acc: 34.41%, Test Acc: 34.81%  
Epoch 28/150, Loss: 2.3138, Train Acc: 39.31%, Val Acc: 35.12%, Test Acc: 34.47%  
Epoch 29/150, Loss: 2.3047, Train Acc: 39.28%, Val Acc: 35.08%, Test Acc: 35.22%  
Checkpoint saved at epoch 30
Epoch 30/150, Loss: 2.2878, Train Acc: 39.92%, Val Acc: 35.16%, Test Acc: 34.90%  
Epoch 31/150, Loss: 2.3001, Train Acc: 39.44%, Val Acc: 35.30%, Test Acc: 36.35%  
Epoch 32/150, Loss: 2.2608, Train Acc: 40.41%, Val Acc: 34.33%, Test Acc: 34.43%  
Epoch 33/150, Loss: 2.2502, Train Acc: 40.37%, Val Acc: 34.61%, Test Acc: 34.98%  
Epoch 34/150, Loss: 2.2410, Train Acc: 40.59%, Val Acc: 35.58%, Test Acc: 35.59%  
Epoch 35/150, Loss: 2.2341, Train Acc: 40.79%, Val Acc: 35.93%, Test Acc: 36.68%  
Epoch 36/150, Loss: 2.2235, Train Acc: 41.27%, Val Acc: 35.72%, Test Acc: 35.46%  
Epoch 37/150, Loss: 2.2120, Train Acc: 41.03%, Val Acc: 36.18%, Test Acc: 35.99%  
Epoch 38/150, Loss: 2.2089, Train Acc: 41.38%, Val Acc: 36.06%, Test Acc: 36.75%  
Epoch 39/150, Loss: 2.1842, Train Acc: 41.91%, Val Acc: 35.91%, Test Acc: 36.03%  
Checkpoint saved at epoch 40
Epoch 40/150, Loss: 2.1875, Train Acc: 42.04%, Val Acc: 36.38%, Test Acc: 37.19%  
Epoch 41/150, Loss: 2.1773, Train Acc: 42.35%, Val Acc: 35.43%, Test Acc: 37.07%  
Epoch 42/150, Loss: 2.1724, Train Acc: 42.30%, Val Acc: 36.45%, Test Acc: 37.09%  
Epoch 43/150, Loss: 2.1574, Train Acc: 42.49%, Val Acc: 35.96%, Test Acc: 36.50%  
Epoch 44/150, Loss: 2.1473, Train Acc: 43.16%, Val Acc: 37.29%, Test Acc: 37.22%  
Epoch 45/150, Loss: 2.1416, Train Acc: 42.99%, Val Acc: 36.74%, Test Acc: 36.74%  
Epoch 46/150, Loss: 2.1275, Train Acc: 43.65%, Val Acc: 37.23%, Test Acc: 37.38%  
Epoch 47/150, Loss: 2.1186, Train Acc: 43.36%, Val Acc: 37.95%, Test Acc: 37.85%  
Epoch 48/150, Loss: 2.1008, Train Acc: 43.87%, Val Acc: 37.92%, Test Acc: 36.94%  
Epoch 49/150, Loss: 2.0917, Train Acc: 44.34%, Val Acc: 36.98%, Test Acc: 36.96%  
Checkpoint saved at epoch 50
Epoch 50/150, Loss: 2.1004, Train Acc: 43.94%, Val Acc: 37.46%, Test Acc: 37.66%  
Epoch 51/150, Loss: 2.0846, Train Acc: 44.06%, Val Acc: 37.23%, Test Acc: 37.86%  
Epoch 52/150, Loss: 2.0700, Train Acc: 44.32%, Val Acc: 37.32%, Test Acc: 37.80%  
Epoch 53/150, Loss: 2.0689, Train Acc: 44.51%, Val Acc: 37.20%, Test Acc: 37.80%  
Epoch 54/150, Loss: 2.0598, Train Acc: 44.82%, Val Acc: 37.50%, Test Acc: 37.71%  
Epoch 55/150, Loss: 2.0374, Train Acc: 45.08%, Val Acc: 38.05%, Test Acc: 38.80%  
Epoch 56/150, Loss: 2.0474, Train Acc: 44.92%, Val Acc: 39.11%, Test Acc: 39.00%  
Epoch 57/150, Loss: 2.0262, Train Acc: 45.38%, Val Acc: 38.36%, Test Acc: 38.00%  
Epoch 58/150, Loss: 2.0228, Train Acc: 45.55%, Val Acc: 38.07%, Test Acc: 38.01%  
Epoch 59/150, Loss: 2.0181, Train Acc: 45.61%, Val Acc: 38.39%, Test Acc: 39.34%  
Checkpoint saved at epoch 60
Epoch 60/150, Loss: 2.0036, Train Acc: 45.65%, Val Acc: 38.46%, Test Acc: 38.95%  
Epoch 61/150, Loss: 2.0055, Train Acc: 46.09%, Val Acc: 38.44%, Test Acc: 38.74%  
Epoch 62/150, Loss: 1.9889, Train Acc: 46.16%, Val Acc: 39.36%, Test Acc: 38.66%  
Epoch 63/150, Loss: 1.9830, Train Acc: 46.50%, Val Acc: 38.96%, Test Acc: 38.74%  
Epoch 64/150, Loss: 1.9760, Train Acc: 46.42%, Val Acc: 38.69%, Test Acc: 37.91%  
Epoch 65/150, Loss: 1.9633, Train Acc: 47.00%, Val Acc: 38.58%, Test Acc: 38.85%  
Epoch 66/150, Loss: 1.9580, Train Acc: 46.96%, Val Acc: 38.12%, Test Acc: 38.69%  
Epoch 67/150, Loss: 1.9433, Train Acc: 47.30%, Val Acc: 39.40%, Test Acc: 39.79%  
Epoch 68/150, Loss: 1.9550, Train Acc: 47.15%, Val Acc: 39.89%, Test Acc: 39.28%  
Epoch 69/150, Loss: 1.9304, Train Acc: 47.59%, Val Acc: 39.30%, Test Acc: 38.84%  
Checkpoint saved at epoch 70
Epoch 70/150, Loss: 1.9295, Train Acc: 47.75%, Val Acc: 39.75%, Test Acc: 39.30%  
Epoch 71/150, Loss: 1.9188, Train Acc: 47.77%, Val Acc: 39.55%, Test Acc: 39.52%  
Epoch 72/150, Loss: 1.9088, Train Acc: 48.23%, Val Acc: 39.31%, Test Acc: 39.67%  
Epoch 73/150, Loss: 1.9062, Train Acc: 47.84%, Val Acc: 40.33%, Test Acc: 39.81%  
Epoch 74/150, Loss: 1.8804, Train Acc: 48.52%, Val Acc: 40.04%, Test Acc: 40.34%  
Epoch 75/150, Loss: 1.8766, Train Acc: 48.70%, Val Acc: 39.71%, Test Acc: 39.62%  
Epoch 76/150, Loss: 1.8664, Train Acc: 49.09%, Val Acc: 39.78%, Test Acc: 39.79%  
Epoch 77/150, Loss: 1.8679, Train Acc: 48.78%, Val Acc: 39.70%, Test Acc: 39.97%  
Epoch 78/150, Loss: 1.8637, Train Acc: 49.17%, Val Acc: 40.13%, Test Acc: 40.17%  
Epoch 79/150, Loss: 1.8565, Train Acc: 49.34%, Val Acc: 39.81%, Test Acc: 39.65%  
Checkpoint saved at epoch 80
Epoch 80/150, Loss: 1.8429, Train Acc: 49.60%, Val Acc: 39.56%, Test Acc: 39.39%  
Epoch 81/150, Loss: 1.8339, Train Acc: 49.68%, Val Acc: 40.16%, Test Acc: 39.78%  
Epoch 82/150, Loss: 1.8208, Train Acc: 49.96%, Val Acc: 40.36%, Test Acc: 40.56%  
Epoch 83/150, Loss: 1.8139, Train Acc: 50.27%, Val Acc: 40.49%, Test Acc: 39.26%  
Epoch 84/150, Loss: 1.8098, Train Acc: 50.47%, Val Acc: 40.27%, Test Acc: 40.55%  
Epoch 85/150, Loss: 1.8081, Train Acc: 50.33%, Val Acc: 40.16%, Test Acc: 40.26%  
Epoch 86/150, Loss: 1.7979, Train Acc: 50.62%, Val Acc: 40.47%, Test Acc: 40.39%  
Epoch 87/150, Loss: 1.7856, Train Acc: 51.20%, Val Acc: 40.30%, Test Acc: 41.45%  
Epoch 88/150, Loss: 1.7783, Train Acc: 51.02%, Val Acc: 40.70%, Test Acc: 40.98%  
Epoch 89/150, Loss: 1.7833, Train Acc: 51.00%, Val Acc: 40.84%, Test Acc: 41.48%  
Checkpoint saved at epoch 90
Epoch 90/150, Loss: 1.7711, Train Acc: 51.20%, Val Acc: 40.79%, Test Acc: 40.88%  
Epoch 91/150, Loss: 1.7638, Train Acc: 51.43%, Val Acc: 40.40%, Test Acc: 41.28%  
Epoch 92/150, Loss: 1.7478, Train Acc: 51.60%, Val Acc: 39.86%, Test Acc: 40.80%  
Epoch 93/150, Loss: 1.7520, Train Acc: 51.59%, Val Acc: 40.57%, Test Acc: 40.51%  
Epoch 94/150, Loss: 1.7308, Train Acc: 52.18%, Val Acc: 40.81%, Test Acc: 41.24%  
Epoch 95/150, Loss: 1.7364, Train Acc: 51.93%, Val Acc: 41.02%, Test Acc: 40.99%  
Epoch 96/150, Loss: 1.7240, Train Acc: 52.23%, Val Acc: 41.13%, Test Acc: 41.62%  
Epoch 97/150, Loss: 1.7241, Train Acc: 52.42%, Val Acc: 41.51%, Test Acc: 41.49%  
Epoch 98/150, Loss: 1.7194, Train Acc: 52.54%, Val Acc: 41.59%, Test Acc: 40.99%  
Epoch 99/150, Loss: 1.6983, Train Acc: 52.83%, Val Acc: 41.28%, Test Acc: 41.90%  
Checkpoint saved at epoch 100
Epoch 100/150, Loss: 1.7010, Train Acc: 53.22%, Val Acc: 41.56%, Test Acc: 41.89%  
Epoch 101/150, Loss: 1.7004, Train Acc: 52.74%, Val Acc: 41.66%, Test Acc: 42.17%  
Epoch 102/150, Loss: 1.6885, Train Acc: 53.12%, Val Acc: 41.52%, Test Acc: 41.79%  
Epoch 103/150, Loss: 1.6881, Train Acc: 53.17%, Val Acc: 41.28%, Test Acc: 41.76%  
Epoch 104/150, Loss: 1.6754, Train Acc: 53.61%, Val Acc: 41.61%, Test Acc: 42.23%  
Epoch 105/150, Loss: 1.6674, Train Acc: 53.73%, Val Acc: 41.98%, Test Acc: 41.66%  
Epoch 106/150, Loss: 1.6687, Train Acc: 53.69%, Val Acc: 41.62%, Test Acc: 41.51%  
Epoch 107/150, Loss: 1.6646, Train Acc: 53.84%, Val Acc: 41.44%, Test Acc: 41.80%  
Epoch 108/150, Loss: 1.6504, Train Acc: 54.08%, Val Acc: 41.84%, Test Acc: 42.28%  
Epoch 109/150, Loss: 1.6472, Train Acc: 54.38%, Val Acc: 42.12%, Test Acc: 42.05%  
Checkpoint saved at epoch 110
Epoch 110/150, Loss: 1.6414, Train Acc: 54.39%, Val Acc: 42.47%, Test Acc: 42.17%  
Epoch 111/150, Loss: 1.6358, Train Acc: 54.62%, Val Acc: 41.72%, Test Acc: 41.72%  
Epoch 112/150, Loss: 1.6331, Train Acc: 54.49%, Val Acc: 41.87%, Test Acc: 42.67%  
Epoch 113/150, Loss: 1.6340, Train Acc: 54.48%, Val Acc: 42.39%, Test Acc: 42.04%  
Epoch 114/150, Loss: 1.6223, Train Acc: 54.80%, Val Acc: 42.73%, Test Acc: 42.35%  
Epoch 115/150, Loss: 1.6305, Train Acc: 54.64%, Val Acc: 42.57%, Test Acc: 41.68%  
Epoch 116/150, Loss: 1.6160, Train Acc: 54.77%, Val Acc: 42.66%, Test Acc: 41.98%  
Epoch 117/150, Loss: 1.6060, Train Acc: 55.12%, Val Acc: 41.33%, Test Acc: 42.33%  
Epoch 118/150, Loss: 1.6114, Train Acc: 55.02%, Val Acc: 42.55%, Test Acc: 42.28%  
Epoch 119/150, Loss: 1.5996, Train Acc: 55.31%, Val Acc: 41.82%, Test Acc: 42.45%  
Checkpoint saved at epoch 120
Epoch 120/150, Loss: 1.6049, Train Acc: 55.12%, Val Acc: 42.36%, Test Acc: 42.74%  
Epoch 121/150, Loss: 1.5987, Train Acc: 55.67%, Val Acc: 42.34%, Test Acc: 41.92%  
Epoch 122/150, Loss: 1.5952, Train Acc: 55.62%, Val Acc: 42.38%, Test Acc: 42.03%  
Epoch 123/150, Loss: 1.5866, Train Acc: 55.46%, Val Acc: 42.51%, Test Acc: 42.21%  
Epoch 124/150, Loss: 1.5877, Train Acc: 55.60%, Val Acc: 42.03%, Test Acc: 42.60%  
Epoch 125/150, Loss: 1.5727, Train Acc: 56.28%, Val Acc: 42.35%, Test Acc: 42.49%  
Epoch 126/150, Loss: 1.5719, Train Acc: 56.21%, Val Acc: 42.60%, Test Acc: 43.10%  
Epoch 127/150, Loss: 1.5729, Train Acc: 55.94%, Val Acc: 43.06%, Test Acc: 42.72%  
Epoch 128/150, Loss: 1.5637, Train Acc: 56.27%, Val Acc: 42.42%, Test Acc: 43.00%  
Epoch 129/150, Loss: 1.5670, Train Acc: 56.20%, Val Acc: 43.06%, Test Acc: 43.21%  
Checkpoint saved at epoch 130
Epoch 130/150, Loss: 1.5619, Train Acc: 56.10%, Val Acc: 42.02%, Test Acc: 42.91%  
Epoch 131/150, Loss: 1.5661, Train Acc: 56.31%, Val Acc: 42.03%, Test Acc: 42.62%  
Epoch 132/150, Loss: 1.5578, Train Acc: 56.37%, Val Acc: 42.38%, Test Acc: 42.13%  
Epoch 133/150, Loss: 1.5551, Train Acc: 56.60%, Val Acc: 42.58%, Test Acc: 43.42%  
Epoch 134/150, Loss: 1.5544, Train Acc: 56.44%, Val Acc: 42.49%, Test Acc: 42.70%  
Epoch 135/150, Loss: 1.5539, Train Acc: 56.31%, Val Acc: 42.43%, Test Acc: 42.50%  
Epoch 136/150, Loss: 1.5507, Train Acc: 56.43%, Val Acc: 43.12%, Test Acc: 42.34%  
Epoch 137/150, Loss: 1.5466, Train Acc: 56.66%, Val Acc: 43.10%, Test Acc: 43.13%  
Epoch 138/150, Loss: 1.5458, Train Acc: 56.49%, Val Acc: 43.59%, Test Acc: 42.51%  
Epoch 139/150, Loss: 1.5395, Train Acc: 56.64%, Val Acc: 42.73%, Test Acc: 43.11%  
Checkpoint saved at epoch 140
Epoch 140/150, Loss: 1.5421, Train Acc: 56.73%, Val Acc: 43.29%, Test Acc: 42.76%  
Epoch 141/150, Loss: 1.5505, Train Acc: 56.57%, Val Acc: 42.36%, Test Acc: 42.66%  
Epoch 142/150, Loss: 1.5400, Train Acc: 56.83%, Val Acc: 42.81%, Test Acc: 42.91%  
Epoch 143/150, Loss: 1.5408, Train Acc: 57.04%, Val Acc: 43.01%, Test Acc: 42.70%  
Epoch 144/150, Loss: 1.5426, Train Acc: 56.85%, Val Acc: 42.65%, Test Acc: 42.74%  
Epoch 145/150, Loss: 1.5307, Train Acc: 57.22%, Val Acc: 43.27%, Test Acc: 43.17%  
Epoch 146/150, Loss: 1.5445, Train Acc: 56.40%, Val Acc: 42.87%, Test Acc: 42.86%  
Epoch 147/150, Loss: 1.5477, Train Acc: 56.69%, Val Acc: 42.48%, Test Acc: 43.04%  
Epoch 148/150, Loss: 1.5344, Train Acc: 56.76%, Val Acc: 43.02%, Test Acc: 42.97%  
Epoch 149/150, Loss: 1.5318, Train Acc: 56.75%, Val Acc: 43.77%, Test Acc: 42.84%  
Checkpoint saved at epoch 150
Epoch 150/150, Loss: 1.5347, Train Acc: 57.06%, Val Acc: 42.45%, Test Acc: 42.43%

#### Plots

![Plot](./Plot/e=150_bs=64_b=0.9_lr=1e-3_wd=1e-4/train_loss.png)
![Plot](./Plot/e=150_bs=64_b=0.9_lr=1e-3_wd=1e-4/val_loss.png)
![Plot](./Plot/e=150_bs=64_b=0.9_lr=1e-3_wd=1e-4/test_loss.png)
![Plot](./Plot/e=150_bs=64_b=0.9_lr=1e-3_wd=1e-4/train_accuracy.png)
![Plot](./Plot/e=150_bs=64_b=0.9_lr=1e-3_wd=1e-4/val_accuracy.png)
![Plot](./Plot/e=150_bs=64_b=0.9_lr=1e-3_wd=1e-4/test_accuracy.png)

# Train with AdamW

| Epochs | batch_size | beta | weight_decay | learning_rate |
| ------ | ---------- | ---- | ------------ | ------------- |
| 100    | 128        | 0.95 | 1e-4         | 1e-3          |

#### Results log

#### Plots

![Plot](./Plot/e=100_bs=128_b=0.95_lr=1e-3_wd=1e-4/train_loss.png)
![Plot](./Plot/e=100_bs=128_b=0.95_lr=1e-3_wd=1e-4/val_loss.png)
![Plot](./Plot/e=100_bs=128_b=0.95_lr=1e-3_wd=1e-4/test_loss.png)
![Plot](./Plot/e=100_bs=128_b=0.95_lr=1e-3_wd=1e-4/train_accuracy.png)
![Plot](./Plot/e=100_bs=128_b=0.95_lr=1e-3_wd=1e-4/val_accuracy.png)
![Plot](./Plot/e=100_bs=128_b=0.95_lr=1e-3_wd=1e-4/test_accuracy.png)

# Train with AdamW

| Epochs | batch_size | beta | weight_decay | learning_rate |
| ------ | ---------- | ---- | ------------ | ------------- |
| 150    |            |      |              |               |

#### Results log

#### Plots

![Plot](./Plot/insert_folder_here/train_loss.png)
![Plot](./Plot/insert_folder_here/val_loss.png)
![Plot](./Plot/insert_folder_here/test_loss.png)
![Plot](./Plot/insert_folder_here/train_accuracy.png)
![Plot](./Plot/insert_folder_here/val_accuracy.png)
![Plot](./Plot/insert_folder_here/test_accuracy.png)
