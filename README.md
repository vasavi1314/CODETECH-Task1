# CODETECH-Task1
<h1><b>Intern</b></h1><br>
<b>Name:</b>V.vasavi Gayathri<br>
<b>College:</b>NRI Institute of Technology<br>
<b>Roll No:</b>22KP1A44E5<br>
<B>Company:</B>CODETECH IT SOLUTIONS<br>
<B>ID:</B>CT4PP3667<br>
<B>Domain:</B>PYTHON PROGRAMMING<br>
<B>Duration:</B>July to August 2024<br>
<B>Mentor:</B>Srvavani Gouni<br>
<h1>Project Overview</h1><br>
<h2>Sample code:</h2>
# Function to add two numbers
def add(x, y):
    return x + y


# Function to subtract two numbers
def subtract(x, y):
    return x - y


# Function to multiply two numbers
def multiply(x, y):
    return x * y


# Function to divide two numbers
def divide(x, y):
    if y == 0:
        return "Error! Division by zero."
    else:
        return x / y


def calculator():
    print("Select operation:")
    print("1. Add")
    print("2. Subtract")
    print("3. Multiply")
    print("4. Divide")

    # Take input from the user
    choice = input("Enter choice(1/2/3/4): ")

    # Check if the choice is one of the four options
    if choice in ['1', '2', '3', '4']:
        num1 = float(input("Enter first number: "))
        num2 = float(input("Enter second number: "))

        if choice == '1':
            print(f"{num1} + {num2} = {add(num1, num2)}")

        elif choice == '2':
            print(f"{num1} - {num2} = {subtract(num1, num2)}")

        elif choice == '3':
            print(f"{num1} * {num2} = {multiply(num1, num2)}")

        elif choice == '4':
            result = divide(num1, num2)
            print(f"{num1} / {num2} = {result}")

    else:
        print("Invalid input")
calculator()<br>
<h1>Output</h1><br>
![Screenshot 2024-07-14 151534](https://github.com/user-attachments/assets/b0a3054f-0c11-4f01-9a47-96a63d63b72a)


<h1><b>Objective:</b></h1><br>
The objective of this project is to design and develop a simple calculator using Python. This calculator will be capable of performing basic arithmetic operations such as addition, subtraction, multiplication, and division. The primary goals of this project are to:<br><br>
Understand the Basics of Python Programming: Gain a foundational understanding of Python syntax, data types, and control structures.<br>
Implement Arithmetic Operations: Develop functions to perform basic arithmetic operations and handle user inputs and outputs.<br>
Create a User-Friendly Interface: Design a simple text-based interface that allows users to interact with the calculator easily.<br>
<h1><b>Features:</b></h1>
<b>Basic Arithmetic Operations:</b>

Addition<br>
Subtraction<br>
Multiplication<br>
Division<br>
<b>User Input Handling:</b><br>

Ability to enter two numbers and an operator (+, -, *, /)<br>
Validation of user inputs to ensure they are numerical<br>
Prompt for re-entry if invalid inputs are detected<br>
<b>Error Handling:</b><br>

Manage division by zero errors gracefully<br>
Display appropriate error messages for invalid operations<br>
<h1><b>Explanation:</b></h1><br>
<b>Function Definitions:</b>

add, subtract, multiply, and divide functions perform the respective arithmetic operations.<br>
divide function includes error handling for division by zero.<br>
<b>User Input Handling:</b>

get_number function prompts the user for a number and includes validation to ensure the input is a valid number.<br>
get_operation function prompts the user for an operation and ensures it is one of the allowed operations (+, -, *, /).<br>
<b>Main Calculator Loop:</b>

calculator function manages the main loop of the program.<br>
Prompts the user for the first number, operation, and second number.<br>
Performs the chosen arithmetic operation.<br>
Displays the result.<br>
<h1><b>Conclusion</b></h1>
The simple calculator project in Python serves as a practical example for learning basic programming concepts and the fundamentals of the Python language. This project not only demonstrates the implementation of essential arithmetic operations but also highlights crucial programming skills such as user input validation, error handling, and creating a user-friendly interface.








