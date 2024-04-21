# Java Comments

In Java, comments are annotations in the source code that the compiler ignores. They are used to provide explanations, increase readability, and aid others (or yourself in the future) in understanding what certain parts of the code are meant to do. Java supports three types of comments:

1. **Single-line comments**
2. **Multi-line comments**
3. **Documentation comments**

## 1. Single-line Comments

Single-line comments start with two forward slashes (`//`). Everything following the `//` on that line will be ignored by the Java compiler.

```java
// This is a single-line comment in Java

int number = 5; // This comment follows a statement
```

## 2. Multi-line Comments

Multi-line comments (also known as block comments) start with `/*` and end with `*/`. Everything between these markers will be ignored by the compiler. This type of comment can span multiple lines, making it useful for longer descriptions or for temporarily disabling blocks of code.

```java
/* This is a multi-line comment.
   It can span multiple lines.
   Java ignores everything between the start and end markers. */

int number = 10; /* This is a multi-line comment after a statement
                   and it can also be placed here */

```

## 3. Documentation Comments

Documentation comments (or doc comments) start with `/**` and end with `*/`. These are used by the Javadoc tool to generate HTML documentation for the Java code. They can include various tags that describe methods, parameters, class information, and more.

```java
/**
 * The Main class represents the entry point of the program.
 * This class contains a single method, main, which outputs "Hello, World!".
 *
 * @version 1.0
 */
public class Main {
    /**
     * Main method that runs when the program starts.
     * @param args command line arguments
     */
    public static void main(String[] args) {
        System.out.println("Hello, World!"); // Print Hello, World! to the console
    }
}


```

## Purpose of Each Type of Comment

- **Single-line and Multi-line Comments**:

  - Used by developers primarily during the development phase for notes or to temporarily deactivate code. These comments make it easier for developers to leave reminders or explain the logic of specific sections of the code without affecting its operation.

- **Documentation Comments**:
  - Intended for anyone who might use the code later, including end users of libraries, and for generating formal documentation using the Javadoc tool. These comments are essential for creating official documentation that can be generated into HTML format, providing a clear guide to the code's functionality, parameters, and more.
