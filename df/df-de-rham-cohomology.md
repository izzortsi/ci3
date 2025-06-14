---
field: differential-forms
category: concept
dependencies: [df-exterior-derivative]
weight: 2
tags: [differential-forms, topology]
---

# de Rham Cohomology

de Rham cohomology is an algebraic structure capturing the topology of differential forms, providing a bridge between differential geometry and algebraic topology.

## Definition
For a smooth manifold $M$, the k-th de Rham cohomology group is:

$H^k_{dR}(M) = \frac{\ker(d: \Omega^k(M) \to \Omega^{k+1}(M))}{\text{im}(d: \Omega^{k-1}(M) \to \Omega^k(M))}$

where $\Omega^k(M)$ is the space of k-forms on $M$.

## Interpretation
- Elements of $H^k_{dR}(M)$ are equivalence classes of closed k-forms (forms $\omega$ with $d\omega = 0$), where two forms are equivalent if they differ by an exact form ($d\alpha$ for some $(k-1)$-form $\alpha$).
- $H^k_{dR}(M)$ measures the "k-dimensional holes" in the manifold.

## de Rham's Theorem
The de Rham cohomology is isomorphic to the singular cohomology with real coefficients:

$H^k_{dR}(M) \cong H^k(M; \mathbb{R})$

## Examples
- For a connected manifold: $H^0_{dR}(M) \cong \mathbb{R}$ (constant functions)
- For the circle $S^1$: $H^1_{dR}(S^1) \cong \mathbb{R}$ (generated by $d\theta$)
- For the torus $T^2$: $H^1_{dR}(T^2) \cong \mathbb{R}^2$, $H^2_{dR}(T^2) \cong \mathbb{R}$

## Applications
- Investigating topological properties of manifolds
- Classification of manifolds
- Morse theory
- Mathematical physics (gauge theory)

## See Also
- [[df-generalized-stokes-theorem|Generalized Stokes' Theorem]]
- [[df-integration-of-forms|Integration of Forms]]