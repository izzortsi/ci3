---
field: manifold-theory
category: concept
dependencies: [mt-continuity]
weight: 3
tags: [manifold-theory, topology]
---
---

# Homeomorphisms

Homeomorphisms are continuous bijections with continuous inverses, preserving topological properties. They represent the fundamental notion of "topological equivalence."

## Definition
A function $f: X \to Y$ between topological spaces is a homeomorphism if:
1. $f$ is bijective (one-to-one and onto)
2. $f$ is continuous
3. The inverse function $f^{-1}: Y \to X$ is continuous

Two spaces are said to be homeomorphic if there exists a homeomorphism between them.

## Intuition
Homeomorphisms represent the idea of "rubber sheet geometry" - they preserve topological properties while allowing stretching, bending, or twisting (but not tearing or gluing).

## Examples
- The open interval $(0,1)$ is homeomorphic to $\mathbb{R}$
- A coffee mug is homeomorphic to a donut (torus) in the famous topological joke
- The circle $S^1$ is homeomorphic to any simple closed curve

## Topological Invariants
Properties preserved by homeomorphisms include:
- Compactness
- Connectedness
- Path-connectedness
- The number of holes (genus)

## See Also
- [[mt-manifolds|Manifolds]]
- [[mt-immersions-embeddings|Immersions & Embeddings]]