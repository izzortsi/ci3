---
field: multivariable-calculus
category: concept
dependencies: [mc-vectors]
weight: 4
tags: [multivariable-calculus, integration]
---

# Multiple Integrals

Multiple integrals generalize the definite integral to functions of more than one variable, allowing integration over regions in higher-dimensional spaces.

## Definition
For a function $f: \mathbb{R}^n \to \mathbb{R}$ and a region $D \subset \mathbb{R}^n$:

- Double integral: $\iint_D f(x,y) \, dA$
- Triple integral: $\iiint_D f(x,y,z) \, dV$
- General case: $\int_D f(\mathbf{x}) \, d\mathbf{x}$

## Key Properties
- Can be evaluated using iterated integrals (Fubini's theorem)
- Represent volumes, masses, centers of mass, moments of inertia
- Require careful handling of integration bounds

## Applications
- Computing volumes and masses
- Probability distributions
- Physics (electromagnetism, fluid dynamics)

## Leads To
- [[mc-change-of-variables|Change of Variables]]
- [[mc-surface-integrals|Surface Integrals]]

## See Also
- [[df-integration-of-forms|Integration of Forms]]
- [[mt-partition-of-unity|Partition of Unity]]