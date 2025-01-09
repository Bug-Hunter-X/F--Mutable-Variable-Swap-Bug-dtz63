# F# Mutable Variable Swap Bug

This repository demonstrates a common error in F# involving the incorrect swapping of mutable variables.

The `bug.fs` file contains code that attempts to swap two mutable variables using a function. However, due to the way F# handles mutable variables, the swap operation does not modify the original variables.

The `bugSolution.fs` file provides a corrected version of the code, demonstrating the correct way to swap mutable variables in F#.

## How to Reproduce

1. Clone this repository.
2. Open the `bug.fs` file in a F# editor.
3. Run the code. Observe that the values of `x` and `y` are not swapped.
4. Open the `bugSolution.fs` file and run that code to see the correct behavior.