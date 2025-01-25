# ArrayIndexOutOfBoundsException in Java

This repository demonstrates a common error in Java: the `ArrayIndexOutOfBoundsException`. The error arises from attempting to access an array element using an index that is out of the array's valid range (0 to array.length - 1).

The `bug.java` file contains the erroneous code, while `bugSolution.java` provides the corrected version.

## How to Reproduce

1. Clone the repository.
2. Compile `bug.java` using a Java compiler (e.g., `javac bug.java`).
3. Run the compiled code (e.g., `java MyClass`).

You will observe an `ArrayIndexOutOfBoundsException` being thrown.

## Solution

The solution is simple: modify the loop condition in `bugSolution.java` to ensure the index `i` always stays within the valid bounds of the array.