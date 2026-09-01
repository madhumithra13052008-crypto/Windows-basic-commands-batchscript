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

Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="525" height="152" alt="Screenshot 2026-09-01 162044" src="https://github.com/user-attachments/assets/e2a762d1-c686-452b-ad74-3c5f88fb5567" />


Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="643" height="367" alt="Screenshot 2026-09-01 161042" src="https://github.com/user-attachments/assets/100c84ed-5324-475b-83a2-1058590869fc" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="592" height="117" alt="Screenshot 2026-09-01 161109" src="https://github.com/user-attachments/assets/3821a908-e8b9-4fcd-aaec-a65e5eb64397" />


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="533" height="128" alt="Screenshot 2026-09-01 161126" src="https://github.com/user-attachments/assets/8d2323fe-e959-4f3e-b271-b4e5253b8c4a" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="495" height="227" alt="Screenshot 2026-09-01 161142" src="https://github.com/user-attachments/assets/10f26dc1-35cc-4b7e-9f9b-610bff52624b" />

List out the file hello1.txt in the current directory


List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="537" height="778" alt="Screenshot 2026-09-01 161214" src="https://github.com/user-attachments/assets/7e7a6e1d-8bc8-4d2e-9f78-94ab0ef6fbf5" />



Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="517" height="202" alt="Screenshot 2026-09-01 161233" src="https://github.com/user-attachments/assets/42aa8987-b9de-4dc5-ae28-602ccb70cb95" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT



# RESULT:
The commands/batch files are executed successfully.

