# Python-Assignment

def calculator():
    # Prompt user for two numbers
    num1 = float(input("Enter the first number:"))
    num2 = float(input("Enter the second number: "))

    # Prompt user for a mathematical operation
    operation = input("Choose an operation (addition, subtraction, multiplication, division): ").lower()

    # Perform the chosen operation and print the result
    if operation == "addition":
        print(f"The result of adding {num1} and {num2} is: {num1 + num2}")
    elif operation == "subtraction":
        print(f"The result of subtracting {num2} from {num1} is: {num1 - num2}")
    elif operation == "multiplication":
        print(f"The result of multiplying {num1} and {num2} is: {num1 * num2}")
    elif operation == "division":
        if num2 != 0:
            print(f"The result of dividing {num1} by {num2} is: {num1 / num2}")
        else:
            print("Error: Division by zero is not allowed.")
    else:
        print("Invalid operation. Please choose addition, subtraction, multiplication, or division.")

# Call the calculator function
calculator()
