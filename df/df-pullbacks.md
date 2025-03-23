---
field: differential-forms
category: operation
dependencies: [df-k-forms, mt-immersions-embeddings]
weight: 3
tags: [differential-forms, operation]
---

# Pullbacks

Pullbacks are a way to transfer differential forms from one manifold to another, preserving their algebraic and geometric properties.

## Definition
For a smooth map $f: M \to N$ between manifolds and a k-form $\omega$ on $N$, the pullback $f^*\omega$ is a k-form on $M$ defined by:

$(f^*\omega)_p(v_1, \ldots, v_k) = \omega_{f(p)}(df_p(v_1), \ldots, df_p(v_k))$

where $df_p: T_pM \to T_{f(p)}N$ is the differential of $f$ at $p$.

## Properties
- Linearity: $f^*(\alpha + \beta) = f^*\alpha + f^*\beta$
- Preserves wedge products: $f^*(\alpha \wedge \beta) = f^*\alpha \wedge f^*\beta$
- Commutes with exterior derivative: $f^*(d\omega) = d(f^*\omega)$
- Functoriality: $(g \circ f)^* = f^* \circ g^*$ for composable maps $f$ and $g$

## Examples
- For a function $g$ on $N$, $f^*g = g \circ f$ (the usual composition)
- For spherical coordinates $\phi: \mathbb{R}^3 \setminus \{0\} \to \mathbb{R}^+ \times S^2$, the pullback $\phi^*$ transforms forms in spherical coordinates to forms in Cartesian coordinates

## Applications
- Coordinate transformations
- Invariant formulations of physical laws
- Relating integration on different manifolds
- Defining characteristic classes

## See Also
- [[df-integration-of-forms|Integration of Forms]]
- [[df-lie-derivatives|Lie Derivatives]]