# Integer Overflow Bug in Julia

This repository demonstrates a subtle integer overflow bug in a simple Julia function. The function `myfunction` calculates the square of a number if it's greater than 10; otherwise, it adds 1. However, if the input `x` is sufficiently large, calculating `x^2` can result in an integer overflow, leading to incorrect results.

The `bug.jl` file contains the buggy code.  The `bugSolution.jl` file demonstrates how to mitigate this issue by using a larger integer type or floating-point numbers.