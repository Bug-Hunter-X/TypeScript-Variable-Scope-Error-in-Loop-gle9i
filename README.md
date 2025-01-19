# TypeScript Variable Scope Error

This example demonstrates a common error in TypeScript related to variable scope within loops. The variable `i` is declared inside the `for` loop, making it inaccessible outside the loop's scope. Attempting to access or return `i` after the loop results in a compiler error.

The solution involves either declaring `i` outside the loop or refactoring the code to avoid the need to access `i` after the loop.