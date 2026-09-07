# Conditional / Joint Probability, Markov Chains

> Part of [Maths-for-ML](../Readme.md)

## Goals
- [ ] Joint / marginal / conditional: `P(X,Y)`, `P(X) = Σ_y P(X,y)`
- [ ] Chain rule: `P(X,Y) = P(X|Y)P(Y)`
- [ ] Markov chains: transition matrix, stationary distribution, sampling intuition

## Practice (numpy)
```python
import numpy as np

P = np.array([[0.9, 0.1], [0.5, 0.5]])  # transition matrix
state = np.array([1.0, 0.0])
for _ in range(10):
    state = state @ P
print(state)
```
