PLP Python Week 6 - Safe Functions

Files

"safe_tools.py" — Contains three safe functions for handling division, number conversion, and dictionary fields without crashing.
"unbreakable.py" — Contains code demonstrating how error handling can keep a Python program running when unexpected input is provided.
"README.md" — Describes the assignment and explains why an "if" check alone cannot catch invalid input such as "abc".
Why can the if check not catch abc on its own?

An "if" check can test a condition, but converting "abc" to an integer with "int()" raises a "ValueError". The "try/except" block catches this error and allows the program to continue instead of crashing.
