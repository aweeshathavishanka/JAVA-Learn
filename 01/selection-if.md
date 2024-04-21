# Java Selection: `if` Statement

The `if` statement in Java is used to perform decision-making operations within a program. It tests a condition and executes a block of code if the condition is `true`. If the condition is `false`, the code inside the block is skipped.

## Syntax of `if` Statement

Here is the basic syntax of an `if` statement in Java:

```java
if (condition) {
    // code to be executed if condition is true
}

```

- condition: A boolean expression that evaluates to true or false.
- code to be executed: This is the block of code that runs only if the condition is true.

## Example: Simple if Statement

```java
public class IfExample {
    public static void main(String[] args) {
        int number = 20;

        // check if the number is greater than 10
        if (number > 10) {
            System.out.println("The number is greater than 10.");
        }
    }
}
```

This program checks if the variable number is greater than 10. If this condition is true, it prints a message to the console.

## Example: if with Else Clause

You can also use an else clause with an if statement to specify the code that should execute when the condition is false.

```java
public class IfElseExample {
    public static void main(String[] args) {
        int number = 8;

        if (number > 10) {
            System.out.println("The number is greater than 10.");
        } else {
            System.out.println("The number is 10 or less.");
        }
    }
}
```

In this example, the program will check if number is greater than 10. If this condition is true, it will print "The number is greater than 10." If the condition is false, it will print "The number is 10 or less."

## Conclusion

The if statement is a powerful tool in Java for making decisions based on conditions. By incorporating if statements into your programs, you can control the flow of execution based on different conditions, allowing for more dynamic and responsive code.
