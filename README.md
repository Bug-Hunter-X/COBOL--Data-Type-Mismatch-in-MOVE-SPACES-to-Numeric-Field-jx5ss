This repository demonstrates a subtle but potentially harmful bug in COBOL involving the use of the MOVE SPACES statement with numeric fields. The bug can be difficult to detect because it may not immediately result in a compiler error. The primary issue is that moving spaces into a numeric variable will not result in a zero but will result in a garbage value or unpredictable behaviour.  This code example highlights the issue and provides a robust solution.

The `bug.cob` file contains the buggy code, which can lead to unexpected results, whilst `bugSolution.cob` demonstrates how to correctly handle the initialization of numeric fields. 

This example emphasizes the importance of rigorous data type checking and validation in COBOL programming to prevent such subtle errors.