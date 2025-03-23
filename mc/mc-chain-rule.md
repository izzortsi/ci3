---
field: multivariable-calculus
category: theorem
dependencies: [mc-partial-derivatives]
weight: 3
tags: [multivariable-calculus, calculus]
---

# Chain Rule for Multivariable Functions

The chain rule for multivariable functions extends the single-variable chain rule to functions of several variables, allowing us to compute derivatives of composite functions.

## Statement
Let $f: \mathbb{R}^m \to \mathbb{R}$ be a differentiable function and $\mathbf{g}: \mathbb{R}^n \to \mathbb{R}^m$ be a differentiable vector-valued function. Then the composite function $h = f \circ \mathbf{g}: \mathbb{R}^n \to \mathbb{R}$ is differentiable, and:

$$\frac{\partial h}{\partial x_i} = \sum_{j=1}^m \frac{\partial f}{\partial y_j} \frac{\partial g_j}{\partial x_i}$$

## Matrix Form
Using the Jacobian matrix $J_\mathbf{g}$ of $\mathbf{g}$ and the gradient $\nabla f$, the chain rule can be written as:

$$\nabla h = J_\mathbf{g}^T \nabla f$$

## Examples
1. **Change of variables**: For polar coordinates $(r, \theta)$ related to Cartesian coordinates by $x = r\cos\theta$, $y = r\sin\theta$:
   $$\frac{\partial f}{\partial r} = \frac{\partial f}{\partial x}\frac{\partial x}{\partial r} + \frac{\partial f}{\partial y}\frac{\partial y}{\partial r} = \frac{\partial f}{\partial x}\cos\theta + \frac{\partial f}{\partial y}\sin\theta$$

2. **Composite functions**: For $f(x,y) = x^2 + y^2$ and $x = s+t$, $y = s-t$:
   $$\frac{\partial f}{\partial s} = \frac{\partial f}{\partial x}\frac{\partial x}{\partial s} + \frac{\partial f}{\partial y}\frac{\partial y}{\partial s} = 2x \cdot 1 + 2y \cdot 1 = 2(s+t) + 2(s-t) = 4s$$

## Key Applications
- Coordinate transformations
- Implicit differentiation
- Finding extrema of constrained functions
- Path derivatives and directional derivatives
- Change of variables in optimization

## Relation to Single-Variable Chain Rule
The multivariable chain rule reduces to the familiar single-variable form when $m = n = 1$:
$$\frac{dh}{dx} = \frac{df}{dy} \frac{dy}{dx}$$

## Leads To
- [[mc-gradient|Gradient]]
- [[mc-jacobian-matrix|Jacobian Matrix]]

## See Also
- [[mc-partial-derivatives|Partial Derivatives]]
- [[mc-directional-derivatives|Directional Derivatives]]
