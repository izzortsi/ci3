---
field: multivariable-calculus
category: operator
dependencies: [mc-vector-fields]
weight: 3
tags: [multivariable-calculus, vector-calculus]
---

# Divergence

Divergence is a scalar field measuring the volume density of the outward flux of a vector field from an infinitesimal volume around each point.

## Definition
For a vector field $\mathbf{F} = (F_1, F_2, F_3)$, the divergence is:

$$\operatorname{div}\mathbf{F} = \nabla \cdot \mathbf{F} = \frac{\partial F_1}{\partial x} + \frac{\partial F_2}{\partial y} + \frac{\partial F_3}{\partial z}$$

## Physical Interpretation
- Positive divergence: source (fluid flowing outward)
- Negative divergence: sink (fluid flowing inward)
- Zero divergence: incompressible flow (solenoidal field)

## Applications
- Fluid dynamics (continuity equation)
- Electromagnetism (Gauss's law)
- Heat diffusion

## Leads To
- [[mc-divergence-theorem|Divergence Theorem]]
- [[df-exterior-derivative|Exterior Derivative]]

## See Also
- [[mc-curl|Curl]]
- [[df-k-forms|k-Forms]]