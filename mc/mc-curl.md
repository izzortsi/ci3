---
field: multivariable-calculus
category: operator
dependencies: [mc-vector-fields]
weight: 3
tags: [multivariable-calculus, vector-calculus]
---

# Curl

Curl is a vector field measuring the rotation or circulation of a vector field, indicating the tendency of a fluid to rotate about a point.

## Definition
For a vector field $\mathbf{F} = (F_1, F_2, F_3)$, the curl is:

$$\operatorname{curl}\mathbf{F} = \nabla \times \mathbf{F} = \begin{pmatrix} 
\frac{\partial F_3}{\partial y} - \frac{\partial F_2}{\partial z} \\
\frac{\partial F_1}{\partial z} - \frac{\partial F_3}{\partial x} \\
\frac{\partial F_2}{\partial x} - \frac{\partial F_1}{\partial y}
\end{pmatrix}$$

## Key Properties
- Curl-free fields (irrotational) can be expressed as gradients of scalar fields
- The curl of a gradient is zero
- The divergence of a curl is zero

## Applications
- Fluid dynamics (vorticity)
- Electromagnetism (Faraday's law)
- Elasticity theory

## Leads To
- [[mc-stokes-theorem|Stokes' Theorem]]
- [[df-exterior-derivative|Exterior Derivative]]

## See Also
- [[mc-divergence|Divergence]]
- [[df-k-forms|k-Forms]]