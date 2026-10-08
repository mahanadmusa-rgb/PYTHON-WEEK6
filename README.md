# Week 6 Assignment - Safe Functions

## Files

- `safe_tools.py` - Contains three safe functions using try/except to handle errors.
- `README.md` - Explains the assignment and why an if check alone cannot catch invalid number conversion.

## Why can't an if check catch "abc" on its own?

An `if` check can test conditions, but `int("abc")` causes a `ValueError` when Python tries to convert the text into a number. The `try/except` block catches this error and allows the program to continue running.

