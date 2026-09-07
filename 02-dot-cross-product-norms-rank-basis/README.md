# Dot / Cross Product, Norms, Rank, Basis

> Part of [Maths-for-ML](../Readme.md)

## Goals
- [ ] Dot product: `a·b`, cosine similarity, projections
- [ ] Cross product (3D): area, orthogonal vector
- [ ] Norms: L0 / L1 / L2 / Linf, unit vectors, normalization
- [ ] Rank, column/row space, linear independence, basis, dimension

## Key formulas
- `a·b = ||a|| ||b|| cos(theta)`
- `||x||_2 = sqrt(sum x_i^2)`, `||x||_1 = sum |x_i|`

## Practice (numpy)
```python
import numpy as np

a = np.array([1, 2, 3])
b = np.array([4, 5, 6])
print("dot:", a @ b)
print("L2:", np.linalg.norm(a))
print("rank:", np.linalg.matrix_rank(np.array([[1, 2], [2, 4]])))
```
