---
field: differential-forms
category: operation
dependencies: [df-k-forms, mt-manifolds]
weight: 3
tags: [differential-forms, analysis]
---

# Integration of Forms

Integration of forms is the process of evaluating differential forms over manifolds, generalizing integration from calculus to curved spaces.

## Definition
For a k-form $\omega$ and a k-dimensional oriented manifold $M$:

$\int_M \omega$

In local coordinates, if $\omega = f dx^1 \wedge \cdots \wedge dx^k$ and $M$ is parameterized by $\phi: U \subset \mathbb{R}^k \to M$, then:

$\int_M \omega = \int_U (f \circ \phi) \det(J_\phi) du^1 \cdots du^k$

where $J_\phi$ is the Jacobian matrix of $\phi$.

## Properties
- Linearity: $\int_M (a\omega + b\eta) = a\int_M \omega + b\int_M \eta$
- Orientation: $\int_{-M} \omega = -\int_M \omega$ where $-M$ is $M$ with opposite orientation
- Pullback formula: $\int_M f^*\omega = \int_{f(M)} \omega$ for proper maps $f$

## Examples
- Line integrals of 1-forms: $\int_\gamma \omega = \int_a^b \omega_{\gamma(t)}(\gamma'(t)) dt$
- Surface integrals of 2-forms on surfaces in $\mathbb{R}^3$
- Volume integrals of n-forms on n-dimensional manifolds

## Applications
- Formulating conservation laws in physics
- Defining periods of forms (integrals over cycles)
- Computing flux and circulation in vector fields
- Defining topological invariants

## Leads To
- [[df-generalized-stokes-theorem|Generalized Stokes' Theorem]]

## See Also
- [[mc-line-integrals|Line Integrals]]
- [[mc-surface-integrals|Surface Integrals]]