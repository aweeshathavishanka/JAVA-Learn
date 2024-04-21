# Exercise 01

- Write a Java program to display your name and address in 3
  lines.

```java
public class PersonalInfo {
    public static void main(String[] args) {
        // Print name and address in three lines
        System.out.println("John Doe");
        System.out.println("1234 Elm Street");
        System.out.println("Hometown, USA 12345");
    }
}



```

### Explanation of the Java Program `PersonalInfo`

- **Class Declaration**:

  - `public class PersonalInfo` - This line declares a class named `PersonalInfo`. Every Java application must have at least one class definition that consists of class keyword followed by class name.

- **Main Method**:

  - `public static void main(String[] args)` - This method is the entry point for any standalone Java application. The `public` keyword denotes that the method can be called from any other class. The `static` means that this method can be invoked without creating an instance of the class. The `void` indicates that this method does not return any value.

- **Print Statements**:
  - `System.out.println("John Doe");` - This statement prints the name on the first line.
  - `System.out.println("1234 Elm Street");` - This statement prints the street address on the second line.
  - `System.out.println("Hometown, USA 12345");` - This statement prints the city, state, and ZIP code on the third line.

Each `System.out.println` method outputs the string passed to it and moves the cursor to the next line, making it simple to print multiple lines of text sequentially on the console.
