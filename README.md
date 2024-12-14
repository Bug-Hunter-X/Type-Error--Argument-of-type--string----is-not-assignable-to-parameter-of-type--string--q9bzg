# Type Error in TypeScript: Argument of type 'string[]' is not assignable to parameter of type 'string'

This repository demonstrates a common TypeScript error: passing an array of strings to a function expecting a single string.  The `bug.ts` file contains the erroneous code, while `bugSolution.ts` provides a corrected version.

## Problem
The `greeter` function is designed to take a single string as input and return a greeting. However, an array is passed as an argument, leading to a type error.

## Solution
The solution involves either modifying the `greeter` function to handle arrays or adjusting the way the array is handled before calling the function. The `bugSolution.ts` file provides an example of handling the array appropriately.