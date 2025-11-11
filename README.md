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

<img width="420" height="75" alt="Screenshot 2025-11-11 110538" src="https://github.com/user-attachments/assets/c95d2a3a-0305-485a-b49c-f66cb780b1df" />

## COMMAND AND OUTPUT

Remove the directory "my-folder"

<img width="409" height="43" alt="Screenshot 2025-11-11 110551" src="https://github.com/user-attachments/assets/d241c214-0553-43fc-a2b4-dd37b9872bf4" />

## COMMAND AND OUTPUT


Create the file Rose.txt

<img width="491" height="298" alt="Screenshot 2025-11-11 110610" src="https://github.com/user-attachments/assets/21e00993-8823-44a2-a24b-d4971d49c3b2" />

## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection

<img width="559" height="99" alt="Screenshot 2025-11-11 110629" src="https://github.com/user-attachments/assets/c853feed-5838-4941-9c34-364cf2cf86d9" />

## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt

<img width="487" height="108" alt="Screenshot 2025-11-11 110652" src="https://github.com/user-attachments/assets/1b1da5d3-fe7a-4bfe-a60f-70ff79512e10" />

## COMMAND AND OUTPUT

Remove the file hello1.txt

<img width="402" height="41" alt="Screenshot 2025-11-11 110716" src="https://github.com/user-attachments/assets/cc27faf2-d2fe-4563-8771-484e6d338bab" />

## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

<img width="440" height="148" alt="Screenshot 2025-11-11 110744" src="https://github.com/user-attachments/assets/8da1f2ec-9c6b-48df-a7d3-39420ff09861" />

## COMMAND AND OUTPUT

List out all the associated file extensions

<img width="606" height="719" alt="Screenshot 2025-11-11 110815" src="https://github.com/user-attachments/assets/4ed0c00e-fff2-4b81-b54e-a81288cd244c" />

## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt

<img width="472" height="167" alt="Screenshot 2025-11-11 110835" src="https://github.com/user-attachments/assets/74606c2b-dd65-4d84-b1a6-39050e355f6f" />

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

## OUTPUT

<img width="373" height="85" alt="Screenshot 2025-11-11 111317" src="https://github.com/user-attachments/assets/5db60fb1-db46-4026-a6d1-e960b5ecbc50" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.


## OUTPUT

<img width="511" height="193" alt="Screenshot 2025-11-11 111436" src="https://github.com/user-attachments/assets/fb540407-14c7-46fc-8073-27e2ee64da78" />


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="367" height="155" alt="image" src="https://github.com/user-attachments/assets/0ca994e1-192f-4e2c-91c6-02136ce0ac19" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="357" height="86" alt="image" src="https://github.com/user-attachments/assets/6f4e2b71-4e2b-430d-902f-d5a42bfc5f5d" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="415" height="353" alt="image" src="https://github.com/user-attachments/assets/e9c9d12a-e44b-4da4-a79a-fd9e41dabc2f" />


# RESULT:
The commands/batch files are executed successfully.

