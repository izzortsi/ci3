---
field: differential-forms
category: operation
dependencies: [df-k-forms, mt-lie-groups]
weight: 2
tags: [differential-forms, operation]
---

# Lie Derivatives

Lie derivatives describe how tensor fields change along the flow of a vector field, providing a coordinate-independent way to take directional derivatives on manifolds.

## Definition
For a tensor field $T$ and a vector field $X$ on a manifold $M$, the Lie derivative $\mathcal{L}_X T$ is defined as:

$\mathcal{L}_X T = \lim_{t \to 0} \frac{\phi_{-t}^* T - T}{t}$

where $\phi_t$ is the flow of $X$ and $\phi_t^*$ is the pullback by $\phi_t$.

## Properties
- Commutes with contractions and tensor products
- For functions $f$: $\mathcal{L}_X f = X(f)$ (directional derivative)
- For vector fields $Y$: $\mathcal{L}_X Y = [X, Y]$ (Lie bracket)
- For differential forms $\omega$: $\mathcal{L}_X \omega = d(i_X \omega) + i_X(d\omega)$ (Cartan's magic formula)
- Leibniz rule: $\mathcal{L}_X(T \otimes S) = \mathcal{L}_X T \otimes S + T \otimes \mathcal{L}_X S$

## Examples
- Rotation vector field in $\mathbb{R}^2$: $X = -y\frac{\partial}{\partial x} + x\frac{\partial}{\partial y}$
  - $\mathcal{L}_X f$ measures how $f$ changes under rotation
- For a 1-form $\alpha$ and vector field $X$: $(\mathcal{L}_X \alpha)(Y) = X(\alpha(Y)) - \alpha([X, Y])$

## Applications
- Symmetries and conservation laws
- Geometric flows
- Defining invariant quantities
- Noether's theorem in physics

## See Also
- [[df-connections|Connections]]
- [[df-pullbacks|Pullbacks]]