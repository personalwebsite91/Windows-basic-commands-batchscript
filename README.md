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
<img width="831" height="308" alt="image" src="https://github.com/user-attachments/assets/82f95112-d137-470b-a5b9-aa18eb58945b" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT

<img width="1121" height="481" alt="image" src="https://github.com/user-attachments/assets/ca3e64e5-c2c6-4310-8fa4-73e639628524" />

Create the file Rose.txt

## COMMAND AND OUTPUT

<img width="1065" height="471" alt="image" src="https://github.com/user-attachments/assets/593820c9-cfda-4fe5-a945-67b7722735ed" />

Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="1128" height="123" alt="image" src="https://github.com/user-attachments/assets/1fbd25dc-bbe3-4702-acb6-b47bf5afbcc4" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="1135" height="171" alt="image" src="https://github.com/user-attachments/assets/ecd20201-8a99-47bf-9ae6-88d9c0b24662" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="1082" height="297" alt="image" src="https://github.com/user-attachments/assets/24dd13b0-ce8c-42d8-b187-b626ac77827c" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="635" height="887" alt="image" src="https://github.com/user-attachments/assets/42af8f14-0705-4a06-9e39-4b2d4a83d3bf" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="670" height="887" alt="image" src="https://github.com/user-attachments/assets/0399870b-568d-4095-b2e4-45cdeb7ce346" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="647" height="153" alt="image" src="https://github.com/user-attachments/assets/a88cb4a7-446b-4dd2-9d83-2b22af3649ba" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="791" height="103" alt="image" src="https://github.com/user-attachments/assets/4ba44af1-02c6-4fdf-aaab-feb652447446" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="758" height="261" alt="image" src="https://github.com/user-attachments/assets/830cc515-f0e9-46dd-99c2-fc5a1ac5b1b1" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT


<img width="792" height="227" alt="image" src="https://github.com/user-attachments/assets/13186dbe-084c-4510-ab22-5ff5e046128f" />


Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="818" height="502" alt="image" src="https://github.com/user-attachments/assets/cdbb9b82-03db-447d-b192-f1e46d613ddb" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT



# RESULT:
The commands/batch files are executed successfully.

