# Java Repetition: `for` Loop

The `for` loop in Java is used to repeat a block of statements a known number of times, making it highly useful for iterating over arrays, collections, or any task that requires repetition of actions for a specific count.

## Syntax of `for` Loop

The basic syntax of a `for` loop in Java is as follows:

```java
for (initialization; condition; update) {
    // Block of statements
}
```

- Initialization: This step allows you to initialize one or more loop counters, but it's optional.
- Condition: The loop continues as long as this condition is true. When the condition becomes false, the loop terminates.
- Update: Executes after each iteration of the loop, which usually increments or decrements the loop counter.

## Example: Basic for Loop

```java
public class ForLoopExample {
    public static void main(String[] args) {
        for (int i = 1; i <= 5; i++) {
            System.out.println("Number: " + i);
        }
    }
}
```

In this example, i is initialized to 1, and the loop continues as long as i is less than or equal to 5. The value of i is incremented by 1 in each iteration.

## Use Case: Iterating Over Arrays

```java
public class ArrayIterationExample {
    public static void main(String[] args) {
        int[] numbers = {10, 20, 30, 40, 50};

        for (int i = 0; i < numbers.length; i++) {
            System.out.println("Element at index " + i + " is " + numbers[i]);
        }
    }
}
```

This example demonstrates iterating over an array of integers and printing each element with its index.

## Enhanced for Loop (For-Each)

Java also provides an enhanced for loop, often called the "for-each" loop, which simplifies the syntax for iterating through arrays and collections:

```java
public class ForEachExample {
    public static void main(String[] args) {
        int[] numbers = {10, 20, 30, 40, 50};

        for (int number : numbers) {
            System.out.println("Number: " + number);
        }
    }
}
```

The for-each loop automatically iterates over each element in the numbers array without needing to use an index variable.

<br>
<br>
<br>

## Conclusion

The for loop and its enhanced variant provide flexible methods for iterating over data structures or executing a block of code a specific number of times. Understanding these loops is essential for effective control flow in Java programming.
