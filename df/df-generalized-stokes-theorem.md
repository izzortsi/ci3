---
field: differential-forms
category: theorem
dependencies: [df-exterior-derivative, df-integration-of-forms, mc-green-theorem, mc-stokes-theorem, mc-divergence-theorem]
weight: 2
tags: [differential-forms, theorem]
---

# Generalized Stokes' Theorem

The Generalized Stokes' Theorem relates integration of a form over a manifold to integration over its boundary, unifying and generalizing the classical integral theorems of vector calculus.

## Statement
For a smooth oriented k-dimensional manifold $M$ with boundary $\partial M$ and a $(k-1)$-form $\omega$:

$\int_M d\omega = \int_{\partial M} \omega$

## Special Cases
- Fundamental Theorem of Calculus: $\int_a^b f'(x) dx = f(b) - f(a)$
- Green's Theorem: $\iint_D \left(\frac{\partial Q}{\partial x} - \frac{\partial P}{\partial y}\right) dA = \oint_C P dx + Q dy$
- Classical Stokes' Theorem: $\iint_S (\nabla \times \mathbf{F}) \cdot d\mathbf{S} = \oint_C \mathbf{F} \cdot d\mathbf{r}$
- Divergence Theorem: $\iiint_V (\nabla \cdot \mathbf{F}) dV = \iint_S \mathbf{F} \cdot d\mathbf{S}$

## Significance
- Provides a unified framework for integration theorems
- Connects local and global properties of manifolds
- Fundamental in differential geometry and topology
- Underpins many physical laws and conservation principles

## Applications
- Electromagnetism (Maxwell's equations)
- Conservation laws in physics
- Cohomology theory
- Topological invariants

## See Also
- [[df-de-rham-cohomology|de Rham Cohomology]]
- [[df-exterior-derivative|Exterior Derivative]]