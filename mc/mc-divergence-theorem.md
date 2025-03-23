---
field: multivariable-calculus
category: theorem
dependencies: [mc-divergence]
weight: 2
tags: [multivariable-calculus, theorem]
---

# Divergence Theorem

The Divergence Theorem (also known as Gauss's theorem) relates the flux of a vector field through a closed surface to the triple integral of the divergence over the volume it encloses.

## Statement
For a continuously differentiable vector field $\mathbf{F}$ defined on a region $V$ with boundary surface $S$:

$$\iint_S \mathbf{F} \cdot d\mathbf{S} = \iiint_V (\nabla \cdot \mathbf{F}) \, dV$$

## Key Insights
- Connects surface behavior (flux) with volume behavior (divergence)
- Generalizes the fundamental theorem of calculus to 3D
- Essential for understanding conservation laws

## Applications
- Electromagnetism (Gauss's law)
- Fluid dynamics (continuity equation)
- Heat transfer and diffusion processes

## Leads To
- [[df-generalized-stokes-theorem|Generalized Stokes' Theorem]]

## See Also
- [[mc-green-theorem|Green's Theorem]]
- [[mc-stokes-theorem|Stokes' Theorem]]
- [[df-exterior-derivative|Exterior Derivative]]