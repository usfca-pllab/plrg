# 10/13/23: Programming by Sketches for Bit-Streaming Programs

Mehmet Emre has presented [Programming by Sketching for Bit-Streaming Programs](http://people.csail.mit.edu/asolar/papers/Solar-LezamaRBE05.pdf).  The relevant tool, Sketch is available from Armando Solar-Lezema's [academic web page](https://people.csail.mit.edu/asolar/).

Sketch allows programmers to specify bit manipulating programs in a data flow
language, and a sketch of operations that can be used in a fast implementation.
Then, the sketch compiler converts the problem of finding a correct problem that
abides by that sketch into a constraint solving problem, and uses a constraint
solver to synthesize a working program.  This allows a programming methodology
where the programmer can write an easy-to-understand program, and a high-level
description of what a fast program would look like.  Then, the compiler helps
the programmer by "filling in the blanks" in the fast program.  This allows for
doing Hacker's Delight-style error prone optimizations without having to think
about particular constants, etc.  It also enables the programmer to experiment
with different approaches by sketching them out.
