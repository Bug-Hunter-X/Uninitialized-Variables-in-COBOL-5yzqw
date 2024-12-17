# Uninitialized Variables in COBOL

This example demonstrates a common error in COBOL: using variables without first initializing them.  Uninitialized variables contain garbage data, leading to unpredictable program behavior and difficult-to-debug issues.

The `bug.cob` file contains code with uninitialized variables. The `bugSolution.cob` file shows how to correctly initialize the variables.