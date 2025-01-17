# task1
**COMPANY** CODETECH IT SOLUTIONS
**NAME** :  Rubika A
**INTERN ID** : CT08HCQ
**DOMAIN NAME ** :  C Programming
**BATCH DURATION **:  December 30th, 2024 to January 30th, 2025
**MENTOR NAME** :  Neela Santhosh Kumar
**DESCRIPTION OF THE TASK**

This C program demonstrates the fundamental operations of file handling, which include creating a file, writing data to it, appending additional data, and reading the contents of the file. Below is a breakdown of the functionality:

1. Create File
Functionality: Creates a new file with the specified filename using fopen in "w" mode.
If the file already exists, it is overwritten, but the program confirms successful creation.
Function Used:
c
Copy
Edit
create_file(const char *filename)
Opens the file in write mode (w).
Prints a message confirming the file creation.
2. Write to File
Functionality: Writes user-inputted data into the file, replacing any existing content.
Prompts the user to enter the text to write to the file.
Any previous content in the file is erased and replaced.
Function Used:
c
Copy
Edit
write_to_file(const char *filename, const char *data)
Opens the file in write mode (w).
Writes the provided data into the file and closes it.
3. Append to File
Functionality: Appends (adds) new data to the file without removing the existing content.
Prompts the user to enter text to add at the end of the file.
Function Used:
c
Copy
Edit
append_to_file(const char *filename, const char *data)
Opens the file in append mode (a).
Adds the user-inputted data to the end of the file.
4. Read File
Functionality: Reads and displays the content of the file line by line.
Helps verify what is written or appended to the file.
Function Used:
c
Copy
Edit
read_file(const char *filename)
Opens the file in read mode (r).
Reads the file line by line using fgets and displays it on the console.
5. Menu System
Provides an easy-to-use interactive menu for the user to choose different file operations:
1 - Create a new file.
2 - Write data into the file.
3 - Append data to the file.
4 - Read the file's contents.
5 - Exit the program.
Each menu choice directs to the corresponding file operation.
