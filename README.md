# TypeScript Generic Type Inference Issue with Array Combination

This repository demonstrates a common issue encountered when using generics in TypeScript for combining arrays of different types.  The `combineArrays` function attempts to combine two arrays of any type `T`, but the type inference fails when the arrays contain different types.

The `bug.ts` file contains the buggy code, showcasing the type error. The `bugSolution.ts` file provides a solution to resolve the type mismatch.