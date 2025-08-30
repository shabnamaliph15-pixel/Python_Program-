#Task 1: Perform Basic Mathematical Operations

num1 = int(input("Enter the first number: "))
num2 = int(input("Enter the second number: "))

addition = num1 + num2
subtraction = num1 - num2
multiplication = num1 * num2

if num2 != 0:
    division = num1 / num2
else:
    division = "Undefined (cannot divide by zero)"

print(f"Addition: {addition}")
print(f"Subtraction: {subtraction}")
print(f"Multiplication: {multiplication}")
print(f"Division: {division}")




#Task 2: Create a Personalized Greeting

first_name = input("Enter your first name: ")
last_name = input("Enter your last name: ")

full_name = first_name + " " + last_name
print(f"\nHello, {full_name}! Welcome to the program.")
