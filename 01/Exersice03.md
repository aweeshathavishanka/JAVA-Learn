Here is a simple Java program that takes three integers as input from the user, determines the largest and the smallest of the three, and then prints them. This program demonstrates how to use the Scanner class for input and conditional statements (if-else) to find and compare values.

## Java Program to Find the Largest and Smallest Numbers

```java
import java.util.Scanner;

public class LargestSmallest {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int a, b, c;

        // Prompt the user to enter three integers
        System.out.println("Enter the first integer:");
        a = scanner.nextInt();

        System.out.println("Enter the second integer:");
        b = scanner.nextInt();

        System.out.println("Enter the third integer:");
        c = scanner.nextInt();

        // Initialize largest and smallest with the first number
        int largest = a;
        int smallest = a;

        // Compare b with largest and smallest
        if (b > largest) {
            largest = b;
        }
        if (b < smallest) {
            smallest = b;
        }

        // Compare c with largest and smallest
        if (c > largest) {
            largest = c;
        }
        if (c < smallest) {
            smallest = c;
        }

        // Output the results
        System.out.println("The largest number is: " + largest);
        System.out.println("The smallest number is: " + smallest);

        // Close the scanner resource
        scanner.close();
    }
}
```

### Explanation of the Program

1. Import Scanner Class: The program starts by importing the Scanner class, which is used to read the user's input.
2. Main Method Declaration: The main method is the entry point for any Java application.
3. Create Scanner Object: Inside the main method, a Scanner object named scanner is created to read input from the standard input stream (keyboard).
4. Variable Declaration: Three integer variables a, b, and c are declared to hold the values entered by the user.
5. User Input: The program asks the user to enter three integers, which are read and stored in a, b, and c respectively.
6. Initial Comparison Setup: Variables largest and smallest are initialized to the value of a.
7. Comparison Logic:
   - The values of b and c are compared with largest and smallest to find which is the largest and which is the smallest among the three.
   - This is done using simple if statements that check each condition and update largest and smallest as needed.
8. Output the Results: After all comparisons are done, the largest and smallest values are printed to the console.
9. Close the Scanner: Finally, the scanner object is closed to free up resources.

<br>
This program efficiently finds the largest and smallest integers among three entered values using basic conditional statements and user input. It's a good example of fundamental Java programming concepts for beginners.
