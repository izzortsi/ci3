---
field: differential-forms
category: concept
dependencies: [df-linear-algebra]
weight: 4
tags: [differential-forms, algebra]
---

# Tensor Products

Tensor products are algebraic constructions creating vector spaces from other vector spaces, essential for building the mathematical machinery of differential forms.

## Definition
For vector spaces $V$ and $W$, the tensor product $V \otimes W$ is a vector space with a bilinear map $\otimes: V \times W \to V \otimes W$ that is universal in the sense that any bilinear map $f: V \times W \to Z$ factors uniquely through $V \otimes W$.

## Properties
- Dimension: $\dim(V \otimes W) = \dim(V) \cdot \dim(W)$
- Non-commutativity: $V \otimes W \cong W \otimes V$ but not equal
- Associativity: $(U \otimes V) \otimes W \cong U \otimes (V \otimes W)$
- Distributivity: $U \otimes (V \oplus W) \cong (U \otimes V) \oplus (U \otimes W)$

## Tensor Algebra
The tensor algebra $T(V)$ of a vector space $V$ is the direct sum:
$$T(V) = \bigoplus_{k=0}^{\infty} V^{\otimes k}$$
where $V^{\otimes k}$ is the $k$-fold tensor product of $V$.

## Applications
- Multilinear algebra
- Physics (relativity, quantum mechanics)
- Differential geometry
- Representation theory

## Leads To
- [[df-alternating-products|Alternating Products]]

## See Also
- [[df-dual-space|Dual Space]]
- [[df-k-forms|k-Forms]]