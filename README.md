#Task 1: Read a File and Handle Errors 

try:
    file1= open('sample.txt','r') 
    print('Reading file content: ')
    reading_file= file1.readlines() 
    for i, line in enumerate(reading_file, start=1):
      print(f"Line {i}: {line.strip()}")
    file1.close()
except FileNotFoundError:
    print("Error: The file 'sample.txt' was not found.")




#Task 2: Write and Append Data to a File

with open("output.txt", "w") as file:
    user_input = input("Enter text to write to the file: ")
    file.write(user_input + "\n")
    print('Data sucessfully written to output.txt.')
    
with open("output.txt", "a") as file:
    extra_data = input("Enter additional text to append: ")
    file.write(extra_data + "\n")
    print('Data sucessfully appended.')
    
with open("output.txt", "r") as file:
    print("\nFinal content of output.txt:")
    print(file.read())





