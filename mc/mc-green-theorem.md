---
field: multivariable-calculus
category: theorem
dependencies: [mc-line-integrals]
weight: 2
tags: [multivariable-calculus, theorem]
---

# Green's Theorem

Green's Theorem relates a line integral around a simple closed curve to a double integral over the region it encloses, connecting the concepts of circulation and curl.

## Statement
For a vector field $\mathbf{F} = (P, Q)$ with continuous partial derivatives on a region $D$ with positively oriented, piecewise smooth boundary curve $C$:

$$\oint_C P \, dx + Q \, dy = \iint_D \left(\frac{\partial Q}{\partial x} - \frac{\partial P}{\partial y}\right) \, dA$$

## Key Insights
- Connects boundary behavior (line integral) with interior properties (double integral)
- Special case of Stokes' theorem in 2D
- Can be interpreted as relating circulation to curl

## Applications
- Computing areas of regions
- Simplifying complex line integrals
- Conservation laws in physics

## Leads To
- [[df-generalized-stokes-theorem|Generalized Stokes' Theorem]]

## See Also
- [[mc-stokes-theorem|Stokes' Theorem]]
- [[mc-divergence-theorem|Divergence Theorem]]
- [[df-exterior-derivative|Exterior Derivative]]