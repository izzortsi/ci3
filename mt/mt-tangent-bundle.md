---
field: manifold-theory
category: concept
dependencies: [mt-tangent-spaces]
weight: 3
tags: [manifold-theory, differential-geometry]
---

# Tangent Bundle

The tangent bundle is the union of all tangent spaces of a manifold, forming a manifold itself and providing the natural setting for dynamics on the manifold.

## Definition
The tangent bundle of a smooth $n$-dimensional manifold $M$ is:
$TM = \bigcup_{p \in M} \{p\} \times T_pM$

It comes with a natural projection map $\pi: TM \to M$ given by $\pi(p, v) = p$.

## Properties
- $TM$ is a $2n$-dimensional smooth manifold
- $TM$ is a vector bundle of rank $n$ over $M$
- Local coordinates on $TM$ are $(x^1, \ldots, x^n, v^1, \ldots, v^n)$
- Vector fields on $M$ correspond to sections of $TM$

## Examples
- The tangent bundle of $\mathbb{R}^n$ is trivial: $T\mathbb{R}^n \cong \mathbb{R}^n \times \mathbb{R}^n$
- The tangent bundle of the circle $S^1$ is the cylinder $S^1 \times \mathbb{R}$
- The tangent bundle of the sphere $S^2$ is non-trivial (no global frame exists)

## Applications
- Phase spaces in Hamiltonian mechanics
- Defining connections and parallel transport
- Foundation for Riemannian geometry

## Leads To
- [[df-k-forms|k-Forms]]
- [[df-connections|Connections]]

## See Also
- [[df-dual-space|Dual Space]]
- [[df-pullbacks|Pullbacks]]