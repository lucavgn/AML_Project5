# RESULTS

- Parameters
  
| Epochs | batch_size | momentum | weight_decay | learning_rate |
|---|---|---|---|---|
|150 | 128 | 0.9 | 1e-4 | 0.1 |

- Dropout:- Not applied
- Results:-
    - Train Accuracy: 68.09%
    - Validation Accuracy: 48.13%
    - Test Accuracy: 48.83%
- Analysis:- 
    - High training accuracy compared to validation and test accuracy indicates overfitting.
    - The high learning rate may lead to convergence at sharp minima, limiting generalization.
