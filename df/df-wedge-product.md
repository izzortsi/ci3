---
field: differential-forms
category: operation
dependencies: [df-k-forms]
weight: 3
tags: [differential-forms, operation]
---

# Wedge Product

The wedge product is an operation combining differential forms of different degrees, providing a way to build higher-degree forms from lower-degree ones.

## Definition
For a p-form $\alpha$ and a q-form $\beta$, their wedge product $\alpha \wedge \beta$ is a (p+q)-form defined by:

$$(\alpha \wedge \beta)(X_1, \ldots, X_{p+q}) = \frac{1}{p!q!} \sum_{\sigma} \text{sgn}(\sigma) \alpha(X_{\sigma(1)}, \ldots, X_{\sigma(p)}) \beta(X_{\sigma(p+1)}, \ldots, X_{\sigma(p+q)})$$

where the sum is over all permutations $\sigma$ of $\{1, \ldots, p+q\}$.

## Properties
- Bilinearity: $(\alpha + \gamma) \wedge \beta = \alpha \wedge \beta + \gamma \wedge \beta$
- Associativity: $(\alpha \wedge \beta) \wedge \gamma = \alpha \wedge (\beta \wedge \gamma)$
- Anticommutativity: $\alpha \wedge \beta = (-1)^{pq} \beta \wedge \alpha$ for p-form $\alpha$ and q-form $\beta$
- Product rule: $d(\alpha \wedge \beta) = d\alpha \wedge \beta + (-1)^p \alpha \wedge d\beta$ for p-form $\alpha$

## Examples
- $dx \wedge dy$ represents an oriented area element in the xy-plane
- $dx \wedge dy \wedge dz$ represents an oriented volume element in 3D space
- For 1-forms $\alpha = f_i dx^i$ and $\beta = g_j dx^j$, we have $\alpha \wedge \beta = (f_i g_j - f_j g_i) dx^i \wedge dx^j$

## Applications
- Defining volume elements
- Formulating field theories in physics
- Expressing conservation laws

## See Also
- [[df-exterior-derivative|Exterior Derivative]]
- [[df-k-forms|k-Forms]]