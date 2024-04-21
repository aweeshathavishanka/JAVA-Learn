# JAVA Terminology

<br>
<br>
<br>
<br>

| Term                | Explanation                                                                                                                                                                                                                                        |
| ------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Class**           | A blueprint for creating objects, which contains methods, variables, and constructors. It defines the nature and behavior of objects.                                                                                                              |
| **Methods**         | Functions defined inside a class that describe the behaviors of the objects of that class. They perform operations and can return results.                                                                                                         |
| **Attribute**       | Variables that are defined within a class. They represent the state or properties of an object. Also known as fields.                                                                                                                              |
| **Interface**       | A reference type in Java, similar to a class, that can contain only constants, method signatures, default methods, static methods, and nested types. Interfaces cannot contain instance fields. The methods in interfaces are abstract by default. |
| **Package**         | A namespace for organizing classes and interfaces in a logical manner. Packages can be imported by other classes and interfaces.                                                                                                                   |
| **ByteCode**        | The intermediate form of compiled code, distinct from machine code, which is platform-independent. This code is executed by the JVM.                                                                                                               |
| **Virtual Machine** | An emulation of a physical machine. In Java, the JVM (Java Virtual Machine) enables Java bytecode to be executed as actions or operating system calls on any processor, regardless of the underlying platform.                                     |

### Key Differences Highlighted:

1. **Headers vs. Imports**: C++ uses headers (e.g., `#include <iostream>`), while Java uses imports to include external libraries, although for this simple program, no imports are needed beyond the default.

2. **Main Method**:

   - C++: `int main()` is the starting point of a C++ program.
   - Java: `public static void main(String[] args)` is the entry point for a Java application. It's always inside a class.

3. **Output**:

   - C++: `std::cout` is used for console output.
   - Java: `System.out.println` is used for printing messages to the console.

4. **Namespaces**:

   - C++: Often uses `std::` prefix before standard library items (unless using `using namespace std;`).
   - Java: Uses fully qualified names or import statements to access classes and packages.

5. **End of Program**:
   - C++: Returns an integer from `main()`, typically `return 0;` to indicate successful execution.
   - Java: `main()` returns void, and the program ends when the main method exits.

Each language has its own set of conventions and syntax rules which are evident even in such a simple program. These examples provide a clear, introductory comparison for new programmers or those transitioning between the two languages.
