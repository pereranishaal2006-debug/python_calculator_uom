# python_calculator_uom
python_calculator_uom
Python Calculator Assignment – Full Stack Developer Course (UoM)
Overview

In this assignment, you will create a simple calculator program from scratch using Python. The calculator will perform basic arithmetic operations and provide control commands for resetting or terminating the program.

Objectives
Write a Python program that performs arithmetic operations based on user input.
Implement a function select_op(choice) to choose the correct operation.
Handle all user input errors gracefully.
Ensure the program continues running until the user chooses to terminate.
Stage 1: Simple Calculator
Arithmetic Operations
Operator	Function Name	Description
+	add(a, b)	Addition
-	subtract(a, b)	Subtraction
*	multiply(a, b)	Multiplication
/	divide(a, b)	Division
^	power(a, b)	Exponentiation
%	remainder(a, b)	Modulus (Remainder)
Control Operations
Command	Description
#	Terminate program
$	Reset / Return to main menu
Program Behavior
Ask the user to select an operation (arithmetic or control).
Prompt the user to input two operands one at a time. Operands should be processed as floating-point numbers.
If the user makes a mistake while entering operands, they can press $ to return to the main menu.
Perform the calculation and display the result. Example: 2.0 + 4.0 = 6.0
Handle all possible errors, including:
Invalid numbers
Invalid arithmetic operators
Invalid control commands
Division by zero
Return to the main menu after each calculation.
The program keeps running until the user terminates it with #.
Tasks
Task 1: User Input
Step 1: Input arithmetic operation or control command.
Step 2: Input first and second operands (or reset/terminate if needed).
Task 2: Implement Arithmetic Functions
Write functions for all operations: add, subtract, multiply, divide, power, remainder.
Each function takes two operands and returns the result.
Task 3: Operation Selection
Implement select_op(choice) to call the correct arithmetic function based on user input.
Display the calculation result from within select_op(choice).
Example Messages to Display
"Enter first number: "
"Enter second number: "
"Not a valid number, please enter again"
"Unrecognized operation"
"Something went wrong"

Make sure these messages are displayed appropriately to help with auto-grading.
