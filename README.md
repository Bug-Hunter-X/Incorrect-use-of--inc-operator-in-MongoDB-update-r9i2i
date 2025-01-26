# Incorrect use of $inc operator in MongoDB update

This example demonstrates an uncommon error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment a numerical field by a given value.  However, if a string value is provided instead of a number, the operation might fail or produce unexpected results.

## Bug
The `bug.js` file contains the incorrect usage of the `$inc` operator, providing a string value ('1') instead of a number (1).

## Solution
The `bugSolution.js` file corrects this error by providing a numerical value to the `$inc` operator.
