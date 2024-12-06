# Haskell Bug: Non-Exhaustive Patterns and Type Restrictions

This repository demonstrates a common Haskell bug involving non-exhaustive patterns in function definitions and overly restrictive type signatures. The `bug.hs` file contains the erroneous code, while `bugSolution.hs` provides a corrected version.

The original code attempts to access the head of a list without checking for emptiness, resulting in a runtime error when an empty list is passed.  The type signature is also too narrow, limiting the function's applicability.

The solution addresses these issues by adding a pattern for the empty list case and using a more flexible type signature.