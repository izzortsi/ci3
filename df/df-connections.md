---
field: differential-forms
category: concept
dependencies: [mt-tangent-bundle]
weight: 2
tags: [differential-forms, differential-geometry]
---

# Connections

Connections allow comparison of vectors in different tangent spaces, providing a way to differentiate vector fields along curves and define parallel transport on manifolds.

## Definition
An affine connection on a manifold $M$ is a bilinear map $\nabla: \mathfrak{X}(M) \times \mathfrak{X}(M) \to \mathfrak{X}(M)$, where $\mathfrak{X}(M)$ is the space of vector fields, such that:
1. $\nabla_{fX} Y = f \nabla_X Y$ for any function $f$
2. $\nabla_X (fY) = X(f)Y + f\nabla_X Y$ (Leibniz rule)

The value $\nabla_X Y$ is called the covariant derivative of $Y$ along $X$.

## Local Representation
In local coordinates, a connection is specified by Christoffel symbols $\Gamma^k_{ij}$:

$\nabla_{\frac{\partial}{\partial x^i}} \frac{\partial}{\partial x^j} = \sum_k \Gamma^k_{ij} \frac{\partial}{\partial x^k}$

## Types of Connections
- Levi-Civita connection: The unique torsion-free connection compatible with a Riemannian metric
- Ehresmann connection: A geometric approach using horizontal and vertical spaces
- Principal connections: Connections on principal bundles

## Applications
- Parallel transport
- Geodesics
- Curvature
- General relativity
- Gauge theory

## Leads To
- [[df-curvature|Curvature]]

## See Also
- [[mt-tangent-bundle|Tangent Bundle]]
- [[df-lie-derivatives|Lie Derivatives]]