# Python program for simple calculator.

nano calculator.py
python calculator.py

# Addition of two numbers
def add(a, b):
    return a + b

# Subtraction of two numbers
def subtract(a, b):
    return a - b

# Multiplication of two numbers
def multiply(a, b):
    return a * b

# Division of two numbers
def divide(a, b):
    return a / b

print("Select operation.")
print("1.Add")
print("2.Subtract")
print("3.Multiply")
print("4.Divide")

# Prompt the user to input two numbers and an operation choice.

num1 = int(input('Enter your first number: '))
num2 = int(input('Enter your second number: '))

print(num1 + num2)
