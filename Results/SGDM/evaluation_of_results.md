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

  # RESULTS WITHOUT DROPOUT

## 1

- Parameters
  
| Epochs | batch_size | momentum | weight_decay | learning_rate |
|---|---|---|---|---|
|150 | 128 | 0.9 | 5e-4 | 0.01 |

-Results:- Loss: 1.6078, 
           Train Acc: 56.08%, 
           Val Acc: 51.26%, 
           Test Acc: 51.74%

### Plots
![image](https://github.com/user-attachments/assets/e9eda97f-d351-4ebc-8c76-9ed1563df575)
![image](https://github.com/user-attachments/assets/e52a88f7-df0a-4b94-a3ae-894c994cf282)
![image](https://github.com/user-attachments/assets/4490de59-a4c0-4c0b-88f3-f1a10c31f1f9)
![image](https://github.com/user-attachments/assets/69f721c6-fe2c-49e8-bdf0-9627335e4f09)
![image](https://github.com/user-attachments/assets/89967cf8-c23a-4e1d-a2e4-5b6724e4e3b4)
![image](https://github.com/user-attachments/assets/32611472-3a54-4310-80ea-8a1a090846d1)






           
