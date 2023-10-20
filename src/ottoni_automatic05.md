# 10/06/23: Automatic Thread Extraction with Decoupled Software Pipelineing

Maleke Hanson has presented [this
paper](https://web.eecs.umich.edu/~mahlke/courses/583f11/reading/ottoni_micro38.pdf)
by Ottoni et al.  In the paper, they extend Itanium with two instructions for
synchronizing data between cores, and they are automatically discovering parts
of a program that can be parallelized and synchronized using this mechanism.

Their technique (decoupled software pipelining) automatically extracts multiple
threads of execution that are non-speculative, and can be executed concurrently.
