Name : MADASU SRAVYA
Company: CODTECH IT SOLUTIONS
ID: CT08SP1069
Domain: Java programming
Durartion: 25th May 2024 to 25th July 2024
Mentor: SRAVANI GOUNI

Overview
Objective

To create a Java program that functions as a simple calculator. The program will prompt the user to input two numbers and select an operation (addition, subtraction, multiplication, or division). It will then perform the selected operation and display the result.

Key Components
User Input:

Numbers: The user is prompted to enter two numbers.
Operation Choice: The user is prompted to select an operation from a list (addition, subtraction, multiplication, division).
Operations:

Addition: Adds the two numbers.
Subtraction: Subtracts the second number from the first.
Multiplication: Multiplies the two numbers.
Division: Divides the first number by the second, with a check to prevent division by zero.
Output:

Displays the result of the chosen operation.
If the division operation is chosen and the second number is zero, an error message is displayed.
Program Flow:

Input Collection: Uses the Scanner class to collect user input for the numbers and the operation choice.
Operation Execution: Uses a switch statement to execute the chosen operation.
Result Display: Prints the result of the operation or an error message if applicable.
Detailed Steps
Import Required Class:

Import the Scanner class to handle user input.
Prompt for Numbers:

Ask the user to input the first and second numbers.
Store the numbers in double variables.
Display Operation Menu:

Display a menu with options for addition, subtraction, multiplication, and division.
Prompt the user to select an operation.
Read User Choice:

Read the user's choice and store it in an int variable.
Perform Selected Operation:

Use a switch statement to determine which operation to perform based on the user's choice.
For division, check if the second number is zero to prevent division by zero.
Display Result:

Print the result of the operation.
If division by zero is attempted, print an error message.
Close Scanner:

Close the Scanner object to free up resources.
Example
The program should work as follows:

User is prompted to enter two numbers (e.g., 10 and 5).
User is shown a menu of operations and selects one (e.g., 1 for addition).
The program performs the selected operation (e.g., 10 + 5).
The program displays the result (e.g., "Result: 15").
The Java code provided earlier implements these steps to create a functional simple calculator.

![Screenshot (6)](https://github.com/sravya1131/CODTECH-Task1/assets/112858180/d8451745-22ad-475d-ba0c-9ed55c3d0fe1)
