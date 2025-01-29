# Type 'string[]' is not assignable to type 'string'

This repository demonstrates a common TypeScript error: assigning an array of strings to a variable expecting a single string. The error arises from a mismatch between the expected type ('string') and the provided type ('string[]').

## Bug

The `greeter` function expects a single string argument. However, the code attempts to pass an array of strings (`user`). This leads to a compile-time error because TypeScript's type system prevents such incompatible assignments.

## Solution

The solution involves modifying the code to handle either a single string or an array of strings, depending on the intended behavior. The solution provided shows how to handle each case.