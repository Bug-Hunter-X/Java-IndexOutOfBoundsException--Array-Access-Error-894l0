# Java IndexOutOfBoundsException Bug

This repository demonstrates a common Java error: the `IndexOutOfBoundsException`. The `bug.java` file contains code that attempts to access an array element beyond its bounds, leading to this exception. The solution is provided in `bugSolution.java`.

**Bug:** The original code incorrectly tries to access index 5 of an array with length 5 (valid indices are 0-4). This causes an `IndexOutOfBoundsException` during runtime.

**Solution:** The solution checks the index bounds before accessing the array element, preventing the exception.