# Debug Notes

1. reproduce: Ran buggy.py and got an IndexError on line 4.
2. hypothesis: The loop is going out of range because of the + 1.
3. isolate: Checked the loop condition range(len(prices) + 1).
4. test: Printed the indices to see where it breaks.
5. fix: Removed the + 1 from the range calculation.