---
field: differential-forms
category: concept
dependencies: [df-alternating-products, df-1-forms, mt-tangent-bundle, mt-smooth-manifolds, mc-surface-integrals]
weight: 4
tags: [differential-forms, fundamental]
---

# k-Forms

k-Forms are antisymmetric tensor fields of rank k that can be integrated over k-dimensional surfaces, generalizing the concept of differential forms.

## Definition
A differential k-form on a manifold $M$ is a smooth assignment to each point $p \in M$ of an alternating multilinear map:
$$\omega_p: \underbrace{T_pM \times \cdots \times T_pM}_{k \text{ times}} \to \mathbb{R}$$

## Local Representation
In local coordinates, a k-form can be written as:
$$\omega = \sum_{i_1 < \cdots < i_k} f_{i_1\ldots i_k}(x) dx^{i_1} \wedge \cdots \wedge dx^{i_k}$$

## Examples
- 0-forms are functions
- 1-forms as described in [[df-1-forms]]
- 2-forms represent area elements (e.g., $dx \wedge dy$)
- 3-forms represent volume elements (e.g., $dx \wedge dy \wedge dz$)

## Key Properties
- Integration over k-dimensional submanifolds
- Wedge product producing higher-degree forms
- Exterior derivative extending to all k-forms
- Pullback under smooth maps

## Leads To
- [[df-wedge-product|Wedge Product]]
- [[df-exterior-derivative|Exterior Derivative]]
- [[df-pullbacks|Pullbacks]]
- [[df-hodge-star|Hodge Star]]
- [[df-integration-of-forms|Integration of Forms]]
- [[df-lie-derivatives|Lie Derivatives]]

## See Also
- [[df-de-rham-cohomology|de Rham Cohomology]]
- [[mt-tangent-bundle|Tangent Bundle]]