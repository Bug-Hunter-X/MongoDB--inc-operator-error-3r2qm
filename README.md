# MongoDB $inc operator error
This example demonstrates an incorrect usage of the `$inc` operator in a MongoDB update operation. The `$inc` operator is used to increment a numeric field by a specified value. However, in this example, the value provided is a string, which leads to an error.

## Bug
The bug lies in the `updateOne` operation, where the value assigned to the `field` is a string instead of a number. This causes the update to fail.

## Solution
The solution involves correcting the value assigned to the `field` in the `$inc` operation to be a number.
