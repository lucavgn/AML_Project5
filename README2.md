# How to Run the Code
## Centralized Baseline
For this section of the project, four mostly identical codes were implemented. The first two, 'Center_CIFAR_100_80split20_AdamW.ipynb' and 'Center_CIFAR_100_TestModel_AdamW.ipynb', use the AdamW optimizer and were employed for hyperparameter tuning and testing, respectively. Similarly, 'Center_CIFAR_100_80split20_SGDM.ipynb' and 'Center_CIFAR_100_TestModel_SGDM.ipynb' use the SGDM optimizer.

In the various tests, the values of the learning rate (lr) and weight decay were modified, which are defined in the first section of the code labeled 'Training setting'.

### Best Hyperparameters:
#### AdamW:
- weight_decay: 1e-1
- lr: 5e-4
- β1: 0.9
- β2: 0.999
- batch_size: 64
#### SGDM:
- weight_decay: 4e-4
- lr: 1e-3
- momentum: 0.9
- batch_size: 64
## Large Batch Optimizers
In this section of the project, to enable all tests to be performed with various optimizers (SGDM, AdamW, LARS and LAMB), we configured the code to allow the optimizer selection via command line. Four parameters must be provided via the command line:

- The name of the file to execute, ending with .py (in this case, 'large_batch_training.py').
- The optimizer to use (choose from SGDM, AdamW, LARS or LAMB).
- The batch size for the test.
- The weight decay value.

Two scripts are available:

- 'Centr_Training_80split20_LargeBach.ipynb' for hyperparameter tuning with a training-validation dataset split.
- 'Centr_Training_TestModel_LargeBach.ipynb' for testing.

To set the learning rate for each optimizer, modify the 'base_lr' variable in the 'Mapping optimizer' section of the code.

Command Line Structure:

- %run script_name.py --optimizer optimizer_name --batch-size batch_value --weight-decay weight_decay_value

Example:
- %run large_batch_training.py --optimizer SGDM --batch-size 128 --weight-decay 4e-4
### Best Hyperparameters:
#### SGDM:
- lr: 1e-3
- weight_decay: 4e-4
- momentum: 0.9
#### AdamW:
- lr: 1e-4
- weight_decay: 1e-1
- β1: 0.9
- β2: 0.999
#### LARS:
- lr: 25e-2
- weight_decay: 4e-4
- momentum: 0.9
- trust_coefficient: 0.001
#### LAMB:
- lr: 5e-4
- weight_decay: 1e-1
- β1: 0.9
- β2: 0.999
## LocalSGD
For this section of the project, to enable testing, we configured the code to allow the selection of workers (K) and local steps (J) via the command line.The script is 'Distributed_LocalSGD.ipynb' and three parameters must be provided via the command line:

- The name of the file to execute, ending with .py (in this case, 'localSGD.py').
- The number of workers to use for the test (K: [2, 4, 8]).
- The number of local steps (J: [4, 8, 16, 32, 64]).

Other hyperparameters are directly set in the 'Define hyperparameters' section of the code.

Command Line Structure:
- %run script_name.py --k workers_num --j step_num

Example:
- %run localSGD.py --k 2 --j 32
### Best Hyperparameters:
- base_learning_rate: 1e-3
- batch_size: 64
- momentum: 0.9
- weight_decay: 4e-4
## SlowMo
In this section, testing is configured similarly to LocalSGD, allowing the selection of workers (K) and local steps (J) via the command line. The script is 'Distributed_LocalSGD_SlowMo.ipynb' and the three required parameters are:

- The name of the file to execute, ending with .py (in this case, 'localSGD_SlowMo.py').
- The number of workers (K: [2, 4, 8]).
- The number of local steps (J).

Other hyperparameters are defined in the 'Define hyperparameters' section of the code.

Command Line Structure:
- %run script_name.py --k workers_num --j step_num

Example:
- %run localSGD.py --k 2 --j 32
### Best Hyperparameters:
- base_learning_rate: 1e-3
- batch_size: 64
- momentum: 0.9
- weight_decay: 4e-4
- α: 0.75
- β: 0.20
- J: 16
## Personal Contribution
For this section of the project, testing was configured to allow the selection of workers (K) and initial local steps (J) via the command line. The script is 'DynamicSGD_starting_code.ipynb' and three parameters must be provided:

- The name of the file to execute, ending with .py (in this case, 'localSGD.py').
- The number of workers (K: [2, 4, 8]).
- The number of local steps (J).

Other hyperparameters are defined in the 'Define hyperparameters' section of the code.

Command Line Structure:
- %run script_name.py --k workers_num --j step_num

Example:
- %run localSGD.py --k 2 --j 32
### Best Hyperparameters:
- batch_size: 64
- base_learning_rate: 1e-3
- momentum: 0.9
- weight_decay: 4e-4

Best results were achieved by setting:

- H_min: 4
- H_max: 64
- alpha: 
- epsilon: 1e-6