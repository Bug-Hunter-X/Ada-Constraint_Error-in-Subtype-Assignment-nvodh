# Ada Constraint_Error Example

This repository demonstrates a common, yet subtle, error in Ada programming: the `Constraint_Error` exception raised when assigning a value outside a subtype's range.  The error isn't always obvious when values are modified through operations instead of direct assignment.

The `bug.ada` file contains the erroneous code, while `bugSolution.ada` provides a corrected version.

This example highlights the importance of careful range checking in Ada, especially when working with subtypes.
