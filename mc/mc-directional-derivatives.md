---
field: multivariable-calculus
category: concept
dependencies: [mc-partial-derivatives, mc-gradient]
weight: 3
tags: [multivariable-calculus, vector-calculus]
---

# Directional Derivatives

Directional derivatives represent the rate of change of a function in any direction, generalizing partial derivatives which only consider changes along coordinate axes.

## Definition
For a differentiable function $f: \mathbb{R}^n \to \mathbb{R}$ and a unit vector $\mathbf{v}$, the directional derivative is:

$$D_{\mathbf{v}}f = \nabla f \cdot \mathbf{v}$$

## Key Properties
- Can be computed using the dot product of the gradient and the direction vector
- Partial derivatives are special cases of directional derivatives along coordinate axes
- Maximum value occurs in the direction of the gradient

## Applications
- Analyzing rates of change in physics problems
- Determining behavior of functions in arbitrary directions
- Optimization in machine learning algorithms

## Leads To
- [[mt-tangent-spaces|Tangent Spaces]]

## See Also
- [[mc-vector-fields|Vector Fields]]
- [[df-1-forms|1-Forms]]