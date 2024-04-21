# Exercise 04

Here is a simple Java program that reads ten numbers from the keyboard, counts how many of those numbers are odd and how many are even, and then prints these counts. This program utilizes a loop to process multiple inputs and conditional statements to classify the numbers.

### Java Program to Count Odd and Even Numbers

```java
import java.util.Scanner;

public class OddEvenCounter {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int countOdd = 0;
        int countEven = 0;
        int number;

        System.out.println("Please enter 10 numbers:");

        for (int i = 1; i <= 10; i++) {
            System.out.print("Number " + i + ": ");
            number = scanner.nextInt();

            if (number % 2 == 0) {
                countEven++;
            } else {
                countOdd++;
            }
        }

        System.out.println("Total odd numbers entered: " + countOdd);
        System.out.println("Total even numbers entered: " + countEven);

        scanner.close();
    }
}
```

### Explanation of the Program

1. Import Scanner Class: The program starts by importing the Scanner class from the `java.util package` , which is used for obtaining input from the user through the keyboard.
2. Main Method Declaration: The main method serves as the entry point for the Java application.
3. Create Scanner Object: A Scanner object named scanner is created to read input from the standard input stream (keyboard).
4. Variable Initialization:

- countOdd and countEven are initialized to zero to keep track of the number of odd and even numbers entered, respectively.
- number is used to store each user input temporarily.

5. Input Loop:

- The program uses a for loop to repeat the number input process ten times. The loop iterates from 1 to 10, prompting the user to enter a number in each iteration.
- Inside the loop, the user's input is read and stored in number.

6. Classification Logic:

- The program checks whether the number is even by using the modulus operator (%). If number % 2 == 0, the number is even, and countEven is incremented. Otherwise, countOdd is incremented for odd numbers.

7. Results Output:

- After exiting the loop, the program prints the total counts of odd and even numbers entered by the user.

8. Close the Scanner: The scanner object is closed to release the resources associated with it.

This program efficiently processes multiple user inputs using a loop, determines whether each input is odd or even using conditional logic, and tracks the counts of each category. It demonstrates essential Java concepts such as loops, conditionals, input handling, and basic arithmetic operations.
