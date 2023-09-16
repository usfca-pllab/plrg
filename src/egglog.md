# 9/22/23: egglog

Puranjai Garg is going to present
[egglog](https://dl.acm.org/doi/10.1145/3591239), a Datalog-based approach to
equality saturation.  egglog marries egg and Datalog, and uses some
optimizations from Datalog-based databases to speed up equality saturation.
Datalog also enables them to use more elaborate analyses to go beyond egg's
approach to analysis (e-class analysis).  The paper also claims that the
Datalog-based approach results in much simpler implementations for some
applications of equality saturation (such as checking if two programs are
equivalent, or program synthesis).

## Links

- [GitHub repo](https://github.com/egraphs-good/egglog)
- [web demo](https://egraphs-good.github.io/egglog/)
- [Python library](https://egg-smol-python.readthedocs.io/en/latest/)
