---
field: manifold-theory
category: concept
dependencies: [mt-topology]
weight: 4
tags: [manifold-theory, topology]
---

# Open Sets

Open sets are fundamental objects in topology that don't contain their boundary points, serving as the building blocks for topological spaces.

## Definition
In a topological space $(X, \mathcal{T})$, the sets in $\mathcal{T}$ are called open sets.

In a metric space $(X, d)$, a set $U \subset X$ is open if for every point $p \in U$, there exists $r > 0$ such that the open ball $B(p, r) \subset U$.

## Key Properties
- The empty set and the whole space are open
- Arbitrary unions of open sets are open
- Finite intersections of open sets are open
- The complement of an open set is closed

## Significance
- Define the structure of topological spaces
- Enable the definition of continuity
- Allow for the concept of convergence
- Form the basis for more complex structures

## Leads To
- [[mt-continuity|Continuity]]

## See Also
- [[mt-manifolds|Manifolds]]
- [[mt-charts-atlases|Charts & Atlases]]