---
field: manifold-theory
category: fundamental
dependencies: [mt-topology]
weight: 5
tags: [manifold-theory, fundamental]
---

# Manifolds

Manifolds are topological spaces that locally resemble Euclidean space, allowing us to extend calculus to curved spaces.

## Definition
An $n$-dimensional manifold is a topological space $M$ such that:
1. $M$ is a Hausdorff space
2. $M$ has a countable basis
3. Around every point $p \in M$, there exists an open neighborhood $U$ that is homeomorphic to an open subset of $\mathbb{R}^n$

## Intuition
- A curve is a 1-dimensional manifold
- A surface is a 2-dimensional manifold
- Manifolds allow us to generalize "flatness" to curved spaces

## Examples
- The circle $S^1$ and sphere $S^2$
- The torus $T^2$
- Projective spaces $\mathbb{RP}^n$ and $\mathbb{CP}^n$
- Lie groups such as $SO(3)$

## Key Concepts
- Local coordinates via charts
- Transition functions between charts
- Tangent spaces and vector fields
- Differential forms and integration

## Leads To
- [[mt-charts-atlases|Charts & Atlases]]
- [[mt-submanifolds|Submanifolds]]
- [[df-integration-of-forms|Integration of Forms]]

## See Also
- [[mt-smooth-manifolds|Smooth Manifolds]]
- [[mt-tangent-spaces|Tangent Spaces]]