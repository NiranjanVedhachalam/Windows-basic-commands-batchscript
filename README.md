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

<img width="440" height="51" alt="Screenshot 2026-09-05 090050" src="https://github.com/user-attachments/assets/057fdd4c-76d7-4c57-a768-d4b76ccfae4c" />




Remove the directory "my-folder"

## COMMAND AND OUTPUT

<img width="483" height="56" alt="Screenshot 2026-09-05 090132" src="https://github.com/user-attachments/assets/6fcb4f18-ee69-4e54-add4-a9f14874c19b" />


Create the file Rose.txt

## COMMAND AND OUTPUT

<img width="562" height="45" alt="Screenshot 2026-09-05 090230" src="https://github.com/user-attachments/assets/ea8e44ab-ce3b-4f2c-b8b2-6bcb55c0c0e4" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

<img width="592" height="46" alt="Screenshot 2026-09-05 090252" src="https://github.com/user-attachments/assets/389261cd-b348-4abe-a2cc-bbf49384cbf0" />


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT

<img width="701" height="72" alt="Screenshot 2026-09-05 090309" src="https://github.com/user-attachments/assets/99791295-9c4d-4834-908d-82a81200f33c" />


Remove the file hello1.txt

## COMMAND AND OUTPUT

<img width="468" height="52" alt="Screenshot 2026-09-05 090324" src="https://github.com/user-attachments/assets/df80d01d-808f-4bd7-b835-e4abc69c2f1c" />



List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT

<img width="505" height="188" alt="Screenshot 2026-09-05 090345" src="https://github.com/user-attachments/assets/90d32acc-75ff-4fbe-8930-52ed4bd6a60e" />



List out all the associated file extensions 

## COMMAND AND OUTPUT

<img width="1450" height="1065" alt="Screenshot 2026-09-05 090419" src="https://github.com/user-attachments/assets/20efbaa3-dda2-411a-8497-59301deb7d59" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

<img width="718" height="162" alt="Screenshot 2026-09-05 090453" src="https://github.com/user-attachments/assets/ba0bc5e9-a79d-4667-8990-b9668cd8b40f" />



## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="472" height="97" alt="Screenshot 2026-09-05 091216" src="https://github.com/user-attachments/assets/693f0379-7711-497e-b7d6-7b982a8424aa" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="785" height="233" alt="Screenshot 2026-09-05 091220" src="https://github.com/user-attachments/assets/0093978c-bf2f-46a8-b6f1-e9c3a1b02fd7" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="560" height="185" alt="Screenshot 2026-09-05 091224" src="https://github.com/user-attachments/assets/63aa02a8-67ca-4ecd-ab46-bd436c522ba8" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT


<img width="507" height="83" alt="Screenshot 2026-09-05 091228" src="https://github.com/user-attachments/assets/4a006661-10c3-4710-ae45-cdf43796320e" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT


<img width="610" height="227" alt="Screenshot 2026-09-05 091235" src="https://github.com/user-attachments/assets/c01d46c0-913b-47c1-b92f-cf0ea7d0ce9c" />

<img width="542" height="205" alt="Screenshot 2026-09-05 091241" src="https://github.com/user-attachments/assets/17b6db53-e8f0-4395-836b-569ae04052bf" />


<img width="595" height="230" alt="Screenshot 2026-09-05 091248" src="https://github.com/user-attachments/assets/f2ab561a-b96c-4569-976a-e586f45551fd" />


# RESULT:
The commands/batch files are executed successfully.

