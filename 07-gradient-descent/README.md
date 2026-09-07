# Gradient Descent

> Part of [Maths-for-ML](../Readme.md)

## Goals
- [ ] Batch / SGD / Mini-batch, learning rate, convergence intuition
- [ ] Momentum, AdaGrad / RMSProp / Adam (high level)
- [ ] Feature scaling, conditioning, local minima vs saddle points

## Practice (numpy)
```python
import numpy as np

# minimize f(x) = (x-3)^2
x = 0.0
lr = 0.1
for _ in range(50):
    grad = 2 * (x - 3)
    x -= lr * grad
print(x)  # ~3.0
```
