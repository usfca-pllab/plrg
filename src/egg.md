# 9/15/22: egg: Fast and extensible equality saturation

Mehmet Emre is going to present [egg: Fast and extensible equality saturation](https://dl.acm.org/doi/10.1145/3434304) by Willsey et al.

Equality saturation is a technique to convert the phase ordering problem in
compilers (how to pick the right order of optimizations) to a numerical
optimization problem.  An equality saturation engine represents all possible
optimized programs in a compact data structure, and finds the optimal program
using numerical optimization solvers.

egg uses techniques from algorithm design (amortization), and order theory &
abstract interpretation (adding lattices) to scale up equality saturation, and
to extend it to more scenarios.
