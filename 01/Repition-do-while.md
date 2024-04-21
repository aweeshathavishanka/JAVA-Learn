# Java Repetition: `do-while` Loop

The `do-while` loop in Java is used to execute a block of statements repeatedly until a specified condition evaluates to false. The key feature of the `do-while` loop is that it guarantees the loop's body will run at least once, because the condition is evaluated after the loop's body executes.

## Syntax of `do-while` Loop

Here is the basic syntax of a `do-while` loop in Java:

```java
do {
    // Statements to execute
} while (condition);
```

- Statements to execute: This block contains the code that will run on each iteration of the loop.
- condition: A boolean expression that is checked after the execution of the loop body. If true, the loop continues; if false, the loop ends.

## Example: Basic do-while Loop

```java
public class DoWhileExample {
    public static void main(String[] args) {
        int count = 1;

        do {
            System.out.println("Count is: " + count);
            count++;
        } while (count <= 5);
    }
}
```

In this example, the do-while loop will print "Count is: 1" through "Count is: 5". The loop increments count each time and continues running as long as count is less than or equal to 5.

## Use Case: User Input Validation

`do-while` loops are particularly useful when you need to ensure that a section of code runs at least once and the condition for continuation is based on user input, typically seen in user input validation scenarios.

```java
import java.util.Scanner;

public class InputValidation {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int number;

        do {
            System.out.print("Enter a positive number: ");
            while (!scanner.hasNextInt()) {
                String input = scanner.next();
                System.out.printf("\"%s\" is not a valid number.\n", input);
                System.out.print("Enter a positive number: ");
            }
            number = scanner.nextInt();
        } while (number <= 0);

        System.out.println("You entered: " + number);
        scanner.close();
    }
}
```

In this example, the program prompts the user to enter a positive number. It continues to prompt the user until they enter a valid positive integer.

## Conclusion

The do-while loop in Java is a powerful control structure for managing repeated tasks where at least one execution of the loop is required. By understanding and using do-while loops effectively, you can handle many scenarios where user interaction and validation are necessary.
