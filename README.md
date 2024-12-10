# JavaScript Error: Cannot read properties of undefined (reading 'length')

This repository demonstrates a common JavaScript error and its solution. The error arises when attempting to access the 'length' property of an undefined variable.

## Bug Description
The `foo` function attempts to return the length of its argument. It correctly handles `null` values, but fails when passed `undefined` because `undefined` has no length property.

## Solution
The solution involves explicitly checking for `undefined` before accessing the `length` property.  A more robust approach would also handle other potential data types to prevent unexpected errors.

## How to Run
1. Clone this repository.
2. Open `bug.js` to see the buggy code.
3. Open `bugSolution.js` to see the corrected code.
4. Run the JavaScript files in a Node.js environment or a browser's console.