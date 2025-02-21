# MongoDB $inc Operator Error with String Value

This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries. The `$inc` operator is designed to increment a numerical field by a specified value.  However, providing a string value leads to an error.

## Bug
The bug arises from passing a string ('1') instead of a number (1) to the `$inc` operator. This will either cause an error or modify the field unexpectedly.