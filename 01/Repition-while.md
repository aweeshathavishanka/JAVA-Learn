# Java Repetition: `while` Loop

The `while` loop in Java is used to execute a block of code repeatedly as long as a given condition is true. This loop is particularly useful when the number of iterations is not known before the loop starts.

## Syntax of `while` Loop

Here is the basic syntax of a `while` loop in Java:

```java
while (condition) {
    // Statements to execute as long as the condition is true
}
```

- condition: A boolean expression that is evaluated before each iteration. If the condition evaluates to true, the loop continues; if it evaluates to false, the loop terminates.

## Example: Basic while Loop

Here’s a simple example demonstrating the while loop:

```java
public class WhileExample {
    public static void main(String[] args) {
        int count = 1;

        while (count <= 5) {
            System.out.println("Count is: " + count);
            count++;
        }
    }
}
```

In this example, the loop will continue to execute as long as the value of count is less than or equal to 5. The output will be a series of numbers from 1 to 5 printed on separate lines.

## Use Case: Reading User Input Until a Condition is Met

`while` loops are often used to process input until a user decides to stop. For instance, you can prompt the user to enter data repeatedly until they enter a specific quit command:

```java
import java.util.Scanner;

public class UserInputExample {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        String input = "";

        while (!input.equals("quit")) {
            System.out.println("Enter some text, or 'quit' to exit:");
            input = scanner.nextLine();
        }

        scanner.close();
        System.out.println("You exited the loop.");
    }
}
```

## Tips for Using while Loops

- Ensure that the condition in a while loop eventually becomes false; otherwise, you may create an infinite loop.
- Update variables involved in the condition within the loop to avoid infinite loops.

## Conclusion

The while loop in Java provides a simple yet powerful way to repeat actions under dynamic conditions where the number of iterations is not known beforehand. It is especially useful in scenarios involving user interaction or when waiting for specific conditions to be met in multi-threaded applications.
