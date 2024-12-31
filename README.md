# Unexpected ZeroDivisionError in Python Function

This repository demonstrates a subtle and uncommon error related to zero division in Python. The `bug.py` file contains a function with flawed logic that leads to an unexpected `ZeroDivisionError` when both inputs are zero. The `bugSolution.py` file provides a corrected version.

The error arises due to how the conditional statements are structured. It correctly handles cases where either input is zero, but when both inputs are zero, the unexpected error occurs.

The solution highlights the importance of considering all possible conditions when dealing with division and ensuring the order of checks prevents errors.