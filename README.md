# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over arrays.  The error results in an `ArrayIndexOutOfBoundsException`. The solution shows the correct way to iterate, ensuring the loop terminates before exceeding the array's bounds.

## Bug

The `BuggyArrayIteration.java` file contains the erroneous code.  The for loop attempts to access an index beyond the array's allocated size.

## Solution

The `CorrectedArrayIteration.java` file provides the corrected code. The loop condition is modified to prevent the index from exceeding the array bounds. 

This example highlights the importance of careful array indexing in programming.