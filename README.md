# Calculator
This code defines four functions to perform basic arithmetic operations such as Addition, Subtraction, multiplication, division.

source code :

  # Define function to perform addition
def add(a, b):
    return a + b

# Define function to perform subtraction
def subtract(a, b):
    return a - b

# Define function to perform multiplication
def multiply(a, b):
    return a * b

# Define function to perform division
def divide(a, b):
    if b == 0:
        return "Error: division by zero"
    else:
        return a / b

# Get user input for operands and operation
num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))
op = input("Enter operation (+, -, *, /): ")

# Perform operation based on user input
if op == '+':
    result = add(num1, num2)
elif op == '-':
    result = subtract(num1, num2)
elif op == '*':
    result = multiply(num1, num2)
elif op == '/':
    result = divide(num1, num2)
else:
    result = "Invalid operation"

# Print the result
print("Result: ", result)



