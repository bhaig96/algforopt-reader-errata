# Errata for the course reader for AA222

1. Sec. 2.3.1: The proof of the quadratic error for the central difference method had a small error that propagated through some of the equations at the end of this subsection.
1. Exercise 2.4 solution: There should be an equals sign before the last 4.
1. Sec 3.1: For simplicity, it's easier to use the definition of unimodality where f is monotonically decreasing for x <= x^* and monotonically increasing for x >= x. Then in the second paragraph we have f(a) > f(b) < f(c).
1. Ch. 4: Figure labels for approximate line search have missing f after nabla.
1. Sec. 4.4 last paragraph: Delta y_pred / Delta y_act should be Delta y_act / Delta y_pred. 
1. Eq. 5.13: There are missing parentheses around the section before the transpose.
1. Eq. 8.19: It should sum to 1, not 0, to be consistent with text.
1. Eq. 8.20: After the ln should be an i.
1. Alg. 16.5: Potential maximizers should be potential minimizers with `M[S] = l[S] .< minimum(u[S])`. The function signature should be `compute_sets!(GP, S, M, E, X, u, l, y_max, β)`
1. Sec. C.2: Second sentence after C.10, replace "infinitely differentiable" with "analytic" and also add "within a local neighborhood".
