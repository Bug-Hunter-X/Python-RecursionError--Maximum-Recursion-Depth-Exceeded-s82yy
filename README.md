# Python RecursionError Example

This repository demonstrates a common error in recursive functions in Python, specifically the `RecursionError: maximum recursion depth exceeded` error.  The `factorial_bug.py` file contains a recursive factorial function that lacks a proper base case for handling negative inputs.  The `factorial_solution.py` file provides a corrected version that addresses this issue.

The error arises because a recursive function, without a proper base case to stop the recursion, keeps calling itself until it exceeds the maximum recursion depth allowed by Python. This leads to a stack overflow and the error message.

The solution involves adding an explicit check for negative input, handling this case gracefully, typically by returning an error value or raising an exception.