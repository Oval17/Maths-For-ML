# SVD, PCA, Tensors

> Part of [Maths-for-ML](../Readme.md)

## Goals
- [ ] SVD: `A = U Σ V^T`, singular values, low-rank approximation
- [ ] PCA: centering, covariance, top-k components, explained variance
- [ ] Tensors: shape, rank/order, reshaping, batched matmul intuition

## Practice (numpy)
```python
import numpy as np

A = np.array([[1, 2], [3, 4], [5, 6]], dtype=float)
U, S, Vt = np.linalg.svd(A, full_matrices=False)
print("S:", S)
k = 1
A_k = (U[:, :k] * S[:k]) @ Vt[:k, :]
print(A_k)
```
