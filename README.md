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





