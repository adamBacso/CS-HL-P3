[[Hyperparameter tuning|hyperparameter]] that determines the number of training samples in a [[neural network]].

impacts memory usage, training speed and model performance

# Impacts

- small batch sizes lead to more frequent updates, speeding up training while creating greater noise
- small batch sizes require more memory, but larger batch sizes can better utilize parallelism of [[graphical processing unit|GPUs]]
- 