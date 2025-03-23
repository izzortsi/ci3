---
field: multivariable-calculus
category: technique
dependencies: [mc-multiple-integrals, mc-jacobian-matrix]
weight: 3
tags: [multivariable-calculus, integration]
---

# Change of Variables

Change of variables is a technique for evaluating multiple integrals using coordinate transformations, generalizing the substitution rule from single-variable calculus.

## Formula
For a transformation $\mathbf{T}: U \to V$ and a function $f: V \to \mathbb{R}$:

$$\int_V f(\mathbf{y}) \, d\mathbf{y} = \int_U f(\mathbf{T}(\mathbf{x})) \, |\det J_{\mathbf{T}}(\mathbf{x})| \, d\mathbf{x}$$

where $J_{\mathbf{T}}$ is the Jacobian matrix of $\mathbf{T}$.

## Common Transformations
- Polar coordinates: $(r, \theta) \to (r\cos\theta, r\sin\theta)$
- Spherical coordinates: $(r, \theta, \phi) \to (r\sin\phi\cos\theta, r\sin\phi\sin\theta, r\cos\phi)$
- Cylindrical coordinates: $(r, \theta, z) \to (r\cos\theta, r\sin\theta, z)$

## Applications
- Simplifying complicated integrals
- Adapting to the geometry of the problem
- Handling regions with curved boundaries

## Leads To
- [[mt-charts-atlases|Charts & Atlases]]

## See Also
- [[mt-smooth-manifolds|Smooth Manifolds]]
- [[df-pullbacks|Pullbacks]]