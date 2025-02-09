# Python Bug: ZeroDivisionError in Average Calculation
This repository demonstrates a common Python bug: a `ZeroDivisionError` that can occur when calculating the average of an empty list.  The `bug.py` file contains the buggy code, while `bugSolution.py` provides the corrected version.

The original code fails to handle the case where the input list is empty, leading to division by zero.  The solution addresses this by explicitly checking for an empty list and returning 0 in that scenario.

## How to Reproduce

1. Clone this repository.
2. Run `bug.py` with an empty list as input: `python bug.py []`
3. Observe the `ZeroDivisionError`.
4. Run `bugSolution.py` with an empty list as input: `python bugSolution.py []`
5. Observe the correct behavior.