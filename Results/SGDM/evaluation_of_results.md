# RESULTS

## 1

- Parameters
  
| Epochs | batch_size | momentum | weight_decay | learning_rate |
|---|---|---|---|---|
|150 | 128 | 0.9 | 1e-4 | 0.1 |

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
  
| Epochs | batch_size | momentum | weight_decay | learning_rate |
|---|---|---|---|---|
|150 | 128 | 0.9 | 1e-4 | 0.01 |

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
  
| Epochs | batch_size | momentum | weight_decay | learning_rate |
|---|---|---|---|---|
|150 | 64 | 0.9 | 1e-4 | 0.01 |

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
  
| Epochs | batch_size | momentum | weight_decay | learning_rate |
|---|---|---|---|---|
|150 | 128 | 0.9 | 1e-3 | 0.01 |

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
  
| Epochs | batch_size | momentum | weight_decay | learning_rate |
|---|---|---|---|---|
|150 | 128 | 0.9 | 1e-4 | 0.01 |

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
  
| Epochs | batch_size | momentum | weight_decay | learning_rate |
|---|---|---|---|---|
|150 | 64 | 0.9 | 5e-4 | 0.01 |

- Dropout:- Just double dropout on last layers Dropout(0.5)

- Results:-
    - Train Accuracy: 47.28%
    - Validation Accuracy: 48.25%
    - Test Accuracy: 49.47%
    - Loss: 1.9563


## 7

- Parameters
  
| Epochs | batch_size | momentum | weight_decay | learning_rate |
|---|---|---|---|---|
|150 | 64 | 0.9 | 5e-4 | 0.01 |

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

| Epochs | batch_size | momentum | weight_decay | learning_rate |
|---|---|---|---|---|
|150 | 32 | 0.9 | 5e-4 | 0.01 |

- Dropout:- double dropout on last layer(0.3)

- Results:-
    - Train Accuracy: 56.84%
    - Validation Accuracy: 52.25%
    - Test Accuracy: 52.62% 
    - Loss: 1.5547 
