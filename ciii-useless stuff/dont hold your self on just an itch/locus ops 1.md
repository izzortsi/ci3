# Operations on curve loci unite geometry and machine learning

The mathematical framework for operations on curve loci extends from classical differential geometry to modern applications in neural network compression, revealing deep connections between abstract mathematics and practical optimization problems. This research explores eight key aspects of curve loci operations, from rigorous mathematical foundations to surprising applications in large language model sparsification.

## What constitutes the "locus of curves" - spaces, families, and moduli

The phrase "locus of curves" admits multiple rigorous mathematical interpretations, each serving different theoretical and computational purposes. For a convex closed plane curve $\gamma$ containing another closed curve H, the most fundamental interpretation is the **configuration space**: 
$$C = \{(\gamma, \mathcal{H}_p) : \gamma \text{ convex closed curve}; \, \mathcal{H}_p \text{ closed curve}; \, \mathcal{H}_p \subset \mathrm{interior}(\gamma)\}.$$ 
This space naturally inherits topology from uniform convergence on curve spaces.

More sophisticated interpretations arise through **moduli theory**. The moduli space $M_g$ represents isomorphism classes of algebraic curves of genus $g$, forming a geometric space of dimension $3g-3$ for $g \geq 2$. These aren't ordinary manifolds but rather Deligne-Mumford stacks, which properly handle curves with non-trivial automorphisms. The Deligne-Mumford compactification $\overline{M}_g$ adds stable nodal curves, creating a projective variety that serves as the universal parameter space for curves.

For smooth curves, the **Fréchet manifold framework** developed by Michor and Mumford provides the most general setting. The space $C^{\infty}(S^1, \mathbb{R}^2)$ of smooth maps from the circle to the plane forms an infinite-dimensional manifold, with tangent spaces consisting of smooth vector fields along curves. This framework supports Riemannian metrics like 
$G^A_c(h,k) = \int(1+A\kappa_c^2)\langle h,k\rangle|c'|d\theta$
where the curvature-weighted term prevents vanishing geodesic distances.

**Parametric families** offer a practical perspective: $F: P → C$ maps parameter spaces to curve configurations while preserving constraints like convexity and enclosure. These families naturally arise in applications from computer vision to robotics, where curves must evolve subject to geometric constraints.

## Minkowski operations extend naturally to curve families

Minkowski sum and difference operations, fundamental in computational geometry, extend from individual curves to curve families through pointwise application across parameters. For parametric families $C(t,s)$ where $t$ parameterizes curves and $s$ indexes the family, the Minkowski sum $A(s) \oplus B(s)$ preserves the family structure while maintaining key geometric properties.

**Convolution curves** play a central role in this extension. For planar curves, the convolution consists of vector sums of curve points sharing the same normal direction. Research by Ruan and Chirikjian (2021) provides closed-form parametric formulas for Minkowski sums of curves with smooth, positively curved boundaries, enabling efficient computation.

On moduli spaces, Minkowski operations acquire additional structure through embeddings in higher-dimensional spaces. The Deligne-Mumford compactification provides a framework where set operations preserve topological invariants like genus bounds and connectivity properties. However, rational curves generally lose rationality under Minkowski operations, necessitating approximation methods for practical computation.

Configuration space construction in robotics exemplifies these operations' practical importance. The Minkowski difference between robot and obstacle geometries yields the configuration space obstacles, reducing complex collision detection to point-robot navigation. For polygonal families, algorithms achieve $O(m+n)$ complexity for convex cases, though non-convex scenarios require decomposition methods.

## Set-theoretic operations reveal geometric structure

Set operations on curve loci—union, intersection, and complement—admit natural geometric interpretations that preserve meaningful properties. The **union of curve loci** represents the envelope of multiple curve families, capturing all curves satisfying at least one defining condition. Geometrically, this corresponds to the outer boundary of overlapping curve families.

**Intersection operations** yield curves satisfying multiple constraints simultaneously, crucial for solving variational problems on curve spaces. In moduli theory, intersections of curve loci often represent special geometric configurations—for instance, the hyperelliptic locus within $M_g$ consists of curves admitting degree-2 maps to the projective line.

The **complement operation** defines forbidden regions in applications like motion planning. The complement of a curve locus represents obstacle regions that moving curves must avoid. These operations preserve several topological invariants: Hausdorff dimension for fractal curve families, connectivity properties in function spaces, and degree bounds for algebraic curve families.

Research demonstrates that set operations on curve loci in infinite-dimensional spaces require careful functional analysis. The Hausdorff distance provides a metric on compact curve subsets, while the Gromov-Hausdorff distance generalizes to metric measure spaces. Modified versions accommodate practical applications while preserving theoretical rigor.

## Morphological operations bridge discrete and continuous

Mathematical morphology extends from binary images to curve families through the complete lattice framework developed by Serra and Matheron. For curve families $\gamma(s,t)$, morphological operations take the form: 
$\text{dilation } \delta_B(\gamma) = \sup\{\gamma(s) + B(s-x)\}$
$\text{erosion } \varepsilon_B(\gamma) = \inf\{\gamma(s) - B(s-x)\}$
with opening and closing as compositions.

The **level set connection** proves particularly powerful. Representing curves implicitly as zero level sets $\phi(x,y,t) = 0$ enables morphological operations on level set functions, providing topology-preserving curve evolution with natural handling of merging and splitting. This approach offers numerical stability without reinitialization and enables integer-only operations for computational efficiency.

**Variational methods** complement morphological approaches through energy minimization. Energy functionals like the elastic energy $E[\gamma] = \int \kappa^2(s)ds$ or bending energy $E[\gamma] = \int (\alpha|\gamma'|^2 + \beta|\gamma''|^2)ds$ drive curve evolution through gradient flows. The curve shortening flow $\partial\gamma/\partial t = \kappa N$ exemplifies how local curvature drives global shape change, with convex curves evolving to circles before extinction.

The **square root velocity (SRV) representation** transforms elastic metrics into L² metrics, simplifying geodesic computations while maintaining reparametrization invariance. This framework extends to curves in Lie groups and homogeneous spaces, enabling shape analysis in non-Euclidean settings.

## Variational calculus provides optimization framework

Calculus of variations on curve families involves minimizing energy functionals $E[\gamma] = \int L(s,\gamma,\gamma',\gamma'')ds$, where the Lagrangian $L$ encodes geometric constraints. The Euler-Lagrange equations yield necessary conditions for extrema, generating families of optimal curves.

**Gradient flows** provide systematic optimization approaches. The steepest descent evolution $\partial\gamma/\partial t = -\nabla E[\gamma]$ generalizes to various geometric flows: curve shortening flow preserves embeddedness of simple closed curves, mean curvature flow extends to higher dimensions with applications to general relativity, and elastic flow $\partial\gamma/\partial t = -(\kappa_{ss} + \kappa^3)N$ incorporates higher-order derivatives.

**Optimal transport theory** on curve spaces introduces Wasserstein distances between curve distributions. Recent work applies these concepts to neural network compression, where parameter spaces are viewed as Riemannian manifolds with natural geometric structure. The connection to machine learning optimization proves surprisingly deep.

Active contours in computer vision exemplify practical applications. The energy $E[C] = E_{\text{internal}} + E_{\text{external}}$ balances smoothness constraints against image-derived forces. Modern implementations use level sets for automatic topology handling, with variants like geodesic active contours incorporating geometric curve shortening.

## Algebraic operations encode geometric transformations

Algebraic operations in curve moduli spaces arise primarily through group actions. The projective general linear group $\text{PGL}(n)$ acts on curves embedded in projective space, with moduli spaces emerging as quotients under these actions. **Geometric Invariant Theory (GIT)**, developed by Mumford, provides the theoretical foundation for constructing well-behaved quotients through stability conditions.

**Deformation theory** reveals the infinitesimal structure of moduli spaces. First-order deformations of curves correspond to elements of $H^1(C,T_C) \cong H^0(C,\omega_C^{\otimes 2})$, with dimension $3g-3$ for genus $g > 1$. This algebraic framework connects to differential geometry through versal families and formal existence theorems.

Concrete examples from integrable systems illustrate these concepts. **Seiberg-Witten curves** encode physical properties of supersymmetric gauge theories, while **Hitchin systems** provide families of spectral curves parametrizing Higgs bundles. These algebraic curves determine action-angle variables in classical mechanics, connecting abstract algebra to physical dynamics.

The preservation of properties under algebraic operations proves crucial. Birational invariants like fundamental groups and Hodge numbers remain unchanged under appropriate transformations. Topological properties persist through stratifications of moduli spaces, with boundary strata corresponding to degenerate curve configurations.

## Differential geometry yields meaningful loci

Differential geometry provides numerous examples where operations on curve families produce geometrically significant loci. **Conjugate loci** arise from one-parameter families of geodesics, forming envelopes where geodesics cease to be globally minimizing. This construction connects to coherent states in quantum mechanics and optimal control theory.

**Characteristic curves of PDEs** reduce partial differential equations to families of ordinary differential equations through the method of characteristics. For first-order PDEs, the Lagrange-Charpit equations $\frac{dx_i}{F_{p_i}} = \frac{-dp_i}{F_{x_i} + F_u p_i}$ generate characteristic curves that propagate information. Higher-order PDEs use characteristics to track singularity propagation and classify equation types.

**Geodesic families on Lie groups** with bi-invariant metrics consist of one-parameter subgroups, connecting group theory to differential geometry. The square root velocity transform generalizes to homogeneous spaces $G/H$, enabling reparametrization-invariant shape analysis with applications in computer animation and pattern recognition.

The **space of closed curves on surfaces** forms an infinite-dimensional manifold with natural group actions by reparametrizations. Morse theory on loop spaces, pioneered by Bott, reveals topological information about the underlying manifold through critical points of energy functionals on curve spaces.

## Machine learning leverages geometric optimization

The connection between curve theory and machine learning optimization extends far beyond analogy. **Parameter spaces as Riemannian manifolds** enable geometric optimization using geodesics rather than straight-line updates. Recent surveys document how Riemannian-based deep learning exploits geometric structure that Euclidean optimization cannot access.

**Sparsification as geometric selection** frames neural network pruning as choosing optimal curve subfamilies. Research on "Geometric sparsification in recurrent neural networks" introduces moduli regularization leveraging dynamical systems induced by recurrent structure. This provides the first a priori description of desired sparse architectures through explicit geometric constraints, achieving 55.3% FLOP reduction while maintaining performance.

**Optimal transport for compression** uses geometric distances between probability distributions. Neural optimal transport algorithms compute transport maps and plans with proven universal approximation properties. Applications include knowledge distillation, where student networks learn to match teacher distributions through geometric transport rather than pointwise imitation.

**Mode connectivity via parametrized curves** reveals that different neural network solutions connect through continuous paths in parameter space with low loss. Extensions from linear to quadratic and geodesic connections show that loss landscapes contain rich geometric structure. Direct manifold embeddings generalize simple curves to complex geometric objects while maintaining interpretability.

Information geometry provides a unifying framework, using Fisher information-based metrics to define distances and velocities on parameter manifolds. This reveals phase transition-like behavior during training and enables quantitative comparison of model behaviors through geometric distances.

The emergence of **geometric deep learning** unifies successful neural architectures (CNNs, RNNs, GNNs, Transformers) through geometric principles following Klein's Erlangen Program. Tropical geometry offers another perspective, viewing neural networks as tropical rational functions with parameter space subdivisions corresponding to activation patterns.

These mathematical connections provide concrete tools for neural network compression: manifold regularization for structured pruning, optimal transport for knowledge distillation, and geometric flows for parameter optimization. The curve-theoretic perspective transforms abstract optimization into geometric navigation, offering both theoretical insights and practical algorithms for the sparsification challenges inherent in large language model deployment.