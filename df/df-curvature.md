---
field: differential-forms
category: concept
dependencies: [df-connections]
weight: 1
tags: [differential-forms, differential-geometry]
---

# Curvature

Curvature measures the local deviation of a manifold from being flat, quantifying how tangent spaces twist and turn relative to each other.

## Definition
For a connection $\nabla$ on a manifold, the curvature is a tensor $R$ defined by:

$R(X, Y)Z = \nabla_X \nabla_Y Z - \nabla_Y \nabla_X Z - \nabla_{[X, Y]} Z$

for vector fields $X$, $Y$, and $Z$.

## Types of Curvature
- **Riemann curvature tensor**: The full curvature tensor of a Riemannian manifold
- **Sectional curvature**: Curvature of 2-dimensional sections
- **Ricci curvature**: Contraction of the Riemann tensor
- **Scalar curvature**: Trace of the Ricci tensor

## Local Representation
In coordinates, the components of the Riemann tensor are:

$R^l_{ijk} = \partial_i \Gamma^l_{jk} - \partial_j \Gamma^l_{ik} + \Gamma^m_{jk} \Gamma^l_{im} - \Gamma^m_{ik} \Gamma^l_{jm}$

## Geometric Interpretation
- Positive curvature: sphere-like (converging geodesics)
- Zero curvature: flat (parallel geodesics)
- Negative curvature: saddle-like (diverging geodesics)

## Applications
- General relativity (spacetime curvature represents gravity)
- Riemannian geometry
- Comparison theorems
- Gauss-Bonnet theorem
- Chern-Gauss-Bonnet formula

## See Also
- [[mt-smooth-manifolds|Smooth Manifolds]]
- [[df-connections|Connections]]