- From paper 18 (Large_Batch_Optimization_for_Learning_Training) there were two suggested way of tuning the learning rate for thr large minibatches.
- One way is by order square root of the minibatch size.
    - new_learning_rate = learning_rate * (largerbatch_size / base_batch_size)**2
- Second way is linear scaling of the learning rate with minibatch size. Which is simply multiple the learning rate by k, where k is size multipled to the base_batch.
    - new_learning_rate = learning_rate * (largerbatch_size / base_batch_size)

- About the tuning of learning rate is also mentioned in paper "Goyal et al. (2017)". 


## Results

| Epochs | batch_size | momentum | weight_decay | learning_rate | droupout1 | dropout2 |
|---|---|---|---|---|---|---|
|150 | 256 | 0.9 | 5e-4 | 0.04 | 0.3 | 0.3 |

- this results are by using the linear scaling of the learnign rate.

--- Train with SGDM ---

Epoch 1/150, Loss: 4.5007, Train Acc: 2.42%, Val Acc: 5.31%, Test Acc: 5.13%

Checkpoint saved at epoch 2: ./checkpoint_epoch_2.pth

Epoch 2/150, Loss: 4.1133, Train Acc: 6.72%, Val Acc: 9.00%, Test Acc: 8.63%

Epoch 3/150, Loss: 3.9118, Train Acc: 9.19%, Val Acc: 12.28%, Test Acc: 11.65%

Checkpoint saved at epoch 4: ./checkpoint_epoch_4.pth

Epoch 4/150, Loss: 3.7350, Train Acc: 12.14%, Val Acc: 15.87%, Test Acc: 15.44%

Epoch 5/150, Loss: 3.5919, Train Acc: 14.74%, Val Acc: 18.26%, Test Acc: 17.80%

Checkpoint saved at epoch 6: ./checkpoint_epoch_6.pth

Epoch 6/150, Loss: 3.4548, Train Acc: 17.00%, Val Acc: 19.47%, Test Acc: 19.75%

Epoch 7/150, Loss: 3.3516, Train Acc: 18.86%, Val Acc: 23.01%, Test Acc: 22.81%

Checkpoint saved at epoch 8: ./checkpoint_epoch_8.pth

Epoch 8/150, Loss: 3.2351, Train Acc: 20.83%, Val Acc: 24.48%, Test Acc: 24.63%

Epoch 9/150, Loss: 3.1750, Train Acc: 21.98%, Val Acc: 25.47%, Test Acc: 25.30%

Checkpoint saved at epoch 10: ./checkpoint_epoch_10.pth

Epoch 10/150, Loss: 3.0866, Train Acc: 23.85%, Val Acc: 27.78%, Test Acc: 27.18%

Epoch 11/150, Loss: 3.0382, Train Acc: 24.71%, Val Acc: 28.30%, Test Acc: 28.25%

Checkpoint saved at epoch 12: ./checkpoint_epoch_12.pth

Epoch 12/150, Loss: 2.9904, Train Acc: 25.44%, Val Acc: 28.69%, Test Acc: 29.38%

Epoch 13/150, Loss: 2.9448, Train Acc: 26.37%, Val Acc: 28.55%, Test Acc: 28.37%

Checkpoint saved at epoch 14: ./checkpoint_epoch_14.pth

Epoch 14/150, Loss: 2.8946, Train Acc: 27.37%, Val Acc: 30.20%, Test Acc: 30.08%

Epoch 15/150, Loss: 2.8541, Train Acc: 28.18%, Val Acc: 30.76%, Test Acc: 30.80%

Checkpoint saved at epoch 16: ./checkpoint_epoch_16.pth

Epoch 16/150, Loss: 2.8325, Train Acc: 28.73%, Val Acc: 30.93%, Test Acc: 30.92%

Epoch 17/150, Loss: 2.7927, Train Acc: 29.43%, Val Acc: 32.33%, Test Acc: 32.52%

Checkpoint saved at epoch 18: ./checkpoint_epoch_18.pth

Epoch 18/150, Loss: 2.7487, Train Acc: 30.50%, Val Acc: 33.41%, Test Acc: 33.56%

Epoch 19/150, Loss: 2.7241, Train Acc: 31.01%, Val Acc: 34.28%, Test Acc: 33.39%

Checkpoint saved at epoch 20: ./checkpoint_epoch_20.pth

Epoch 20/150, Loss: 2.7123, Train Acc: 30.93%, Val Acc: 31.64%, Test Acc: 31.67%

Epoch 21/150, Loss: 2.6783, Train Acc: 31.89%, Val Acc: 33.74%, Test Acc: 34.20%

Checkpoint saved at epoch 22: ./checkpoint_epoch_22.pth

Epoch 22/150, Loss: 2.6549, Train Acc: 32.40%, Val Acc: 34.86%, Test Acc: 35.11%

Epoch 23/150, Loss: 2.6076, Train Acc: 32.99%, Val Acc: 35.96%, Test Acc: 35.97%

Checkpoint saved at epoch 24: ./checkpoint_epoch_24.pth

Epoch 24/150, Loss: 2.6059, Train Acc: 33.51%, Val Acc: 35.09%, Test Acc: 35.04%

Epoch 25/150, Loss: 2.5885, Train Acc: 33.86%, Val Acc: 36.05%, Test Acc: 36.53%

Checkpoint saved at epoch 26: ./checkpoint_epoch_26.pth

Epoch 26/150, Loss: 2.5718, Train Acc: 34.33%, Val Acc: 35.89%, Test Acc: 36.27%

Epoch 27/150, Loss: 2.5456, Train Acc: 34.61%, Val Acc: 35.61%, Test Acc: 35.66%

Checkpoint saved at epoch 28: ./checkpoint_epoch_28.pth

Epoch 28/150, Loss: 2.5324, Train Acc: 34.98%, Val Acc: 36.47%, Test Acc: 36.57%

Epoch 29/150, Loss: 2.5008, Train Acc: 35.59%, Val Acc: 36.91%, Test Acc: 37.53%

Checkpoint saved at epoch 30: ./checkpoint_epoch_30.pth

Epoch 30/150, Loss: 2.4950, Train Acc: 35.59%, Val Acc: 37.84%, Test Acc: 37.46%

Epoch 31/150, Loss: 2.4777, Train Acc: 35.63%, Val Acc: 38.30%, Test Acc: 37.73%

Checkpoint saved at epoch 32: ./checkpoint_epoch_32.pth

Epoch 32/150, Loss: 2.4801, Train Acc: 35.77%, Val Acc: 37.64%, Test Acc: 38.30%

Epoch 33/150, Loss: 2.4534, Train Acc: 36.79%, Val Acc: 39.29%, Test Acc: 38.30%

Checkpoint saved at epoch 34: ./checkpoint_epoch_34.pth

Epoch 34/150, Loss: 2.4341, Train Acc: 37.19%, Val Acc: 37.74%, Test Acc: 37.86%

Epoch 35/150, Loss: 2.4398, Train Acc: 36.99%, Val Acc: 40.19%, Test Acc: 39.99%

Checkpoint saved at epoch 36: ./checkpoint_epoch_36.pth

Epoch 36/150, Loss: 2.4234, Train Acc: 37.13%, Val Acc: 38.58%, Test Acc: 39.22%

Epoch 37/150, Loss: 2.3937, Train Acc: 37.52%, Val Acc: 39.30%, Test Acc: 39.09%

Checkpoint saved at epoch 38: ./checkpoint_epoch_38.pth

Epoch 38/150, Loss: 2.3927, Train Acc: 38.01%, Val Acc: 40.77%, Test Acc: 40.98%

Epoch 39/150, Loss: 2.3757, Train Acc: 38.08%, Val Acc: 39.86%, Test Acc: 40.76%

Checkpoint saved at epoch 40: ./checkpoint_epoch_40.pth

Epoch 40/150, Loss: 2.3517, Train Acc: 38.79%, Val Acc: 39.43%, Test Acc: 39.14%

Epoch 41/150, Loss: 2.3576, Train Acc: 38.34%, Val Acc: 39.27%, Test Acc: 39.75%

Checkpoint saved at epoch 42: ./checkpoint_epoch_42.pth

Epoch 42/150, Loss: 2.3441, Train Acc: 38.87%, Val Acc: 37.74%, Test Acc: 37.75%

Epoch 43/150, Loss: 2.3184, Train Acc: 39.25%, Val Acc: 39.51%, Test Acc: 40.04%

Checkpoint saved at epoch 44: ./checkpoint_epoch_44.pth

Epoch 44/150, Loss: 2.3231, Train Acc: 39.24%, Val Acc: 40.11%, Test Acc: 40.97%

Epoch 45/150, Loss: 2.2989, Train Acc: 39.75%, Val Acc: 39.92%, Test Acc: 40.42%

Checkpoint saved at epoch 46: ./checkpoint_epoch_46.pth

Epoch 46/150, Loss: 2.3069, Train Acc: 39.73%, Val Acc: 41.45%, Test Acc: 41.90%

Epoch 47/150, Loss: 2.2735, Train Acc: 40.52%, Val Acc: 41.72%, Test Acc: 41.64%

Checkpoint saved at epoch 48: ./checkpoint_epoch_48.pth

Epoch 48/150, Loss: 2.2824, Train Acc: 40.38%, Val Acc: 40.92%, Test Acc: 41.45%

Epoch 49/150, Loss: 2.2652, Train Acc: 40.40%, Val Acc: 41.53%, Test Acc: 42.13%

Checkpoint saved at epoch 50: ./checkpoint_epoch_50.pth

Epoch 50/150, Loss: 2.2514, Train Acc: 41.01%, Val Acc: 42.33%, Test Acc: 42.86%

Epoch 51/150, Loss: 2.2535, Train Acc: 40.56%, Val Acc: 42.60%, Test Acc: 42.05%

Checkpoint saved at epoch 52: ./checkpoint_epoch_52.pth

Epoch 52/150, Loss: 2.2293, Train Acc: 41.29%, Val Acc: 42.65%, Test Acc: 42.57%

Epoch 53/150, Loss: 2.2124, Train Acc: 41.60%, Val Acc: 41.76%, Test Acc: 42.22%

Checkpoint saved at epoch 54: ./checkpoint_epoch_54.pth

Epoch 54/150, Loss: 2.2263, Train Acc: 41.12%, Val Acc: 41.94%, Test Acc: 42.15%

Epoch 55/150, Loss: 2.2238, Train Acc: 41.30%, Val Acc: 42.75%, Test Acc: 42.89%

Checkpoint saved at epoch 56: ./checkpoint_epoch_56.pth

Epoch 56/150, Loss: 2.2011, Train Acc: 42.03%, Val Acc: 43.84%, Test Acc: 43.63%

Epoch 57/150, Loss: 2.1847, Train Acc: 42.35%, Val Acc: 43.39%, Test Acc: 43.58%

Checkpoint saved at epoch 58: ./checkpoint_epoch_58.pth

Epoch 58/150, Loss: 2.1686, Train Acc: 42.42%, Val Acc: 43.20%, Test Acc: 43.72%

Epoch 59/150, Loss: 2.1690, Train Acc: 42.37%, Val Acc: 43.79%, Test Acc: 44.11%

Checkpoint saved at epoch 60: ./checkpoint_epoch_60.pth

Epoch 60/150, Loss: 2.1621, Train Acc: 42.67%, Val Acc: 43.03%, Test Acc: 43.57%

Epoch 61/150, Loss: 2.1381, Train Acc: 43.18%, Val Acc: 43.54%, Test Acc: 44.26%

Checkpoint saved at epoch 62: ./checkpoint_epoch_62.pth

Epoch 62/150, Loss: 2.1554, Train Acc: 42.80%, Val Acc: 42.19%, Test Acc: 42.45%

Epoch 63/150, Loss: 2.1329, Train Acc: 43.39%, Val Acc: 43.53%, Test Acc: 44.36%

Checkpoint saved at epoch 64: ./checkpoint_epoch_64.pth

Epoch 64/150, Loss: 2.1211, Train Acc: 43.15%, Val Acc: 43.72%, Test Acc: 44.26%

Epoch 65/150, Loss: 2.1163, Train Acc: 43.64%, Val Acc: 44.30%, Test Acc: 44.49%

Checkpoint saved at epoch 66: ./checkpoint_epoch_66.pth

Epoch 66/150, Loss: 2.0989, Train Acc: 44.15%, Val Acc: 45.67%, Test Acc: 45.27%

Epoch 67/150, Loss: 2.0922, Train Acc: 44.20%, Val Acc: 44.56%, Test Acc: 44.69%

Checkpoint saved at epoch 68: ./checkpoint_epoch_68.pth

Epoch 68/150, Loss: 2.0915, Train Acc: 43.93%, Val Acc: 43.67%, Test Acc: 44.10%

Epoch 69/150, Loss: 2.0766, Train Acc: 44.66%, Val Acc: 43.98%, Test Acc: 44.64%

Checkpoint saved at epoch 70: ./checkpoint_epoch_70.pth

Epoch 70/150, Loss: 2.0811, Train Acc: 44.28%, Val Acc: 44.56%, Test Acc: 45.16%

Epoch 71/150, Loss: 2.0436, Train Acc: 45.10%, Val Acc: 43.71%, Test Acc: 44.83%

Checkpoint saved at epoch 72: ./checkpoint_epoch_72.pth

Epoch 72/150, Loss: 2.0602, Train Acc: 44.95%, Val Acc: 42.40%, Test Acc: 43.44%

Epoch 73/150, Loss: 2.0483, Train Acc: 45.27%, Val Acc: 44.35%, Test Acc: 44.88%

Checkpoint saved at epoch 74: ./checkpoint_epoch_74.pth

Epoch 74/150, Loss: 2.0420, Train Acc: 45.23%, Val Acc: 45.44%, Test Acc: 46.22%

Epoch 75/150, Loss: 2.0276, Train Acc: 45.73%, Val Acc: 45.34%, Test Acc: 45.86%

Checkpoint saved at epoch 76: ./checkpoint_epoch_76.pth

Epoch 76/150, Loss: 2.0252, Train Acc: 45.87%, Val Acc: 46.40%, Test Acc: 46.51%

Epoch 77/150, Loss: 1.9954, Train Acc: 46.14%, Val Acc: 46.18%, Test Acc: 46.75%

Checkpoint saved at epoch 78: ./checkpoint_epoch_78.pth

Epoch 78/150, Loss: 1.9966, Train Acc: 45.90%, Val Acc: 46.32%, Test Acc: 46.48%

Epoch 79/150, Loss: 1.9813, Train Acc: 46.54%, Val Acc: 44.49%, Test Acc: 44.57%

Checkpoint saved at epoch 80: ./checkpoint_epoch_80.pth

Epoch 80/150, Loss: 1.9806, Train Acc: 46.55%, Val Acc: 45.88%, Test Acc: 46.47%

Epoch 81/150, Loss: 1.9788, Train Acc: 46.65%, Val Acc: 46.01%, Test Acc: 46.40%

Checkpoint saved at epoch 82: ./checkpoint_epoch_82.pth

Epoch 82/150, Loss: 1.9660, Train Acc: 47.06%, Val Acc: 46.47%, Test Acc: 46.60%

Epoch 83/150, Loss: 1.9688, Train Acc: 46.98%, Val Acc: 47.35%, Test Acc: 46.92%

Checkpoint saved at epoch 84: ./checkpoint_epoch_84.pth

Epoch 84/150, Loss: 1.9429, Train Acc: 47.42%, Val Acc: 46.66%, Test Acc: 47.39%

Epoch 85/150, Loss: 1.9401, Train Acc: 47.53%, Val Acc: 45.92%, Test Acc: 45.90%

Checkpoint saved at epoch 86: ./checkpoint_epoch_86.pth

Epoch 86/150, Loss: 1.9442, Train Acc: 47.55%, Val Acc: 46.79%, Test Acc: 46.78%

Epoch 87/150, Loss: 1.9329, Train Acc: 47.65%, Val Acc: 46.84%, Test Acc: 47.79%

Checkpoint saved at epoch 88: ./checkpoint_epoch_88.pth

Epoch 88/150, Loss: 1.9183, Train Acc: 48.04%, Val Acc: 48.00%, Test Acc: 47.37%

Epoch 89/150, Loss: 1.8943, Train Acc: 48.91%, Val Acc: 47.92%, Test Acc: 47.57%

Checkpoint saved at epoch 90: ./checkpoint_epoch_90.pth

Epoch 90/150, Loss: 1.8851, Train Acc: 48.65%, Val Acc: 47.23%, Test Acc: 48.54%

Epoch 91/150, Loss: 1.8876, Train Acc: 48.54%, Val Acc: 47.00%, Test Acc: 47.87%

Checkpoint saved at epoch 92: ./checkpoint_epoch_92.pth

Epoch 92/150, Loss: 1.8827, Train Acc: 48.82%, Val Acc: 47.80%, Test Acc: 48.32%

Epoch 93/150, Loss: 1.8629, Train Acc: 48.98%, Val Acc: 47.87%, Test Acc: 48.82%

Checkpoint saved at epoch 94: ./checkpoint_epoch_94.pth

Epoch 94/150, Loss: 1.8630, Train Acc: 49.35%, Val Acc: 46.90%, Test Acc: 47.17%

Epoch 95/150, Loss: 1.8604, Train Acc: 49.20%, Val Acc: 48.07%, Test Acc: 47.81%

Checkpoint saved at epoch 96: ./checkpoint_epoch_96.pth

Epoch 96/150, Loss: 1.8583, Train Acc: 49.12%, Val Acc: 48.62%, Test Acc: 49.00%

Epoch 97/150, Loss: 1.8468, Train Acc: 49.77%, Val Acc: 47.92%, Test Acc: 48.84%

Checkpoint saved at epoch 98: ./checkpoint_epoch_98.pth

Epoch 98/150, Loss: 1.8258, Train Acc: 50.08%, Val Acc: 48.82%, Test Acc: 49.12%

Epoch 99/150, Loss: 1.8236, Train Acc: 50.26%, Val Acc: 48.32%, Test Acc: 48.81%

Checkpoint saved at epoch 100: ./checkpoint_epoch_100.pth

Epoch 100/150, Loss: 1.8244, Train Acc: 49.76%, Val Acc: 48.05%, Test Acc: 49.46%

Epoch 101/150, Loss: 1.8023, Train Acc: 50.64%, Val Acc: 48.22%, Test Acc: 48.94%

Checkpoint saved at epoch 102: ./checkpoint_epoch_102.pth

Epoch 102/150, Loss: 1.8037, Train Acc: 50.83%, Val Acc: 48.87%, Test Acc: 49.98%

Epoch 103/150, Loss: 1.7947, Train Acc: 50.50%, Val Acc: 48.77%, Test Acc: 49.39%

Checkpoint saved at epoch 104: ./checkpoint_epoch_104.pth

Epoch 104/150, Loss: 1.7827, Train Acc: 50.98%, Val Acc: 48.51%, Test Acc: 48.89%

Epoch 105/150, Loss: 1.7805, Train Acc: 51.02%, Val Acc: 50.07%, Test Acc: 49.96%

Checkpoint saved at epoch 106: ./checkpoint_epoch_106.pth

Epoch 106/150, Loss: 1.7679, Train Acc: 51.32%, Val Acc: 48.65%, Test Acc: 49.07%

Epoch 107/150, Loss: 1.7654, Train Acc: 51.35%, Val Acc: 48.60%, Test Acc: 49.17%

Checkpoint saved at epoch 108: ./checkpoint_epoch_108.pth

Epoch 108/150, Loss: 1.7550, Train Acc: 51.68%, Val Acc: 49.01%, Test Acc: 49.82%

Epoch 109/150, Loss: 1.7548, Train Acc: 51.91%, Val Acc: 49.01%, Test Acc: 49.96%

Checkpoint saved at epoch 110: ./checkpoint_epoch_110.pth

Epoch 110/150, Loss: 1.7449, Train Acc: 51.73%, Val Acc: 49.46%, Test Acc: 49.95%

Epoch 111/150, Loss: 1.7450, Train Acc: 51.65%, Val Acc: 49.44%, Test Acc: 49.96%

Checkpoint saved at epoch 112: ./checkpoint_epoch_112.pth

Epoch 112/150, Loss: 1.7259, Train Acc: 52.40%, Val Acc: 49.66%, Test Acc: 50.79%

Epoch 113/150, Loss: 1.7098, Train Acc: 52.67%, Val Acc: 50.20%, Test Acc: 50.77%

Checkpoint saved at epoch 114: ./checkpoint_epoch_114.pth

Epoch 114/150, Loss: 1.7155, Train Acc: 52.72%, Val Acc: 49.47%, Test Acc: 50.36%

Epoch 115/150, Loss: 1.6947, Train Acc: 53.22%, Val Acc: 50.53%, Test Acc: 51.03%

Checkpoint saved at epoch 116: ./checkpoint_epoch_116.pth

Epoch 116/150, Loss: 1.6999, Train Acc: 52.72%, Val Acc: 50.37%, Test Acc: 50.82%

Epoch 117/150, Loss: 1.6868, Train Acc: 53.38%, Val Acc: 50.52%, Test Acc: 50.29%

Checkpoint saved at epoch 118: ./checkpoint_epoch_118.pth

Epoch 118/150, Loss: 1.6921, Train Acc: 53.21%, Val Acc: 50.08%, Test Acc: 50.86%

Epoch 119/150, Loss: 1.6850, Train Acc: 53.41%, Val Acc: 50.49%, Test Acc: 50.85%

Checkpoint saved at epoch 120: ./checkpoint_epoch_120.pth

Epoch 120/150, Loss: 1.6756, Train Acc: 53.37%, Val Acc: 50.43%, Test Acc: 50.69%

Epoch 121/150, Loss: 1.6811, Train Acc: 53.62%, Val Acc: 50.88%, Test Acc: 51.85%

Checkpoint saved at epoch 122: ./checkpoint_epoch_122.pth

Epoch 122/150, Loss: 1.6563, Train Acc: 54.18%, Val Acc: 51.05%, Test Acc: 51.43%

Epoch 123/150, Loss: 1.6616, Train Acc: 53.77%, Val Acc: 50.55%, Test Acc: 51.60%

Checkpoint saved at epoch 124: ./checkpoint_epoch_124.pth

Epoch 124/150, Loss: 1.6545, Train Acc: 54.02%, Val Acc: 50.54%, Test Acc: 51.49%

Epoch 125/150, Loss: 1.6481, Train Acc: 54.20%, Val Acc: 51.01%, Test Acc: 51.47%

Checkpoint saved at epoch 126: ./checkpoint_epoch_126.pth

Epoch 126/150, Loss: 1.6514, Train Acc: 53.85%, Val Acc: 51.54%, Test Acc: 51.94%

Epoch 127/150, Loss: 1.6383, Train Acc: 54.49%, Val Acc: 50.60%, Test Acc: 51.87%

Checkpoint saved at epoch 128: ./checkpoint_epoch_128.pth

Epoch 128/150, Loss: 1.6299, Train Acc: 54.78%, Val Acc: 51.24%, Test Acc: 51.07%

Epoch 129/150, Loss: 1.6323, Train Acc: 54.62%, Val Acc: 51.14%, Test Acc: 51.66%

Checkpoint saved at epoch 130: ./checkpoint_epoch_130.pth

Epoch 130/150, Loss: 1.6241, Train Acc: 54.70%, Val Acc: 51.46%, Test Acc: 51.67%

Epoch 131/150, Loss: 1.6243, Train Acc: 54.79%, Val Acc: 51.59%, Test Acc: 51.96%

Checkpoint saved at epoch 132: ./checkpoint_epoch_132.pth

Epoch 132/150, Loss: 1.6224, Train Acc: 54.81%, Val Acc: 51.28%, Test Acc: 51.43%

Epoch 133/150, Loss: 1.6067, Train Acc: 55.15%, Val Acc: 51.63%, Test Acc: 51.23%

Checkpoint saved at epoch 134: ./checkpoint_epoch_134.pth

Epoch 134/150, Loss: 1.6108, Train Acc: 54.97%, Val Acc: 51.08%, Test Acc: 51.89%

Epoch 135/150, Loss: 1.6031, Train Acc: 55.11%, Val Acc: 51.84%, Test Acc: 51.33%

Checkpoint saved at epoch 136: ./checkpoint_epoch_136.pth

Epoch 136/150, Loss: 1.6124, Train Acc: 54.95%, Val Acc: 52.08%, Test Acc: 52.01%

Epoch 137/150, Loss: 1.6021, Train Acc: 55.12%, Val Acc: 52.02%, Test Acc: 52.01%

Checkpoint saved at epoch 138: ./checkpoint_epoch_138.pth

Epoch 138/150, Loss: 1.5971, Train Acc: 55.52%, Val Acc: 51.37%, Test Acc: 51.96%

Epoch 139/150, Loss: 1.6014, Train Acc: 55.03%, Val Acc: 51.56%, Test Acc: 52.11%

Checkpoint saved at epoch 140: ./checkpoint_epoch_140.pth

Epoch 140/150, Loss: 1.5932, Train Acc: 55.42%, Val Acc: 51.69%, Test Acc: 52.18%

Epoch 141/150, Loss: 1.5935, Train Acc: 55.45%, Val Acc: 51.60%, Test Acc: 52.13%

Checkpoint saved at epoch 142: ./checkpoint_epoch_142.pth

Epoch 142/150, Loss: 1.5849, Train Acc: 55.52%, Val Acc: 51.49%, Test Acc: 52.86%

Epoch 143/150, Loss: 1.5885, Train Acc: 55.62%, Val Acc: 50.96%, Test Acc: 52.32%

Checkpoint saved at epoch 144: ./checkpoint_epoch_144.pth

Epoch 144/150, Loss: 1.5941, Train Acc: 55.08%, Val Acc: 51.77%, Test Acc: 52.04%

Epoch 145/150, Loss: 1.5938, Train Acc: 55.43%, Val Acc: 52.23%, Test Acc: 52.45%

Checkpoint saved at epoch 146: ./checkpoint_epoch_146.pth

Epoch 146/150, Loss: 1.5876, Train Acc: 55.30%, Val Acc: 51.75%, Test Acc: 51.78%

Epoch 147/150, Loss: 1.5887, Train Acc: 55.58%, Val Acc: 51.47%, Test Acc: 52.56%

Checkpoint saved at epoch 148: ./checkpoint_epoch_148.pth

Epoch 148/150, Loss: 1.5920, Train Acc: 55.32%, Val Acc: 52.13%, Test Acc: 51.99%

Epoch 149/150, Loss: 1.5852, Train Acc: 55.46%, Val Acc: 51.76%, Test Acc: 52.51%

Checkpoint saved at epoch 150: ./checkpoint_epoch_150.pth

Epoch 150/150, Loss: 1.5836, Train Acc: 55.53%, Val Acc: 51.62%, Test Acc: 52.16%

## Plots

![image](https://github.com/user-attachments/assets/62064dcf-2d12-4732-9379-31995d9a3ca2)
![image](https://github.com/user-attachments/assets/1f08d612-a449-427a-bf35-ed0e5aa44b73)
![image](https://github.com/user-attachments/assets/9f0cdb82-9f53-47f2-94dc-673ed1a4f571)
![image](https://github.com/user-attachments/assets/cdf36d1c-393d-4038-bf90-6a266e98a5ac)








