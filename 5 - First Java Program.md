# First Java Program: Hello World

If you're starting with Java, a typical first program you might write is the "Hello World" program. This program prints the string "Hello World" to the console. Here’s a simple Java program, step by step, that you can use to understand the basics:

## Step 1: Create a Java File

First, you need to create a file with a `.java` extension. Name the file `HelloWorld.java`.

## Step 2: Write the Code

Open the file in a text editor or an Integrated Development Environment (IDE) like Eclipse, IntelliJ IDEA, or Visual Studio Code. Then, write the following code:

```java
public class HelloWorld {
    public static void main(String[] args) {
        // Print Hello World to the console
        System.out.println("Hello World");
    }
}
```

### Explanation of the Code

- **Class Declaration**:

  - `public class HelloWorld` - This line declares a class named `HelloWorld`. In Java, all code must be part of a class. The `public` keyword means that the class can be accessed by any other class.

- **Main Method**:

  - `public static void main(String[] args)` - This line declares the main method, which is the entry point for any standalone Java application. The components of this line are explained as follows:
    - `public`: Accessible from any other class.
    - `static`: Can be run without creating an instance of the class.
    - `void`: Does not return any value.
    - `main`: The name of the method that is looked for by the JVM as the starting point of the application.
    - `String[] args`: An array of strings, `args`, which stores command-line arguments.

- **Print Statement**:
  - `System.out.println("Hello World");` - This line uses the `System.out.println` method to print the text "Hello World" to the console.

## Step 3: Compile the Program

1. **Open your command line tool**:

   - Use Command Prompt on Windows or Terminal on macOS and Linux.

2. **Navigate to the directory containing your `HelloWorld.java` file**:

   - Use the `cd` command to change the directory to where your file is located.

3. **Compile the Java file**:
   - Type `javac HelloWorld.java` and press Enter. This command compiles your Java code into bytecode, creating a file named `HelloWorld.class`.

## Step 4: Run the Program

1. **Run the compiled program**:

   - Type `java HelloWorld` in the command line and press Enter.

2. **Check the output**:
   - You should see "Hello World" printed on the screen.
