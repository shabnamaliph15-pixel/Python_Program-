#Task 1: Check if a Number is Even or Odd

a = int(input('Enter a number: '))
if a%2==0:
    print(f"{a} is an even number.")
else:
    print(f"{a} is an odd number.")




#Task 2: Sum of Integers from 1 to 50 Using a Loop

total_sum=0
for num in range(1,51):
    total_sum += num
print(" The sum of integeres from 1 to 50: ", total_sum)

