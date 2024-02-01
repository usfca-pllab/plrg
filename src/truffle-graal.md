# 2/7/24: One VM to Rule Them All

Mehmet is going to present [One VM to Rule Them
All](http://lafo.ssw.uni-linz.ac.at/papers/2013_Onward_OneVMToRuleThemAll.pdf)
by Wuerthinger, et al.

The paper introduces the Truffle framework, and Graal VM and compiler.  The goal
of Graal is to have one virtual machine (VM) that can execute a variety of
languages efficiently, ranging from really dynamic (R, JavaScript) to static
languages with direct memory access like C, C++, Fortran.  One side effect is
the ability to send data across programs written in different languages without
having to do serialization/deserialization.


[Here](https://www.youtube.com/watch?v=mMmOntDWSgw) is a presentation in case
the paper is too long of a read.
