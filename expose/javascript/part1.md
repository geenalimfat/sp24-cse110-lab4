1. 20
2. 20
3. 20
4. Error because the variable `result` is declared with the keyword `let` which restricts the scope of  `result` to the block. Line 13 is outside the block scope of `result` so the variable will not exist, throwing an error
5. Error because `result` is declared with the keyword `const` which prevents it from being reassigned.
6. Error because `result` is delcared within the block scope of the `if` statement so it does not exist outside of it. Trying to access it at line 13 will throw an error. 
