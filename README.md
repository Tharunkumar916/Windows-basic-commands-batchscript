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

<img width="351" height="46" alt="2" src="https://github.com/user-attachments/assets/1f24285b-400a-4350-a924-7dfc04c61dff" />

## COMMAND AND OUTPUT
Remove the directory "my-folder"

<img width="540" height="46" alt="3" src="https://github.com/user-attachments/assets/f6749413-808d-490b-bec4-e7ec3399beb0" />

## COMMAND AND OUTPUT
Create the file Rose.txt

<img width="582" height="42" alt="4" src="https://github.com/user-attachments/assets/99e2e314-48e8-4492-9fa6-dbb67fefdba8" />

## COMMAND AND OUTPUT
Create the file hello.txt using echo and redirection

<img width="677" height="42" alt="5" src="https://github.com/user-attachments/assets/9dabb6d8-fb05-4190-8a59-e4e9510fed19" />

## COMMAND AND OUTPUT
Copy the file hello.txt into the file hello1.txt

<img width="855" height="58" alt="6" src="https://github.com/user-attachments/assets/c16b0959-6dda-4af3-a397-ed0440ece767" />

## COMMAND AND OUTPUT
Remove the file hello1.txt

<img width="562" height="111" alt="7" src="https://github.com/user-attachments/assets/f5949bd5-e69d-485e-a527-80c64ce71700" />

## COMMAND AND OUTPUT
List out the file hello1.txt in the current directory

<img width="353" height="150" alt="14" src="https://github.com/user-attachments/assets/84864f6f-678d-46d0-b3f4-6da04521e6ab" />

## COMMAND AND OUTPUT
List out all the associated file extensions 

<img width="542" height="1108" alt="8" src="https://github.com/user-attachments/assets/3f23e06a-6566-4367-b644-6f02b0972b30" />

## COMMAND AND OUTPUT
Compare the file hello.txt and rose.txt

<img width="500" height="401" alt="15" src="https://github.com/user-attachments/assets/e5a28029-4ff1-429e-85f1-1658a80981b9" />

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

<img width="365" height="133" alt="9" src="https://github.com/user-attachments/assets/f8153557-0d26-41ae-8201-0f62e0fa67a3" />

## OUTPUT
Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.

<img width="452" height="186" alt="10" src="https://github.com/user-attachments/assets/5f7f09c9-2709-453b-a97b-83f1a221f26d" />

## OUTPUT
Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.

<img width="446" height="191" alt="11" src="https://github.com/user-attachments/assets/079f3b3d-c95c-412a-8b12-48510071e335" />

## OUTPUT
Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

<img width="416" height="112" alt="12" src="https://github.com/user-attachments/assets/e0bfc9b5-1e36-4e0c-ba0e-4e3c4146507c" />

## OUTPUT
Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.

<img width="376" height="571" alt="13" src="https://github.com/user-attachments/assets/dcfaaf83-1985-47d0-bdfd-82d48efd38bd" />

# RESULT:
The commands/batch files are executed successfully.
