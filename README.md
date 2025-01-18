# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB: providing a string value instead of a numeric value.

## Bug Description
The `$inc` operator is used to increment a numeric field in a MongoDB document. If you provide a string value to `$inc`, it will throw an error because it cannot perform arithmetic operations on strings.

## Solution
The solution is to provide a numeric value (integer or double) to the `$inc` operator.
