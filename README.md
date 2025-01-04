# Off-by-One Error in Array Traversal

This repository demonstrates a common off-by-one error in Java. The code attempts to iterate through an array, but the loop condition is incorrect, causing an `ArrayIndexOutOfBoundsException`.  The solution shows how to correct the loop to avoid this error.

## Bug
The `Bug.java` file contains the buggy code.  The loop runs one iteration too many, attempting to access an index that is out of bounds.

## Solution
The `BugSolution.java` file provides the corrected code.  The loop condition is changed to ensure it iterates only within the valid array bounds.

This example highlights the importance of carefully considering array indices when iterating.