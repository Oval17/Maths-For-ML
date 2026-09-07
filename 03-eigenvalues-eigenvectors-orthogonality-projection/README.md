# Eigenvalues / Eigenvectors, Orthogonality, Projection

> Part of [Maths-for-ML](../Readme.md)

## Goals
- [ ] `Av = λv`: eigenvalues / eigenvectors, characteristic equation
- [ ] Eigendecomposition, symmetric matrices, spectral theorem
- [ ] Orthogonality, orthonormal bases, Gram-Schmidt
- [ ] Projection: `proj_u(v)`, orthogonal projection matrices, least squares intuition

## Practice (numpy)
```python
import numpy as np

A = np.array([[4, 1], [2, 3]])
w, V = np.linalg.eig(A)
print("eigvals:", w)
print("eigvecs:\n", V)
```
