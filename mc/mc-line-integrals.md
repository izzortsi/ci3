---
field: multivariable-calculus
category: concept
dependencies: [mc-vector-fields]
weight: 3
tags: [multivariable-calculus, integration]
---

# Line Integrals

Line integrals evaluate a function along a curve in a scalar or vector field, generalizing the concept of integration to paths in higher-dimensional spaces.

## Types
1. Line integral with respect to arc length: $\int_C f(x,y,z) \, ds$
2. Line integral with respect to coordinates: $\int_C f(x,y,z) \, dx + g(x,y,z) \, dy + h(x,y,z) \, dz$
3. Line integral of a vector field: $\int_C \mathbf{F} \cdot d\mathbf{r}$

## Key Properties
- Path-dependent for non-conservative fields
- Path-independent for conservative fields (gradient fields)
- Connected to work done by a force along a path

## Applications
- Work calculation in physics
- Circulation in fluid dynamics
- Electric potential in electromagnetism

## Leads To
- [[mc-green-theorem|Green's Theorem]]
- [[mt-submanifolds|Submanifolds]]
- [[df-1-forms|1-Forms]]

## See Also
- [[mc-stokes-theorem|Stokes' Theorem]]
- [[df-integration-of-forms|Integration of Forms]]