---
field: differential-forms
category: concept
dependencies: [df-dual-space, mt-tangent-spaces, mc-line-integrals]
weight: 4
tags: [differential-forms, fundamental]
---

# 1-Forms

1-Forms are covectors or linear functionals that measure objects in tangent spaces, representing the simplest type of differential form.

## Definition
A 1-form on a manifold $M$ is a smooth assignment of a linear functional $\omega_p: T_pM \to \mathbb{R}$ to each point $p \in M$.

## Local Representation
In local coordinates $(x^1, \ldots, x^n)$, a 1-form $\omega$ can be written as:
$$\omega = \sum_{i=1}^n f_i(x) dx^i$$
where $dx^i$ form the dual basis to $\frac{\partial}{\partial x^i}$.

## Examples
- The differential $df$ of a function $f$
- The work form $F_x dx + F_y dy + F_z dz$ in physics
- The canonical 1-form $p_i dq^i$ in Hamiltonian mechanics

## Key Properties
- Integration along curves
- Pullback under smooth maps
- Exterior derivative producing 2-forms
- Contraction with vector fields

## Leads To
- [[df-k-forms|k-Forms]]

## See Also
- [[mc-line-integrals|Line Integrals]]
- [[df-exterior-derivative|Exterior Derivative]]