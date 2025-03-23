---
field: multivariable-calculus
category: concept
dependencies: [mc-partial-derivatives]
weight: 3
tags: [multivariable-calculus, linear-algebra]
---

# Jacobian Matrix

The Jacobian matrix is the matrix of all first-order partial derivatives of a vector-valued function, representing the best linear approximation to a differentiable function near a given point.

## Definition
For a function $\mathbf{F}: \mathbb{R}^n \to \mathbb{R}^m$ with components $(F_1, F_2, \ldots, F_m)$, the Jacobian matrix is:

$$J = \begin{pmatrix}
\frac{\partial F_1}{\partial x_1} & \cdots & \frac{\partial F_1}{\partial x_n} \\
\vdots & \ddots & \vdots \\
\frac{\partial F_m}{\partial x_1} & \cdots & \frac{\partial F_m}{\partial x_n}
\end{pmatrix}$$

## Key Properties
- The determinant of the Jacobian (when $m=n$) appears in change of variables formulas
- The Jacobian matrix represents the differential of the mapping
- When $\mathbf{F}$ is a diffeomorphism, the Jacobian is invertible

## Applications
- Coordinate transformations
- Implicit function theorem
- Newton's method for solving systems of equations

## Leads To
- [[mc-change-of-variables|Change of Variables]]
- [[mt-immersions-embeddings|Immersions & Embeddings]]

## See Also
- [[mt-smooth-manifolds|Smooth Manifolds]]
- [[df-pullbacks|Pullbacks]]