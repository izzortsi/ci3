---
field: manifold-theory
category: fundamental
dependencies: [mc-vectors]
weight: 5
tags: [manifold-theory, topology]
---

# Metric Spaces

Metric spaces are sets equipped with a notion of distance between elements, providing the mathematical foundation for studying proximity and continuity.

## Definition
A metric space is a pair $(X, d)$ where $X$ is a set and $d: X \times X \to \mathbb{R}$ is a function (metric) satisfying:
1. $d(x, y) \geq 0$ for all $x, y \in X$ (non-negativity)
2. $d(x, y) = 0$ if and only if $x = y$ (identity of indiscernibles)
3. $d(x, y) = d(y, x)$ for all $x, y \in X$ (symmetry)
4. $d(x, z) \leq d(x, y) + d(y, z)$ for all $x, y, z \in X$ (triangle inequality)

## Examples
- $\mathbb{R}^n$ with Euclidean distance
- Function spaces with various norms
- Discrete metric spaces

## Key Concepts
- Open and closed balls
- Convergence of sequences
- Completeness and Cauchy sequences
- Compactness

## Leads To
- [[mt-topology|Topology]]

## See Also
- [[mt-open-sets|Open Sets]]
- [[mt-continuity|Continuity]]