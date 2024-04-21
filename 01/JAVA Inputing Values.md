# Java Inputting Values from the Keyboard

Java provides several ways to read input from the keyboard, with the `Scanner` class being one of the most commonly used due to its simplicity and versatility. This class is part of the `java.util` package and can parse primitive types and strings using regular expressions.

## Setting Up Scanner to Read Keyboard Input

To use the `Scanner` class to read input from the keyboard, you need to follow these steps:

### 1. Import the Scanner Class

First, you must import the `Scanner` class from the `java.util` package.

```java
import java.util.Scanner;
```

### 2. Create an Instance of Scanner

Create an instance of the Scanner class, passing System.in as the argument to its constructor. System.in is an input stream connected to the keyboard input.

```java
Scanner scanner = new Scanner(System.in);
```

### 3. Read Input from the User

You can now use the Scanner instance to read different types of input from the keyboard. Here are some common methods provided by the Scanner class:

- Reading a byte: byte b = scanner.nextByte();
- Reading a short: short s = scanner.nextShort();
- Reading an int: int i = scanner.nextInt();
- Reading a long: long l = scanner.nextLong();
- Reading a float: float f = scanner.nextFloat();
- Reading a double: double d = scanner.nextDouble();
- Reading a boolean: boolean bool = scanner.nextBoolean();
- Reading a full line: String line = scanner.nextLine();
- Reading a single word: String word = scanner.next();

### 4.Close the Scanner

It's good practice to close the Scanner instance once it is no longer needed to free up system resources. This is particularly important in larger applications where resource management is critical.

```java
scanner.close();

```

## Example: Reading Multiple Types of Data

```java
import java.util.Scanner;

public class InputExample {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Enter your name:");
        String name = scanner.nextLine();

        System.out.println("Enter your age:");
        int age = scanner.nextInt();

        System.out.println("Enter your salary:");
        double salary = scanner.nextDouble();

        System.out.println("Name: " + name + ", Age: " + age + ", Salary: " + salary);

        scanner.close();
    }
}
```

### Conclusion

Using the Scanner class to read input from the keyboard in Java is straightforward and efficient for handling various input types. It provides flexibility for parsing and converting input strings into multiple data types directly, making it invaluable for interactive Java applications.
