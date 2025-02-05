# JavaScript Null Value Handling Bug

This repository demonstrates a common error in JavaScript: improper handling of null values. The `foo` function in `bug.js` incorrectly processes null inputs, resulting in unexpected behavior. The corrected version in `bugSolution.js` shows the appropriate handling. 

## Bug Description
The original `foo` function doesn't explicitly check for `null` values, causing errors or unexpected results when called with `null` arguments. 

## Solution
The updated function now includes explicit checks for null values, returning null gracefully and preventing potential errors. 