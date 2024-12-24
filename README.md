# F# Mutable Variable Swap Bug

This repository demonstrates a common error when working with mutable variables in F#.  The `swap` function intends to exchange the values of two mutable variables, but due to pass-by-reference semantics, it fails to achieve the expected result.  The solution demonstrates the correct way to achieve value swapping using a tuple or by creating new variables.