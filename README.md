# MongoDB $inc Operator with String Value
This example demonstrates an incorrect usage of MongoDB's `$inc` operator, where a string value is used instead of a number. This leads to an error during update operations.
The `bug.js` file contains the erroneous code, while `bugSolution.js` provides the corrected version.
## Bug
The bug lies in providing a string ('1') instead of a number (1) to the `$inc` operator. The correct way to increment a field is using a numerical value.
## Solution
The solution replaces the string '1' with the integer 1 in the `$inc` operator to correctly increment the field.