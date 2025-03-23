---
field: multivariable-calculus
category: fundamental
dependencies: [mc-vectors]
weight: 4
tags: [multivariable-calculus, calculus]
---

# Partial Derivatives

Partial derivatives are derivatives with respect to one variable while holding others constant, extending the concept of derivatives to functions of several variables.

## Definition
For a function $f(x_1, x_2, ..., x_n)$, the partial derivative with respect to $x_i$ is:

$$\frac{\partial f}{\partial x_i} = \lim_{h \to 0} \frac{f(x_1, ..., x_i + h, ..., x_n) - f(x_1, ..., x_i, ..., x_n)}{h}$$

## Key Properties
- Measures rate of change in one direction
- Can be computed by treating other variables as constants
- Higher-order partial derivatives require careful attention to order of differentiation

## Leads To
- [[mc-gradient|Gradient]]
- [[mc-directional-derivatives|Directional Derivatives]]
- [[mc-jacobian-matrix|Jacobian Matrix]]
- [[mt-tangent-spaces|Tangent Spaces]]

## See Also
- [[mc-chain-rule|Chain Rule for Multivariable Functions]]