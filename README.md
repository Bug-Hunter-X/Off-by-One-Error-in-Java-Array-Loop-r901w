# Off-by-One Error in Java Array Loop

This repository demonstrates a common off-by-one error in Java when iterating over arrays.  The error occurs because the loop condition `i <= array.length` allows the loop to continue one iteration past the valid indices of the array.

The `bug.java` file contains the code with the error. The `bugSolution.java` file provides the corrected code.

## How to reproduce the error
1. Compile and run `bug.java`.
2. Observe the `ArrayIndexOutOfBoundsException`.

## Solution
The solution is to modify the loop condition to `i < array.length`, ensuring that the loop only iterates over valid indices.
