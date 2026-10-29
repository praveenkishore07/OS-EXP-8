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

## COMMAND AND OUTPUT
<img width="587" height="225" alt="image" src="https://github.com/user-attachments/assets/f7c0f0cf-aed1-4748-9644-a980910ca6dc" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="487" height="37" alt="image" src="https://github.com/user-attachments/assets/ef6800d6-39e7-48e7-b0eb-cba58429eccc" />


Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="512" height="92" alt="image" src="https://github.com/user-attachments/assets/83779b7d-7e79-429d-9fbd-d346f7b38327" />

<img width="582" height="211" alt="image" src="https://github.com/user-attachments/assets/512cbf50-8936-4f0d-9b21-a257fd49196d" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

<img width="617" height="116" alt="image" src="https://github.com/user-attachments/assets/4fcaf0cf-11bd-48f1-8006-cb4f0fb4a395" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="588" height="57" alt="image" src="https://github.com/user-attachments/assets/7dc62e14-a99e-43e4-bf4b-0bee303d257d" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="445" height="42" alt="image" src="https://github.com/user-attachments/assets/08ddf9d6-bcd7-44f8-8c76-33fb1b505ec8" />

-
<img width="231" height="103" alt="image" src="https://github.com/user-attachments/assets/e4d3c037-cbe1-4b41-b6e7-310ed4a5f8e6" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="475" height="186" alt="image" src="https://github.com/user-attachments/assets/fbea4f4a-9526-4563-8950-eaa2ad060de2" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="552" height="655" alt="image" src="https://github.com/user-attachments/assets/108479b7-1702-41fe-9fad-921ab4b95c0d" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="521" height="178" alt="image" src="https://github.com/user-attachments/assets/372b567d-2c75-4c7c-8b01-42d13ebcd48a" />


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".


## OUTPUT

<img width="406" height="108" alt="image" src="https://github.com/user-attachments/assets/b59b8487-92f6-4b7e-8e00-f4017d2b9101" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.


## OUTPUT

<img width="491" height="207" alt="image" src="https://github.com/user-attachments/assets/df04e129-1bea-4839-9ccf-2cc6f7840df7" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.


## OUTPUT

<img width="392" height="172" alt="image" src="https://github.com/user-attachments/assets/5706cb53-8c2d-4682-81a8-9c130c26ce3d" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="626" height="235" alt="image" src="https://github.com/user-attachments/assets/c33a5ba2-a7b3-47ec-a6b8-2dec282912c3" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="442" height="390" alt="image" src="https://github.com/user-attachments/assets/995235da-e8c1-400a-8e16-ac20575d96be" />


# RESULT:
The commands/batch files are executed successfully.

