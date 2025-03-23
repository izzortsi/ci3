---
field: manifold-theory
category: technique
dependencies: [mt-charts-atlases]
weight: 3
tags: [manifold-theory, analysis]
---

# Partition of Unity

Partition of unity is a collection of functions allowing global constructions from local definitions, essential for patching together local objects on a manifold.

## Definition
A partition of unity on a manifold $M$ is a collection of smooth functions $\{\rho_\alpha: M \to [0,1]\}$ such that:
1. Each $\rho_\alpha$ has compact support contained in some chart domain
2. The collection of supports forms a locally finite cover of $M$
3. For every point $p \in M$, $\sum_\alpha \rho_\alpha(p) = 1$

## Properties
- Always exists on paracompact manifolds (including all Hausdorff manifolds with countable basis)
- Allows for "gluing" of local constructions
- Enables extension of local objects to global ones

## Applications
- Defining global differential forms from local ones
- Constructing Riemannian metrics
- Proving the existence of global smooth functions with specific properties
- Averaging local structures to get global structures

## See Also
- [[mt-charts-atlases|Charts & Atlases]]
- [[df-integration-of-forms|Integration of Forms]]