- From paper 18 (Large_Batch_Optimization_for_Learning_Training) there were two suggested way of tuning the learning rate for thr large minibatches.
- One way is by order square root of the minibatch size.
    - new_learning_rate = learning_rate * (largerbatch_size / base_batch_size)**2
- Second way is linear scaling of the learning rate with minibatch size. Which is simply multiple the learning rate by k, where k is size multipled to the base_batch.
    - new_learning_rate = learning_rate * (largerbatch_size / base_batch_size)

- About the tuning of learning rate is also mentioned in paper "Goyal et al. (2017)". 


## Results









