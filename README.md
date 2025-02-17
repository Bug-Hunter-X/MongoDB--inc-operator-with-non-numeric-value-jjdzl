# MongoDB $inc Operator Error
This example demonstrates an error that can occur when using the MongoDB `$inc` operator with a non-numeric value.  The `$inc` operator is used to increment a numeric field in a document.  If you attempt to increment with a non-numeric value (such as a string), the operation will likely fail. 

## Bug
The provided `bug.js` file contains code that incorrectly uses the `$inc` operator with a string value, causing an error.  The correct usage requires a numeric value.

## Solution
The `bugSolution.js` file demonstrates the correct way to use the `$inc` operator by providing a numeric increment value.
