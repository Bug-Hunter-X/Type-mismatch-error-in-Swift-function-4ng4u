# Type Mismatch Error in Swift Function

This repository demonstrates a common type mismatch error in Swift and shows how to fix it.  The error occurs when passing a string argument to a function that expects an integer.

## Bug
The `calculateArea` function expects two integer arguments (`width` and `height`). The `bug.swift` file shows an example where a string ("hello") is passed as the `height` argument, resulting in a compiler error.

## Solution
The `bugSolution.swift` file corrects the error by passing an integer value to the `height` argument. This ensures the data types match the function's definition and prevents the compiler error.

## How to reproduce
1. Clone this repository.
2. Open `bug.swift` in Xcode.
3. Try to compile the code.  You'll see the compiler error.
4. Open `bugSolution.swift` to see the corrected code.