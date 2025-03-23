---
field: manifold-theory
category: concept
dependencies: [mt-submanifolds, mc-jacobian-matrix]
weight: 3
tags: [manifold-theory, differential-geometry]
---

# Immersions & Embeddings

Immersions and embeddings are maps between manifolds that preserve local or global structure, fundamental for understanding how manifolds can be realized within larger spaces.

## Definitions
- An **immersion** $f: M \to N$ is a smooth map whose derivative $df_p: T_pM \to T_{f(p)}N$ is injective at every point $p \in M$.
- An **embedding** is an immersion that is also a homeomorphism onto its image.

## Key Properties
- Immersions preserve tangent vectors but may have self-intersections
- Embeddings represent a manifold faithfully within a larger space
- The Whitney embedding theorem guarantees that any $n$-dimensional manifold can be embedded in $\mathbb{R}^{2n}$

## Examples
- The figure-eight curve is an immersion but not an embedding of $S^1$ into $\mathbb{R}^2$
- The standard inclusion of a sphere $S^2$ into $\mathbb{R}^3$ is an embedding
- The Klein bottle can be immersed but not embedded in $\mathbb{R}^3$

## Applications
- Studying intrinsic vs. extrinsic geometry
- Visualizing abstract manifolds
- Understanding knots and links

## See Also
- [[df-pullbacks|Pullbacks]]
- [[mt-smooth-manifolds|Smooth Manifolds]]