# MongoDB $inc Operator Error
This example demonstrates an incorrect usage of the `$inc` operator in MongoDB. The `$inc` operator is intended to increment numeric fields; using it on a non-numeric field throws an error.

## Bug
The bug is in using `$inc` with a string field.  The correct approach is to either ensure the field is numeric or use a different operator like `$set` if you intend to change the field to a string value.

## Solution
The solution provides the correct implementation of updating numeric or string fields.