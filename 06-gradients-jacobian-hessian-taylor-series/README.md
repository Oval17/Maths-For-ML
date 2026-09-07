# Gradients, Jacobian, Hessian, Taylor Series

> Part of [Maths-for-ML](../Readme.md)

## Goals
- [ ] Gradient `∇f`: direction of steepest ascent
- [ ] Jacobian: vector-valued functions `J[i,j] = ∂f_i/∂x_j`
- [ ] Hessian: second derivatives, curvature, convexity check
- [ ] Taylor series: linear / quadratic approximations

## Key formulas
- First-order: `f(x) ≈ f(a) + ∇f(a)^T (x-a)`
- Second-order: `f(x) ≈ f(a) + ∇f(a)^T (x-a) + 1/2 (x-a)^T H (x-a)`
