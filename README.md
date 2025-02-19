# MongoDB $inc Operator Error
This example demonstrates an error that can occur when using the `$inc` operator in MongoDB if you provide a string instead of a numeric value.  The `$inc` operator is used to increment a numeric field by a specific amount. Attempting to use it with a non-numeric value will result in an error.

## Bug Report
The original code incorrectly attempts to increment the 'age' field by the string '1'. This is incorrect. The solution will fix this issue.