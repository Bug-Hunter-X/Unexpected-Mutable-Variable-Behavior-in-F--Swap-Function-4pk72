# F# Mutable Variable Swap Bug

This repository demonstrates a common issue when working with mutable variables in F#.  The `swap` function attempts to swap the values of two mutable variables, but due to F#'s pass-by-reference semantics for mutable values, it modifies the original variables directly, leading to unexpected results.

The `bug.fs` file contains the code exhibiting the bug, and `bugSolution.fs` provides a corrected version illustrating how to achieve the intended variable swap without unintended side effects.

This example highlights the importance of understanding F#'s mutable variable handling and how to avoid common pitfalls.