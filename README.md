# Calculator
This code defines four functions to perform basic arithmetic operations such as Addition, Subtraction, multiplication, division.

source code :

  
def add(a, b):
    return a + b


def subtract(a, b):
    return a - b

def multiply(a, b):
    return a * b


def divide(a, b):
    if b == 0:
        return "Error: division by zero"
    else:
        return a / b


num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))
op = input("Enter operation (+, -, *, /): ")


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


print("Result: ", result)



