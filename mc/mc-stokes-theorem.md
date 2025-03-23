---
field: multivariable-calculus
category: theorem
dependencies: [mc-surface-integrals, mc-curl]
weight: 2
tags: [multivariable-calculus, theorem]
---

# Stokes' Theorem

Stokes' Theorem relates the surface integral of the curl of a vector field over a surface to the line integral of the vector field around the boundary of the surface.

## Statement
For a smooth oriented surface $S$ with boundary curve $C$:

$$\iint_S (\nabla \times \mathbf{F}) \cdot d\mathbf{S} = \oint_C \mathbf{F} \cdot d\mathbf{r}$$

## Key Insights
- Generalizes Green's theorem to 3D surfaces
- Connects surface behavior with boundary behavior
- Foundation for understanding electromagnetic theory

## Applications
- Electromagnetism (Maxwell's equations)
- Fluid dynamics (circulation and vorticity)
- Differential geometry

## Leads To
- [[df-generalized-stokes-theorem|Generalized Stokes' Theorem]]

## See Also
- [[mc-green-theorem|Green's Theorem]]
- [[mc-divergence-theorem|Divergence Theorem]]
- [[df-exterior-derivative|Exterior Derivative]]