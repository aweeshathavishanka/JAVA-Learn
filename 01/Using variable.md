# Java Variables

Variables in Java are containers that hold data values during the execution of a program. Each variable in Java must be declared with a specific type which determines the size and layout of the variable's memory, the range of values that can be stored within that memory, and the set of operations that can be applied to the variable.

## Types of Variables in Java

Java supports several types of variables, each with its own purpose:

- **Local Variables**: Declared inside methods, constructors, or blocks and are only accessible within those scopes.
- **Instance Variables**: Declared in a class, but outside any method, constructor or block. These variables are specific to an instance of the class.
- **Class Variables (Static Variables)**: Declared with the `static` keyword inside a class but outside any method, constructor, or block. These variables are common to all instances of the class.

## Declaring Variables

To declare variables in Java, you must specify the variable's type followed by the variable's name:

```java
int age;
double salary;
String name;
```

- int, double, String are data types of the variables.
- age, salary, name are identifiers (names) of the variables.

## Initializing Variables

Variables can be initialized (assigned a value) at the time of declaration or after it:

```java
int age = 25; // initialization at the time of declaration
double salary;
salary = 3000.50; // initialization after declaration
String name = "Alice";
```

### Example of Variable Usage

Here's a simple Java program that demonstrates the declaration, initialization, and usage of various types of variables:

```java
public class Employee {
    static int retirementAge = 65; // class variable
    String name; // instance variable
    double salary; // instance variable

    public void displayDetails() {
        int year = 2023; // local variable
        System.out.println("Name: " + name);
        System.out.println("Salary: $" + salary);
        System.out.println("Retirement age: " + retirementAge);
        System.out.println("Year: " + year);
    }

    public static void main(String[] args) {
        Employee emp = new Employee();
        emp.name = "John Doe";
        emp.salary = 50000;
        emp.displayDetails();
    }
}
```

## Conclusion

Understanding how to declare, initialize, and use variables is fundamental in Java programming. Variables are essential for storing and manipulating data within your programs, enabling dynamic and flexible software development.
