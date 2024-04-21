Below is a simple C++ program that prompts the user to input the length and width of a rectangle, calculates the perimeter, and then prints the result. This program demonstrates basic input/output operations and arithmetic in C++.

### C++ Program to Calculate the Perimeter of a Rectangle

```cpp
#include <iostream>
using namespace std;

int main() {
    // Declare variables to store the length and width
    double length, width;

    // Prompt the user to enter the length of the rectangle
    cout << "Enter the length of the rectangle: ";
    cin >> length;

    // Prompt the user to enter the width of the rectangle
    cout << "Enter the width of the rectangle: ";
    cin >> width;

    // Calculate the perimeter of the rectangle
    double perimeter = 2 * (length + width);

    // Print the result
    cout << "The perimeter of the rectangle is: " << perimeter << endl;

    return 0;
}
```

### Explanation of the Program

1. Header File Inclusion: The #include <iostream> directive tells the compiler to include the standard I/O stream library, which contains definitions for input and output operations.
2. Namespace: using namespace std; allows us to use names for objects and variables from the standard library without prefixing them with std::.
3. Variable Declaration: length and width are declared as double to accommodate decimal values, which are typical measurements for length and width.
4. Input Operations: The program uses cin (character input stream) to get user input for the rectangle's length and width. cin is coupled with the extraction operator >> to store input values in the corresponding variables.
5. Perimeter Calculation: The perimeter is calculated using the formula 2 \* (length + width) and stored in the perimeter variable.
6. Output: The result is output to the console using cout (character output stream) followed by the insertion operator <<.
7. Return Statement: return 0; terminates the main() function and indicates that the program ended successfully.
   <br>
   This program is an excellent starting point for beginners to understand how to interact with users, perform calculations, and display results in C++. You can run this program in any C++ environment to see how it works.
