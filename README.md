# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 



# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

<img width="447" height="131" alt="Screenshot 2025-11-03 054416" src="https://github.com/user-attachments/assets/75a7e1fe-4f86-40b7-a953-009805e75540" />


## COMMAND AND OUTPUT

Remove the directory "my-folder"

<img width="439" height="122" alt="Screenshot 2025-11-03 054613" src="https://github.com/user-attachments/assets/de7bef8e-dacd-486d-a259-29cc2cb3b8d4" />


## COMMAND AND OUTPUT

Create the file Rose.txt

<img width="602" height="196" alt="Screenshot 2025-11-03 060525" src="https://github.com/user-attachments/assets/f90fe898-ca66-4a15-97dc-bcc39c601e6e" />

<img width="700" height="301" alt="Screenshot 2025-11-03 060553" src="https://github.com/user-attachments/assets/2558083e-efdd-409f-b97e-30084e6e7bf6" />


## COMMAND AND OUTPUT

Create the file hello.txt using echo and redirection

<img width="716" height="137" alt="Screenshot 2025-11-03 060658" src="https://github.com/user-attachments/assets/e34f1bab-7209-4d40-af2f-39bb376bc319" />


## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt

<img width="627" height="143" alt="Screenshot 2025-11-03 060812" src="https://github.com/user-attachments/assets/165fadf4-eb89-47e5-964e-1c17a32b985c" />


## COMMAND AND OUTPUT

Remove the file hello1.txt

<img width="624" height="198" alt="Screenshot 2025-11-03 060959" src="https://github.com/user-attachments/assets/8b65f291-d6d5-469d-b66b-1a307d26f5fd" />


## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

<img width="1910" height="1079" alt="Screenshot 2025-11-03 061039" src="https://github.com/user-attachments/assets/60a9098c-51e4-40c3-94c5-e6fac2736e44" />


## COMMAND AND OUTPUT

List out all the associated file extensions 

<img width="656" height="1041" alt="image" src="https://github.com/user-attachments/assets/95217f14-e0a1-4e63-be04-187e5fa9b4cd" />


## COMMAND AND OUTPUT

Compare the file hello.txt and rose.txt

<img width="670" height="249" alt="Screenshot 2025-11-03 061216" src="https://github.com/user-attachments/assets/ccb38c8f-86ff-499b-aa9c-206352581fa8" />


## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

## OUTPUT

<img width="469" height="121" alt="Screenshot 2025-11-06 085558" src="https://github.com/user-attachments/assets/76aba164-82b2-422a-b3fe-466fdabd3fc3" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.


## OUTPUT


<img width="662" height="223" alt="Screenshot 2025-11-06 090041" src="https://github.com/user-attachments/assets/0dd06e46-d87a-4d4c-bc40-1f09a5f28632" />


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.


## OUTPUT

<img width="710" height="183" alt="Screenshot 2025-11-06 090157" src="https://github.com/user-attachments/assets/deceeb55-ef6a-4407-8aa4-985fa1918447" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="438" height="161" alt="Screenshot 2025-11-06 090429" src="https://github.com/user-attachments/assets/28ab3e83-ed4b-41f0-ace6-020904281623" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="438" height="426" alt="Screenshot 2025-11-06 090537" src="https://github.com/user-attachments/assets/6d44b75e-1e40-4822-8b30-49d9e0cacaf9" />

# RESULT:
The commands/batch files are executed successfully.

