---
field: manifold-theory
category: concept
dependencies: [mt-manifolds, mc-line-integrals, mc-surface-integrals]
weight: 3
tags: [manifold-theory, differential-geometry]
---

# Submanifolds

Submanifolds are manifolds that are subsets of other manifolds, inheriting their smooth structure while potentially having lower dimension.

## Definition
A subset $S \subset M$ of a smooth $n$-dimensional manifold $M$ is a $k$-dimensional submanifold if for every point $p \in S$, there exists a chart $(U, \varphi)$ of $M$ such that:
$\varphi(U \cap S) = \varphi(U) \cap (\mathbb{R}^k \times \{0\}^{n-k})$

## Types
- **Embedded submanifolds**: Subsets that are manifolds with the subspace topology
- **Immersed submanifolds**: Images of immersions from another manifold
- **Regular level sets**: Sets of the form $f^{-1}(c)$ where $f: M \to \mathbb{R}^m$ is a submersion

## Examples
- Great circles in a sphere
- Curves in 3D space
- Graphs of smooth functions
- Level surfaces of smooth functions

## Applications
- Representing constraints in mechanical systems
- Studying minimal surfaces
- Defining integration domains

## Leads To
- [[mt-immersions-embeddings|Immersions & Embeddings]]

## See Also
- [[df-integration-of-forms|Integration of Forms]]
- [[df-pullbacks|Pullbacks]]