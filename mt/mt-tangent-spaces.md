---
field: manifold-theory
category: concept
dependencies: [mt-smooth-manifolds, mc-partial-derivatives, mc-gradient, mc-directional-derivatives, mc-vector-fields]
weight: 4
tags: [manifold-theory, differential-geometry]
---

# Tangent Spaces

Tangent spaces are vector spaces of possible directions of curves passing through a point on a manifold, generalizing the concept of tangent planes to surfaces.

## Definition
The tangent space $T_pM$ at a point $p$ on a smooth manifold $M$ can be defined in several equivalent ways:
1. As equivalence classes of curves through $p$
2. As derivations (directional derivatives) at $p$
3. Via the pushforward of a chart

## Formal Definition
For a smooth curve $\gamma: (-\epsilon, \epsilon) \to M$ with $\gamma(0) = p$, the tangent vector $\gamma'(0)$ at $p$ is the equivalence class of all curves with the same derivative at $p$.

## Coordinate Representation
In local coordinates $(x^1, \ldots, x^n)$, a tangent vector $v \in T_pM$ can be expressed as:
$v = \sum_{i=1}^{n} v^i \frac{\partial}{\partial x^i}\bigg|_p$

## Applications
- Defining vector fields on manifolds
- Foundation for differential geometry
- Basis for the definition of differential forms
- Essential for defining manifold structures on infinite-dimensional spaces

## Leads To
- [[mt-tangent-bundle|Tangent Bundle]]
- [[df-1-forms|1-Forms]]

## See Also
- [[mc-directional-derivatives|Directional Derivatives]]
- [[df-lie-derivatives|Lie Derivatives]]