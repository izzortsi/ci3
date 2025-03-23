---
field: manifold-theory
category: concept
dependencies: [mt-manifolds, mc-change-of-variables]
weight: 4
tags: [manifold-theory, structure]
---

# Charts & Atlases

Charts and atlases provide the coordinate systems for manifolds, allowing us to perform calculations and apply calculus on curved spaces.

## Definitions
- A **chart** (or coordinate system) on a manifold $M$ is a pair $(U, \varphi)$ where $U \subset M$ is an open set and $\varphi: U \to \varphi(U) \subset \mathbb{R}^n$ is a homeomorphism.
- An **atlas** on $M$ is a collection of charts $\{(U_\alpha, \varphi_\alpha)\}$ such that $\bigcup_\alpha U_\alpha = M$.

## Transition Maps
For overlapping charts $(U_\alpha, \varphi_\alpha)$ and $(U_\beta, \varphi_\beta)$, the transition map is:
$\varphi_\beta \circ \varphi_\alpha^{-1}: \varphi_\alpha(U_\alpha \cap U_\beta) \to \varphi_\beta(U_\alpha \cap U_\beta)$

The smoothness of these transition maps determines the differentiability structure of the manifold.

## Examples
- Stereographic projection for the sphere
- Latitude and longitude on Earth
- Local parameterizations of surfaces

## Leads To
- [[mt-smooth-manifolds|Smooth Manifolds]]
- [[mt-partition-of-unity|Partition of Unity]]

## See Also
- [[mc-change-of-variables|Change of Variables]]
- [[df-pullbacks|Pullbacks]]