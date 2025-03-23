---
field: manifold-theory
category: concept
dependencies: [mt-open-sets]
weight: 4
tags: [manifold-theory, topology]
---

# Continuity

Continuity describes functions that preserve closeness between points, a fundamental concept in topology that generalizes the intuitive notion of functions without "jumps" or "breaks."

## Definition
A function $f: X \to Y$ between topological spaces is continuous if the preimage of every open set in $Y$ is open in $X$.

Equivalently, for every open set $V \subset Y$, the set $f^{-1}(V) = \{x \in X : f(x) \in V\}$ is open in $X$.

## Alternative Definitions
- Sequential continuity: If $x_n \to x$ implies $f(x_n) \to f(x)$
- $\epsilon$-$\delta$ definition (in metric spaces): For every $\epsilon > 0$, there exists $\delta > 0$ such that $d_X(x, y) < \delta$ implies $d_Y(f(x), f(y)) < \epsilon$

## Key Properties
- Composition of continuous functions is continuous
- Continuous image of a connected space is connected
- Continuous image of a compact space is compact

## Leads To
- [[mt-homeomorphisms|Homeomorphisms]]

## See Also
- [[mt-manifolds|Manifolds]]
- [[mt-smooth-manifolds|Smooth Manifolds]]