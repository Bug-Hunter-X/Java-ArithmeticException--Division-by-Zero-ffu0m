# Java ArithmeticException: Division by Zero

This repository demonstrates a common Java error: the `ArithmeticException` that occurs when dividing by zero.  The `BuggyDivision.java` file contains the flawed code, while `FixedDivision.java` provides a corrected version.

The bug is easily fixed by adding a check to prevent division by zero.

## How to run:
1. Clone this repository.
2. Compile and run the buggy code: `javac BuggyDivision.java && java BuggyDivision` (Expect an exception).
3. Compile and run the fixed code: `javac FixedDivision.java && java FixedDivision` (Expect the output 10).