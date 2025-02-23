# Incorrect Usage of $inc Operator in MongoDB
This example demonstrates an uncommon error in MongoDB update operations involving the `$inc` operator. The `$inc` operator is used to increment a numerical field in a document. However, providing a string value instead of a number will not result in the expected numerical increment. Instead, the string will be appended to the existing value.