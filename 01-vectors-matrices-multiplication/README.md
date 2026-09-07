# Vectors, Matrices, Matrix Multiplication

> Part of [Maths-for-ML](../Readme.md)

## Goals
- [ ] Vectors: addition, scalar multiplication, linear combinations
- [ ] Matrices: shapes, transpose, identity, inverse
- [ ] Matrix multiplication: rules, shapes `(m×n) @ (n×p) → (m×p)`, non-commutativity
- [ ] Broadcasting and `numpy` vectorization

## Key formulas
- Dot-style multiply: `C[i,j] = sum_k A[i,k] * B[k,j]`

## Practice (numpy)
```python
import numpy as np

A = np.array([[1, 2], [3, 4]])
B = np.array([[5, 6], [7, 8]])
print(A @ B)
print(A.T)
```
