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
<h1>Output</h1>
<img src="![image](https://github.com/user-attachments/assets/e0dde2bf-5367-452a-a9b5-41103420cebc)"/>






