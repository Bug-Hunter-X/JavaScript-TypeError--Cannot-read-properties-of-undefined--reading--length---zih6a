# JavaScript TypeError: Cannot read properties of undefined (reading 'length')

This repository demonstrates a common JavaScript error: a TypeError thrown when accessing the 'length' property of an undefined variable.

The `bug.js` file contains code that reproduces this error.  The `bugSolution.js` file offers a solution.

The error occurs because the function doesn't explicitly check for `undefined`.  The solution demonstrates how to handle both `null` and `undefined` cases gracefully to prevent the error.