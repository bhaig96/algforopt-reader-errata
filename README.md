# Errata for the course reader for AA222

1. Alg. 16.5: Potential maximizers should be potential minimizers with `M[S] = l[S] .< minimum(u[S])`. The function signature should be `compute_sets!(GP, S, M, E, X, u, l, y_max, β)`
2. Sec. 2.3.1: The proof of the quadratic error for the central difference method had a small error that propagated through some of the equations at the end of this subsection.
3. Sec. C.2: Second sentence after C.10, replace "infinitely differentiable" with "analytic" and also add "within a local neighborhood".
4. Sec 3.1: For simplicity, it's easier to use the definition of unimodality where f is monotonically decreasing for x <= x^* and monotonically increasing for x >= x. Then in the second paragraph we have f(a) > f(b) < f(c).
