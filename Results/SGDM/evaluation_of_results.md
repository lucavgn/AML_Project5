# RESULTS

## 1

- Parameters
  
| Epochs | batch_size | momentum | weight_decay | learning_rate | dropout1 | dropout2|
|---|---|---|---|---|---|---|
|150 | 128 | 0.9 | 1e-4 | 0.1 |-|-|

- Dropout:- Not applied
- Results:-
    - Train Accuracy: 68.09%
    - Validation Accuracy: 48.13%
    - Test Accuracy: 48.83%
    - Loss: 1.0867
- Analysis:- 
    - High training accuracy compared to validation and test accuracy indicates overfitting.
    - The high learning rate may lead to convergence at sharp minima, limiting generalization.

## 2

- Parameters
  
| Epochs | batch_size | momentum | weight_decay | learning_rate | dropout1 | dropout2|
|---|---|---|---|---|---|---|
|150 | 128 | 0.9 | 1e-4 | 0.01 |-|0.5|

- Dropout:- Just single dropout on last layer Dropout(0.5)

- Results:-
    - Train Accuracy: 58.83%
    - Validation Accuracy: 49.83%
    - Test Accuracy: 49.80%
    - Loss: 1.4535
- Analysis:- 
    - Reduced training accuracy due to the regularizing effect of dropout.
    - Improved generalization as validation and test accuracy increased slightly.

## 3

- Parameters
  
| Epochs | batch_size | momentum | weight_decay | learning_rate | dropout1 | dropout2|
|---|---|---|---|---|---|---|
|150 | 64 | 0.9 | 1e-4 | 0.01 |-|0.3|

- Dropout:- Just single dropout on last layer Dropout(0.3)

- Results:-
    - Train Accuracy: 67.66%
    - Validation Accuracy: 51.03%
    - Test Accuracy: 51.31%
    - Loss: 1.0984
- Analysis:- 
    - Lower batch size improved gradient updates but slowed training slightly.
    - Dropout reduced overfitting but impacted learning capacity at a smaller dropout rate.

## 4

- Parameters
  
| Epochs | batch_size | momentum | weight_decay | learning_rate | dropout1 | dropout2|
|---|---|---|---|---|---|---|
|150 | 128 | 0.9 | 1e-3 | 0.01 |0.3|0.3|

- Dropout:- Just double dropout on last layers Dropout(0.3)

- Results:-
    - Train Accuracy: 51.31%
    - Validation Accuracy: 50.03%
    - Test Accuracy: 50.26%
    - Loss: 1.7755
- Analysis:- 
    - The model struggles to fit the training data effectively.
    - The validation and test accuracies are close to each other, which is a good sign of generalization.
    - This confirms the model is not learning the dataset effectively, likely due to underfitting.

## 5

- Parameters
  
| Epochs | batch_size | momentum | weight_decay | learning_rate | dropout1 | dropout2|
|---|---|---|---|---|---|---|
|150 | 128 | 0.9 | 1e-4 | 0.01 | 0.3|0.3|

- Dropout:- Just double dropout on last layers Dropout(0.3)

- Results:-
    - Train Accuracy: 53.38%
    - Validation Accuracy: 50.29%
    - Test Accuracy: 49.92%
    - Loss: 1.6748
- Analysis:- 
    - Reducing the value of weight_decay help reduce the loss.

## 6

- Parameters
  
| Epochs | batch_size | momentum | weight_decay | learning_rate | dropout1 | dropout2|
|---|---|---|---|---|---|---|
|150 | 64 | 0.9 | 5e-4 | 0.01 |0.5|0.5|

- Dropout:- Just double dropout on last layers Dropout(0.5)

- Results:-
    - Train Accuracy: 47.28%
    - Validation Accuracy: 48.25%
    - Test Accuracy: 49.47%
    - Loss: 1.9563


## 7

- Parameters
  
| Epochs | batch_size | momentum | weight_decay | learning_rate | dropout1 | dropout2|
|---|---|---|---|---|---|---|
|150 | 64 | 0.9 | 5e-4 | 0.01 |0.3|0.3|

- Dropout:- Just double dropout on last layers Dropout(0.3)

- Results:-
    - Train Accuracy: 56.13%
    - Validation Accuracy: 52.20%
    - Test Accuracy: 53.65%
    - Loss: 1.5558
- Analysis:- 
    - So far this is the best parameter.
    - Adding droupout of 0.3 helped model to not overfit and also to get lower loss.
    - Lower batch size and moderate weight decay balanced regularization and training capacity.
    - 

## 8

- Parameters

| Epochs | batch_size | momentum | weight_decay | learning_rate | dropout1 | dropout2|
|---|---|---|---|---|---|---|
|150 | 32 | 0.9 | 5e-4 | 0.01 |0.3|0.3|

- Dropout:- double dropout on last layer(0.3)

- Results:-
    - Train Accuracy: 56.84%
    - Validation Accuracy: 52.25%
    - Test Accuracy: 52.62% 
    - Loss: 1.5547
 
## 9

- Parametrs

| Epochs | batch_size | momentum | weight_decay | learning_rate | dropout1 | dropout2|
|---|---|---|---|---|---|---|
|150 | 128 | 0.99 | 5e-4 | 0.01 |0.3|0.3|

- double dropout of 0.3

- Results:-
    - Train Accuracy: 45.12%
    - Validation Accuracy: 45.83%
    - Test Accuracy: 45.78% 
    - Loss: 2.0468
 
- Increase in momemtume reduced the accuracy and increased loss


## 10

- Parametrs

| Epochs | batch_size | momentum | weight_decay | learning_rate | dropout1 | dropout2|
|---|---|---|---|---|---|---|
|150 | 64 | 0.9 | 1e-3 | 0.01 |0.3|0.3|

- double dropout of 0.3

- Results:-
    - Train Accuracy: 53.86%
    - Validation Accuracy: 51.03%
    - Test Accuracy: 52.00% 
    - Loss: 1.6578
 
- Increase in momemtume reduced the accuracy and increased loss


## 11

- Parameters
  
| Epochs | batch_size | momentum | weight_decay | learning_rate | dropout1 | dropout2|
|---|---|---|---|---|---|---|
|150 | 32 | 0.9 | 1e-3 | 0.01 |0.3|0.3|

- Dropout:- Double of 0.2
- Results:-
    - Train Accuracy: 54.23%
    - Validation Accuracy: 52.25%
    - Test Accuracy: 52.53%
    - Loss: 1.6506
- Analysis:- 
    - Reduction of batch size has no huge effect on the results.
    - 


## 12

- Parameters
  
| Epochs | batch_size | momentum | weight_decay | learning_rate | dropout1 | dropout2|
|---|---|---|---|---|---|---|
|150 | 32 | 0.9 | 4e-4 | 0.01 |0.3|0.3|

- Dropout:- two droupout of 0.3
- Results:-
    - Train Accuracy: 53.70%
    - Validation Accuracy: 53.77%
    - Test Accuracy: 54.21%
    - Loss: 1.6952
- Analysis:- 
    - for this output i tried adding the batch normalization to the lenet5 architecture
    - super(LeNet5, self).__init__()
      
            self.conv1 = nn.Conv2d(3, 64, 5)
          
            self.bn1 = nn.BatchNorm2d(64)  # Batch Normalization after conv1
          
            self.relu1 = nn.ReLU()
          
            self.pool1 = nn.MaxPool2d(2, 2)
            
            self.conv2 = nn.Conv2d(64, 64, 5)
          
            self.bn2 = nn.BatchNorm2d(64)  # Batch Normalization after conv2
          
            self.relu2 = nn.ReLU()
          
            self.pool2 = nn.MaxPool2d(2, 2)
            
            self.fc1 = nn.Linear(64 * 5 * 5, 384)
          
            self.bn3 = nn.BatchNorm1d(384)  # Batch Normalization for fully connected layers
          
            self.relu3 = nn.ReLU()
          
            self.drop1 = nn.Dropout(p=0.3)
            
            self.fc2 = nn.Linear(384, 192)
          
            self.bn4 = nn.BatchNorm1d(192)  # Batch Normalization for fully connected layers
          
            self.relu4 = nn.ReLU()
          
            self.drop2 = nn.Dropout(p=0.3)
            
            self.fc3 = nn.Linear(192, 100)
    
## 13

- Parameters
  
| Epochs | batch_size | momentum | weight_decay | learning_rate | dropout1 | dropout2|
|---|---|---|---|---|---|---|
|150 | 32 | 0.9 | 4e-4 | 0.01 | 0.3|0.3|

- Dropout:- Just double dropout on last layers Dropout(0.3)

- Results:-
    - Train Accuracy: 54.86%
    - Validation Accuracy: 53.30%
    - Test Accuracy: 54.14%
    - Loss: 1.6214
- super(LeNet5, self).__init__()
  
        self.conv1 = nn.Conv2d(3, 64, 5)
  
        self.bn1 = nn.BatchNorm2d(64)  # Batch Normalization after conv1
  
        self.relu1 = nn.ReLU()
  
        self.pool1 = nn.MaxPool2d(2, 2)

        self.conv2 = nn.Conv2d(64, 64, 5)
  
        self.bn2 = nn.BatchNorm2d(64)  # Batch Normalization after conv2

  - used just batch normalization of covolution layer and not on fully connected
  - 

# RESULTS WITHOUT ANY EXTRA MODIFICATION IN THE MODEL ARCHITECTURE

## 1

### Parameters and Results
  
| Epochs | batch_size | momentum | weight_decay | learning_rate | Loss | Train_Acc | Val_Acc | Test_Acc|
|---|---|---|---|---|---|---|---|---|
|150 | 128 | 0.9 | 5e-4 | 0.01 | 1.6078|56.08%|51.26%|51.74%|

### Plots

| Training_Loss | Training_Accuracy | Validation_Loss | Validation_Accuracy | Test_Loss | Test_Accuracy|
|---|---|---|---|---|---|
|![image](https://github.com/user-attachments/assets/e9eda97f-d351-4ebc-8c76-9ed1563df575) | ![image](https://github.com/user-attachments/assets/e52a88f7-df0a-4b94-a3ae-894c994cf282) | ![image](https://github.com/user-attachments/assets/4490de59-a4c0-4c0b-88f3-f1a10c31f1f9) | ![image](https://github.com/user-attachments/assets/69f721c6-fe2c-49e8-bdf0-9627335e4f09) | ![image](https://github.com/user-attachments/assets/89967cf8-c23a-4e1d-a2e4-5b6724e4e3b4) |![image](https://github.com/user-attachments/assets/32611472-3a54-4310-80ea-8a1a090846d1) |








## 2

### Parameters and Result
  
| Epochs | batch_size | momentum | weight_decay | learning_rate |Loss | Train_Acc | Val_Acc | Test_Acc|
|---|---|---|---|---|---|---|---|---|
|150 | 128 | 0.9 | 5e-4 | 0.001 |3.0656|25.07%|28.58%|28.58%|

### Plots


| Training_Loss | Training_Accuracy | Validation_Loss | Validation_Accuracy | Test_Loss | Test_Accuracy|
|---|---|---|---|---|---|
|![image](https://github.com/user-attachments/assets/0a1c597d-9384-4e12-917d-f90a09dc5767) | ![image](https://github.com/user-attachments/assets/ecbd15a1-f6ef-40af-89dc-7c20ed06ea22) | ![image](https://github.com/user-attachments/assets/4b9f7171-2a8b-4f6d-9947-3a63aa67bafa) | ![image](https://github.com/user-attachments/assets/9b1a9a46-9e2e-4770-b1b9-5af5dec3c552) | ![image](https://github.com/user-attachments/assets/cbc6d7f5-4345-4766-810b-fe808f11f946) |![image](https://github.com/user-attachments/assets/4faa441e-110a-4c8e-8181-15c14143de37) |


## 3

### Parameters and Result
  
| Epochs | batch_size | momentum | weight_decay | learning_rate |Loss | Train_Acc | Val_Acc | Test_Acc|
|---|---|---|---|---|---|---|---|---|
|150 | 128 | 0.9 | 5e-4 | 0.1 |1.6514|54.84%|53.22%|53.19%|

### Plots


| Training_Loss | Training_Accuracy | Validation_Loss | Validation_Accuracy | Test_Loss | Test_Accuracy|
|---|---|---|---|---|---|
|![image](https://github.com/user-attachments/assets/04f121e9-bfdd-4915-b30c-cf096320967a) |![image](https://github.com/user-attachments/assets/54bfed7e-0811-4831-88f7-57f1bae726b5) | ![image](https://github.com/user-attachments/assets/99c93c17-5767-4c77-8db5-dc7ede1197cf) | ![image](https://github.com/user-attachments/assets/b829cbf3-e97d-49cd-b504-101658044c70) | ![image](https://github.com/user-attachments/assets/efeddf16-f3f5-42cf-bc51-aa6709ade84b) |![image](https://github.com/user-attachments/assets/9df11013-40db-42dd-91bf-b695f5887dc1) |


## 4

### Parameters and Result
  
| Epochs | batch_size | momentum | weight_decay | learning_rate |Loss | Train_Acc | Val_Acc | Test_Acc|
|---|---|---|---|---|---|---|---|---|
|150 | 128 | 0.9 | 1e-4 | 0.1 |1.5906|55.95%|50.64%|50.95%|

### Plots


| Training_Loss | Training_Accuracy | Validation_Loss | Validation_Accuracy | Test_Loss | Test_Accuracy|
|---|---|---|---|---|---|
|![image](https://github.com/user-attachments/assets/cf8356c2-6e84-442f-83b2-a44869a32b8b) |![image](https://github.com/user-attachments/assets/4b69f15f-a68f-4c5c-83c3-ba51afc089d0) | ![image](https://github.com/user-attachments/assets/7f21ac1d-54e7-4eac-8b73-854d9f5c5d05) | ![image](https://github.com/user-attachments/assets/17576c4d-0351-4168-a482-27a6adbdb919) | ![image](https://github.com/user-attachments/assets/be759014-8750-4385-aafd-9599b4e52d44) |![image](https://github.com/user-attachments/assets/a3107a08-55e3-42b4-9c49-05b17f1b174a)|


## 5

### Parameters and Result
  
| Epochs | batch_size | momentum | weight_decay | learning_rate |Loss | Train_Acc | Val_Acc | Test_Acc|
|---|---|---|---|---|---|---|---|---|
|150 | 64 | 0.9 | 4e-4 | 0.01 |1.4508|59.47%|53.48%|53.42%|

### Plots


| Training_Loss | Training_Accuracy | Validation_Loss | Validation_Accuracy | Test_Loss | Test_Accuracy|
|---|---|---|---|---|---|
|![image](https://github.com/user-attachments/assets/b50dcd22-f57f-4607-9cae-dd475ea73d32) |![image](https://github.com/user-attachments/assets/0200f208-5e75-4a57-8fcd-956b1fcd67f6) |![image](https://github.com/user-attachments/assets/b4e8dc38-d3be-4700-a37a-408d1c4987d8) | ![image](https://github.com/user-attachments/assets/7891bc4e-f055-4cc3-803f-474f516e96b2)| ![image](https://github.com/user-attachments/assets/584164f4-98aa-4be0-866b-b4a14ea1c983) |![image](https://github.com/user-attachments/assets/b502ccfd-e157-4b2d-9216-39a220a07c85)|


## 6

### Parameters and Result

### Transform

train_transform = transforms.Compose([
    transforms.RandomHorizontalFlip(0.5),
    transforms.RandomCrop(32,4),
    transforms.ColorJitter(
    brightness=0.2,
    contrast=0.2,
    saturation=0.2,
    hue=0.1
    ),
    transforms.ToTensor(),  # Converti in tensore
    transforms.Normalize((0.5, 0.5, 0.5), (0.5, 0.5, 0.5))  # Normalizzazione
])
  
| Epochs | batch_size | momentum | weight_decay | learning_rate |Loss | Train_Acc | Val_Acc | Test_Acc|
|---|---|---|---|---|---|---|---|---|
|150 | 64 | 0.9 | 4e-4 | 0.01 |0.6050|81.75%|53.13%|54.62%|

### Plots


| Training_Loss | Training_Accuracy | Validation_Loss | Validation_Accuracy | Test_Loss | Test_Accuracy|
|---|---|---|---|---|---|
|![image](https://github.com/user-attachments/assets/f8771f66-50e8-46ad-8f0e-71ff4fd8671e)|![image](https://github.com/user-attachments/assets/1ac5fac8-6f24-4022-b455-7d838e21e967) |![image](https://github.com/user-attachments/assets/5c85c9c9-dfcb-48e6-89e5-e2cdd214a907)|![image](https://github.com/user-attachments/assets/2167a166-4a44-4975-8d52-b46b7b53d501)| ![image](https://github.com/user-attachments/assets/233234c9-0441-4dd0-a38d-3ceee92c9d60)|![image](https://github.com/user-attachments/assets/2f478359-6e42-46d0-bc4e-b8bdd7facdfb)|












           
