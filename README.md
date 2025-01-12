# JavaScript Bug: Unexpected Null Handling

This repository demonstrates a common but subtle JavaScript bug related to null handling. The `foo` function handles null values by returning 0, which may not always be the correct behavior.  The solution explores better error handling and input validation.

## Bug Description

The `foo` function adds two numbers. However, it implicitly handles null values by returning 0.  While this prevents errors, it may mask underlying issues and produce unexpected results if 0 isn't an appropriate default value.

## Bug Solution

The solution provides more robust error handling by throwing an error if null values are passed, providing clearer indication of unexpected input.