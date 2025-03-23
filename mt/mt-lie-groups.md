---
field: manifold-theory
category: concept
dependencies: [mt-smooth-manifolds]
weight: 3
tags: [manifold-theory, group-theory]
---

# Lie Groups

Lie groups are groups that are also differentiable manifolds, with smooth group operations, combining algebraic structure with geometric properties.

## Definition
A Lie group $G$ is a smooth manifold with a group structure such that:
1. The multiplication map $m: G \times G \to G$ defined by $m(g, h) = g \cdot h$ is smooth
2. The inversion map $i: G \to G$ defined by $i(g) = g^{-1}$ is smooth

## Examples
- General linear group $GL(n, \mathbb{R})$ of invertible $n \times n$ matrices
- Special orthogonal group $SO(n)$ of rotations in $\mathbb{R}^n$
- Unitary group $U(n)$ of unitary matrices
- Heisenberg group representing quantum mechanical symmetries

## Key Concepts
- Lie algebras (tangent space at the identity)
- Exponential map
- One-parameter subgroups
- Adjoint representation

## Applications
- Quantum mechanics (symmetry groups)
- Gauge theories in physics
- Robotics (rotation and translation groups)
- Crystallography (symmetry groups)

## Leads To
- [[df-lie-derivatives|Lie Derivatives]]

## See Also
- [[mt-tangent-spaces|Tangent Spaces]]
- [[df-connections|Connections]]