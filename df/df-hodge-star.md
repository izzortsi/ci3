---
field: differential-forms
category: operation
dependencies: [df-k-forms]
weight: 2
tags: [differential-forms, operation]
---

# Hodge Star

The Hodge star is an operator mapping k-forms to (n-k)-forms using a metric, providing a way to relate differential forms of complementary degrees.

## Definition
On an n-dimensional oriented Riemannian manifold $(M, g)$, the Hodge star operator $\star: \Omega^k(M) \to \Omega^{n-k}(M)$ is defined by the relation:

$\alpha \wedge \star \beta = \langle \alpha, \beta \rangle \text{vol}_g$

for any k-forms $\alpha$ and $\beta$, where $\langle \alpha, \beta \rangle$ is the inner product induced by the metric and $\text{vol}_g$ is the volume form.

## Properties
- $\star \star \alpha = (-1)^{k(n-k)} s \alpha$ where $s = \pm 1$ depends on the signature of the metric
- $\star 1 = \text{vol}_g$ (the volume form)
- If $\{e^i\}$ is an orthonormal basis of 1-forms, then $\star(e^{i_1} \wedge \cdots \wedge e^{i_k}) = \pm e^{j_1} \wedge \cdots \wedge e^{j_{n-k}}$ where $\{j_1, \ldots, j_{n-k}\}$ is the complement of $\{i_1, \ldots, i_k\}$

## Applications
- Defining codifferential operator $\delta = \pm \star d \star$
- Formulating electromagnetic theory (relating electric and magnetic fields)
- Expressing Hodge decomposition
- Defining Laplacian on forms: $\Delta = d\delta + \delta d$

## Examples
- In $\mathbb{R}^3$ with Euclidean metric: $\star dx = dy \wedge dz$, $\star dy = dz \wedge dx$, $\star dz = dx \wedge dy$
- In Minkowski spacetime: $\star dt = dx \wedge dy \wedge dz$

## See Also
- [[df-de-rham-cohomology|de Rham Cohomology]]
- [[df-integration-of-forms|Integration of Forms]]