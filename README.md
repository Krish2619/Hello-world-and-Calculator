Aim:
To create a simple C++ program that takes two floating-point numbers as input and performs basic arithmetic operations: addition, subtraction, multiplication, and division.

Apparatus:
-GNU g++ compiler or any C++ compiler
-Text editor or integrated development environment (IDE) like Visual Studio Code, Code::Blocks, or Dev-C++

Program Explanation:
The program begins by including the <iostream> library, which allows input and output operations using cin and cout.
using namespace std; is declared to avoid prefixing standard library functions and objects with std::.
Inside the main() function:
It first prints a greeting message: "Hello, World!".
Then it declares floating-point variables n and m to store two numbers, and variables to store results of arithmetic operations (sum, sub, div, mul).
The program prompts the user to input the first and second numbers.
It calculates the sum, difference, product, and quotient of the two numbers.
It displays the results of each operation.
The division operation assumes the second number is not zero to avoid runtime errors (in improved versions, this should be checked).
The program terminates after displaying all results.

Algorithm:
1. Start the program.
2. Print a welcome message.
3. Declare floating-point variables for inputs and results.
4. Prompt the user to enter the first number and read it.
5. Prompt the user to enter the second number and read it.
6. Calculate:
   Sum = first number + second number
   Subtraction = first number - second number
   Multiplication = first number * second number
   Division = first number / second number
7. Display each result to the user.
8. End the program.

Key Concepts:
Input/Output Operations: Using cin to take user input and cout to display output.
Data Types: Usage of float to allow decimal numbers and store results.
Arithmetic Operators: +, -, *, and / are used to perform calculations.
Variable Declaration: Variables are declared to store inputs and results.
Program Flow: Sequential execution from input, calculation, to output.

Conclusion:
This program demonstrates the fundamental structure of a C++ program performing arithmetic calculations on user inputs. It reinforces the use of basic data types, input/output operations, and arithmetic operators. Users learn how to declare variables, accept input, process data, and display results. The program also highlights the importance of handling operations carefully, especially division, where a zero divisor can cause errors (to be handled in future improvements). Overall, this simple calculator program is a solid introduction to programming basics in C++.
