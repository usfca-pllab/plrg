# 10/20/23: Csmith

Rachel Coley is going to present [Finding and Understanding Bugs in C
Compilers](https://users.cs.utah.edu/~regehr/papers/pldi11-preprint.pdf).  This
paper introduces Csmith, which is a fuzzer (random test generator) that
generates _undefined behavior-free_ C programs.  The team behind this paper has
found hundreds of bugs in GCC and Clang using Csmith, and showed the
effectiveness of fuzzing even for complex programs.  They have a lot more work
that builds on top of Csmith.
