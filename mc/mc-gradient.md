---
field: multivariable-calculus
category: concept
dependencies: [mc-partial-derivatives]
weight: 4
tags: [multivariable-calculus, vector-calculus]
---

# Gradient

The gradient is a vector field that points in the direction of greatest rate of increase of a function. It generalizes the concept of derivative to functions of several variables.

## Definition
For a differentiable function $f: \mathbb{R}^n \to \mathbb{R}$, the gradient is the vector:

$$\nabla f = \left(\frac{\partial f}{\partial x_1}, \frac{\partial f}{\partial x_2}, \ldots, \frac{\partial f}{\partial x_n}\right)$$

## Key Properties
- The gradient is perpendicular to level curves/surfaces
- The magnitude of the gradient represents the maximum rate of change
- The gradient points in the direction of steepest ascent
- The negative gradient points in the direction of steepest descent

## Applications
- Optimization algorithms (gradient descent)
- Finding normal vectors to level surfaces
- Potential theory in physics

## Leads To
- [[mc-directional-derivatives|Directional Derivatives]]
- [[mt-tangent-spaces|Tangent Spaces]]

## See Also
- [[mc-vector-fields|Vector Fields]]
- [[df-1-forms|1-Forms]]