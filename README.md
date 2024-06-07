# If_Statement-While-Statement-Writing-Function-Lambda-Function

Understanding Memory Location in Python
Every object in Python is stored at a specific memory location. The id function returns the memory address of an object, and the hex function can convert this address to a hexadecimal representation.

id(x): Returns the memory location of the object x.
hex(id(x)): Converts the memory location to a hexadecimal string.
When two variables have the same value, Python optimizes memory usage by storing them in the same memory location, a behavior known as interning.

Example
Declaring x = 20 and y = 20 will point both x and y to the same memory location.

Identity Operator is

Understanding is and ==

is: Checks if two variables point to the same object in memory.
==: Checks if the values of two variables are equal.

Example
x is y will be True if x and y refer to the same object.
x == y will be True if x and y have the same value.

If Statements

Conditional Statements in Python

=: Used for assignment.
==: Used for comparison.

Syntax

if condition:
Code block to execute if condition is true.
elif condition:
Code block to execute if previous conditions are false and this condition is true.
else:
Code block to execute if all previous conditions are false.
Example
Checking if two variables x and y are equal and executing code based on the comparison.
Loops in Python
While Loop
Executes a block of code repeatedly as long as a condition is true.

while condition:
Code block to execute.
Break and Continue
break: Exits the loop immediately.
continue: Skips the current iteration and moves to the next iteration.
Example
Using a while loop to print a message multiple times.
Using break to exit the loop under a specific condition.
Using continue to skip an iteration under a specific condition.

User Input

Getting Input from User
input(prompt): Prompts the user for input and returns it as a string.
int(input(prompt)): Converts the user input to an integer.

Example
Prompting the user to enter their name and age, and then displaying a greeting message.
Functions

Defining and Using Functions
def function_name(parameters):
Code block to execute when the function is called.
return: Returns a value from the function.

Example
Creating a function to calculate the square of a number.
Creating a function to print the day of the week based on a numeric input.

Docstrings
Used for documentation purposes.
Enclosed in triple quotes (''' or """).

Example
Adding a docstring to a function to describe its purpose, input, and output.

Lambda Functions
Anonymous Functions in Python
Lambda Functions: Small, anonymous functions defined using the lambda keyword.

Syntax: lambda arguments: expression.
Example
Creating a lambda function to calculate the square of a number.
Creating a lambda function to calculate the product of two numbers.

This readme file provides an overview of fundamental Python concepts, including memory locations, identity operators, conditional statements, loops, user input, functions, docstrings, and lambda functions. Understanding these basics will help in writing efficient and readable Python code.
