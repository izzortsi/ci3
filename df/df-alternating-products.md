---
field: differential-forms
category: concept
dependencies: [df-tensor-products]
weight: 3
tags: [differential-forms, algebra]
---

# Alternating Products

Alternating products create antisymmetric multilinear forms, providing the algebraic structure for differential forms.

## Definition
The alternating product (or wedge product) of vectors $v_1, \ldots, v_k$ in a vector space $V$ is a multilinear form that changes sign when any two inputs are swapped.

## Exterior Algebra
The exterior algebra (or Grassmann algebra) $\Lambda(V)$ of a vector space $V$ is:
$$\Lambda(V) = \bigoplus_{k=0}^{\dim V} \Lambda^k(V)$$
where $\Lambda^k(V)$ is the space of alternating $k$-forms.

## Properties
- $\Lambda^0(V) = \mathbb{R}$ (scalars)
- $\Lambda^1(V) = V$ (vectors)
- $\dim \Lambda^k(V) = \binom{\dim V}{k}$
- $v \wedge v = 0$ for any $v \in V$
- $v \wedge w = -w \wedge v$ for $v, w \in V$

## Key Concepts
- Wedge product
- Exterior derivative
- Antisymmetrization
- Determinants as alternating forms

## Leads To
- [[df-k-forms|k-Forms]]

## See Also
- [[df-wedge-product|Wedge Product]]
- [[df-exterior-derivative|Exterior Derivative]]