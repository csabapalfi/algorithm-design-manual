# Introduction

## Definition

An algorithm:

* is a procedure to accomplish a specific task
* must solve a general, well-specified problem

An algorithmic problem is specified by:

* describing the complete set of instances it must work on 
* and of its output after running on one of these instances

An algorithm is a procedure that takes any of the possible input instances and transforms it to the desired output.

## Correctness

There is a fundamental difference between algorithms, which always produce a correct result, and heuristics, which may usually do a good job but without providing any guarantee.

Reasonable-looking algorithms can easily be incorrect. Algorithm correctness is a property that must be carefully demonstrated (by a mathematical proof).

### Expressing algorithms
The heart of any algorithm is an idea. If your idea is not clearly revealed when you express an algorithm, then you are using too low-level a notation to describe it.

Problem specifications have two parts: 

* (1) the set of allowed input instances, and 
* (2) the required properties of the algorithm’s output

An important and honorable technique in algorithm design is to narrow the set of allowable instances until there is a correct and efficient algorithm. For example, we can restrict a graph problem from general graphs down to trees, or a geometric problem from two dimensions down to one.

common traps in specifying the output requirements of a problem:

* asking an ill-defined question
* creating compound goals

### Demonstrating incorrectness
