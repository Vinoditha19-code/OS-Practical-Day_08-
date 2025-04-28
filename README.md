# OS-Practical-Day_08-

Input Numbers and Operator:The script prompts the user to enter two numbers and an operator (+, -, *, /). This provides the inputs needed for the calculator.
Handle Arithmetic Operations Using expr:
Addition (+): Uses expr to add the two numbers.
Subtraction (-): Uses expr to subtract the second number from the first.
Multiplication (*): Uses expr with an escaped asterisk (\*) to multiply the numbers.
Division (/): Uses expr to divide the numbers, with a check to avoid division by zero.

Invalid Operator Handling:If the user enters an invalid operator, the script outputs an error message and exits.

Division by Zero:The script explicitly checks if the second number is zero before performing division. If it is, it outputs an error message and exits without performing the operation.

Display the Result:After performing the selected operation, the result is displayed.

Make the Script Executable:The chmod +x simple_calculator.sh command makes the script executable so that it can be run.

Execution:The script is executed with ./simple_calculator.sh
