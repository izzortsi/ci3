---
field: differential-forms
category: concept
dependencies: [df-linear-algebra]
weight: 4
tags: [differential-forms, algebra]
---

# Dual Space

The dual space of a vector space is the vector space of all linear functionals on the original space, forming the foundation for differential forms.

## Definition
For a vector space $V$ over a field $F$, the dual space $V^*$ is the set of all linear maps $f: V \to F$, which forms a vector space under pointwise addition and scalar multiplication.

## Properties
- Dimension: $\dim(V^*) = \dim(V)$ for finite-dimensional spaces
- Double dual: $(V^*)^* \cong V$ for finite-dimensional spaces
- Natural pairing: $\langle \cdot, \cdot \rangle: V^* \times V \to F$ given by $\langle f, v \rangle = f(v)$
- Dual basis: If $\{e_i\}$ is a basis for $V$, then the dual basis $\{e^i\}$ in $V^*$ satisfies $e^i(e_j) = \delta^i_j$

## Key Concepts
- Linear functionals
- Dual maps
- Annihilators
- Reflexivity

## Applications
- Defining covectors in differential geometry
- Formulating conservation laws in physics
- Constructing differential forms
- Representing observables in quantum mechanics

## Leads To
- [[df-1-forms|1-Forms]]

## See Also
- [[mt-tangent-spaces|Tangent Spaces]]
- [[df-tensor-products|Tensor Products]]