---
field: differential-forms
category: operation
dependencies: [df-k-forms, mc-div, mc-curl]
weight: 3
tags: [differential-forms, operation]
---

# Exterior Derivative

The exterior derivative is an operator generalizing the gradient, curl, and divergence operations, providing a unified framework for differential calculus on manifolds.

## Definition
The exterior derivative $d$ is a linear operator that maps k-forms to (k+1)-forms and satisfies certain properties. For a smooth function $f$ (0-form), $df$ is the differential of $f$.

For a k-form $\omega = \sum_{i_1 < \cdots < i_k} f_{i_1\ldots i_k} dx^{i_1} \wedge \cdots \wedge dx^{i_k}$, the exterior derivative is:

$$d\omega = \sum_{i_1 < \cdots < i_k} \sum_{j=1}^n \frac{\partial f_{i_1\ldots i_k}}{\partial x^j} dx^j \wedge dx^{i_1} \wedge \cdots \wedge dx^{i_k}$$

## Properties
- Linearity: $d(\alpha + \beta) = d\alpha + d\beta$
- Leibniz rule: $d(\alpha \wedge \beta) = d\alpha \wedge \beta + (-1)^k \alpha \wedge d\beta$ for k-form $\alpha$
- Nilpotency: $d \circ d = 0$ (i.e., $d^2 = 0$)
- Naturality: $d(f^*\omega) = f^*(d\omega)$ for pullback by a smooth map $f$

## Relation to Vector Calculus
- For a function $f$: $df = \nabla f \cdot d\mathbf{r}$
- For a 1-form $\omega = F_1 dx + F_2 dy + F_3 dz$: $d\omega$ corresponds to $\nabla \times \mathbf{F}$
- For a 2-form $\omega$ in $\mathbb{R}^3$: $d\omega$ corresponds to $\nabla \cdot \mathbf{F}$

## Leads To
- [[df-de-rham-cohomology|de Rham Cohomology]]
- [[df-generalized-stokes-theorem|Generalized Stokes' Theorem]]

## See Also
- [[mc-gradient|Gradient]]
- [[mc-curl|Curl]]
- [[mc-divergence|Divergence]]