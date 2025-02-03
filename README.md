# Dereferencing a Null Pointer in C++

This repository demonstrates a common C++ error: dereferencing a null pointer.  The `bug.cpp` file contains code that attempts to dereference a null pointer, resulting in undefined behavior. The `bugSolution.cpp` file provides a corrected version that handles the null pointer gracefully.

This is a critical error to avoid as it often leads to program crashes and unpredictable behavior.  Always check for null pointers before attempting to dereference them. 

## How to Reproduce
1. Clone the repository.
2. Compile and run `bug.cpp`. Observe the crash.
3. Compile and run `bugSolution.cpp`. Observe the corrected behavior.