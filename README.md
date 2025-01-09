# MongoDB $inc Operator Error
This example demonstrates an incorrect usage of the MongoDB `$inc` operator, where a string value is mistakenly provided instead of a numeric value. This results in an unexpected update behavior or an error.

## Bug Description
The `$inc` operator is used to increment a numeric field in a MongoDB document.  However, in the provided code, the value to increment by ('1') is enclosed in quotes, making it a string.

## Solution
To correct the error, ensure that the value provided to the `$inc` operator is a valid number without quotes.