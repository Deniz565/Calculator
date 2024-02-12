# Calculator
This Python script implements a simple console-based calculator that allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division. The calculator runs in a continuous loop, presenting a menu of operations for the user to choose from. It prompts the user to enter two numbers and then performs the selected operation, displaying the result.

Functions:

add(x, y): Performs addition of two numbers x and y.
subtract(x, y): Performs subtraction of y from x.
multiply(x, y): Performs multiplication of two numbers x and y.
divide(x, y): Performs division of x by y. Handles the case where division by zero is attempted.
Menu Options:

Addition (1): Adds two numbers.
Subtraction (2): Subtracts the second number from the first.
Multiplication (3): Multiplies two numbers.
Division (4): Divides the first number by the second. Handles division by zero.
Exit (5): Exits the calculator.
Usage:

The user is prompted to select an operation by entering the corresponding number (1 to 5).
After selecting an operation, the user is asked to input two numbers.
The chosen operation is performed on the input numbers, and the result is displayed.
The program continues to run until the user chooses to exit (option 5).
Note: The calculator uses a continuous loop (while True) to allow users to perform multiple calculations without restarting the program. The loop can be exited by selecting option 5.
