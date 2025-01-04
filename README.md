# Stack Overflow Bug in JavaScript

This repository demonstrates a common error in JavaScript: stack overflow due to improper recursion handling. The `bug.js` file contains a recursive function that causes a stack overflow for any input where 'a' is a positive integer. The `bugSolution.js` demonstrates the corrected version that handles recursion correctly. 

## How to reproduce

1. Clone this repository.
2. Open `bug.js` and run the `foo` function with a positive integer as the first argument.
3. Observe the stack overflow error.
4. Open `bugSolution.js` and run the corrected function to see it execute without error.

## Solution

The solution involves adding a check to ensure that the recursive call is made only when 'a' is larger than 0. It also handles the case where 'a' is 0 or negative, resulting in appropriate termination of the recursive calls. 