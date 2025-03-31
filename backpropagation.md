---
aliases:
  - backward propagation of errors
---
>[!important] Goal
>reduced the difference between the model's predicted output and the actual output

Technique used in [[feed-forward network|feed-forward networks]] to iteratively adjust [[Weights]] and [[biases]] to minimize [[cost function]]

![[Pasted image 20250326100529.png]]

often uses gradient descent optimization algorithms

# Advantages

1. computes gradient of [[loss function]] with respect to each weight -> updates weights efficiently
2. scales well
3. automated adjustment of weights and biases