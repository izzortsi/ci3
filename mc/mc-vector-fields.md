---
field: multivariable-calculus
category: concept
dependencies: [mc-vectors]
weight: 4
tags: [multivariable-calculus, vector-calculus]
---

# Vector Fields

A vector field is an assignment of a vector to each point in a subset of Euclidean space, providing a way to model many physical phenomena.

## Definition
A vector field $\mathbf{F}$ on $\mathbb{R}^n$ assigns a vector $\mathbf{F}(\mathbf{p})$ to each point $\mathbf{p}$ in a subset of $\mathbb{R}^n$.

## Examples
- Gravitational field: $\mathbf{F}(\mathbf{r}) = -G\frac{m}{|\mathbf{r}|^2}\frac{\mathbf{r}}{|\mathbf{r}|}$
- Electric field: $\mathbf{E}(\mathbf{r}) = \frac{1}{4\pi\epsilon_0}\frac{q}{|\mathbf{r}|^2}\frac{\mathbf{r}}{|\mathbf{r}|}$
- Velocity field of a fluid: $\mathbf{v}(x,y,z,t)$

## Key Properties
- Can be visualized using field lines or arrows
- Can be conservative (derived from a potential function) or non-conservative
- Can be analyzed using divergence and curl

## Leads To
- [[mc-line-integrals|Line Integrals]]
- [[mc-surface-integrals|Surface Integrals]]
- [[mc-divergence|Divergence]]
- [[mc-curl|Curl]]
- [[mt-tangent-spaces|Tangent Spaces]]

## See Also
- [[df-1-forms|1-Forms]]
- [[df-k-forms|k-Forms]]