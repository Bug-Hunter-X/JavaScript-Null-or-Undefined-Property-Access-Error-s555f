# JavaScript Null or Undefined Property Access Error

This repository demonstrates a common error in JavaScript: attempting to access a property (`.length` in this case) of a variable that might be null or undefined.  This often leads to a `TypeError: Cannot read properties of undefined (reading 'length')` or similar error.

The `bug.js` file contains the erroneous code. The `bugSolution.js` file provides a corrected version that handles null and undefined values using a conditional check before accessing the property.

## How to Reproduce

1. Clone this repository.
2. Open `bug.js` and `bugSolution.js`.
3. Run `bug.js` in a JavaScript environment (e.g., Node.js). Observe the error when calling `foo(undefined)`.
4. Run `bugSolution.js`. Observe that it handles null and undefined input gracefully.