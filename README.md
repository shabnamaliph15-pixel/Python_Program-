#Task 1: Calculate Factorial Using a Function 

def factorial(n):
    if n == 0 or n == 1:
     return 1
    else:
     return n * factorial(n - 1)

num = int(input('Enter a number: '))
print(f"The factorial of {num} is: {factorial(num)}")




#Task 2: Using the Math Module for Calculations

import math
num = float(input('Enter a number: '))

square_root=math.sqrt(num)
natural_log=math.log(num)
sine_value=math.sin(num)

print(f"Square root: {square_root}")
print(f"logarithm: {natural_log}")
print(f"Sine: {sine_value}")

