# Java Calculation Example

This Java program demonstrates basic arithmetic operations like addition, subtraction, multiplication, and division. The program prompts the user to enter two numbers and then calculates and displays the results of these operations.

## Program Code

Here's the complete Java code for a simple arithmetic calculator:

```java
import java.util.Scanner;

public class SimpleCalculator {
    public static void main(String[] args) {
        // Create a Scanner object to read input from the keyboard
        Scanner scanner = new Scanner(System.in);

        // Ask the user to enter two numbers
        System.out.println("Enter first number:");
        double firstNumber = scanner.nextDouble();

        System.out.println("Enter second number:");
        double secondNumber = scanner.nextDouble();

        // Perform arithmetic operations
        double sum = firstNumber + secondNumber;
        double difference = firstNumber - secondNumber;
        double product = firstNumber * secondNumber;
        double quotient = firstNumber / secondNumber;

        // Display the results
        System.out.println("Results:");
        System.out.println(firstNumber + " + " + secondNumber + " = " + sum);
        System.out.println(firstNumber + " - " + secondNumber + " = " + difference);
        System.out.println(firstNumber + " * " + secondNumber + " = " + product);
        System.out.println(firstNumber + " / " + secondNumber + " = " + quotient);

        // Close the scanner
        scanner.close();
    }
}
```

## How the Program Works

1. Importing Scanner: First, we import the Scanner class, which allows us to read input from the user via the keyboard.
2. Reading Input: We create an instance of Scanner and use it to prompt the user for two numbers.
3. Calculating Results: The program calculates the sum, difference, product, and quotient of the two numbers entered by the user.
4. Displaying Results: It then prints out the results of these calculations to the console.
5. Resource Management: Finally, we close the Scanner instance to free up resources.

## Conclusion

This simple calculator program in Java illustrates how to perform basic arithmetic operations and handle user input. It's a fundamental example of how Java can be used for mathematical calculations and user-interactive applications.
