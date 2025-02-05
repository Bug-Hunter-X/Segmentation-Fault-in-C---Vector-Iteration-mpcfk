# C++ Vector Out-of-Bounds Access
This repository demonstrates a common C++ error: accessing an element beyond the bounds of a `std::vector`. The `bug.cpp` file contains the erroneous code, which results in a segmentation fault. The `bugSolution.cpp` file provides the corrected code.

**Error:** Attempting to access `myVector[10]` when the vector's size is 10 leads to undefined behavior.  Vectors are 0-indexed, meaning valid indices range from 0 to `size() - 1`.