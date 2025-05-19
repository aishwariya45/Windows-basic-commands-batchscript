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
![image](https://github.com/user-attachments/assets/f3c5ee6b-8ecc-44b3-8f89-65c56590b507)



## COMMAND AND OUTPUT

Remove the directory "my-folder"


![image](https://github.com/user-attachments/assets/c5afcc4c-834e-4579-8a43-b02167ae0ae7)



## COMMAND AND OUTPUT


Create the file Rose.txt

![image](https://github.com/user-attachments/assets/201dce86-bd9e-4272-b5a8-d6c4f7d28197)




## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection


![image](https://github.com/user-attachments/assets/8370e936-d120-4090-b626-f14ca6622473)



## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt

![image](https://github.com/user-attachments/assets/7e204137-fe4b-4215-b31a-ce7d5999d620)



## COMMAND AND OUTPUT

Remove the file hello1.txt
![image](https://github.com/user-attachments/assets/2de4b98c-0ad1-4fad-b754-6bd7527eba2e)


## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory
![image](https://github.com/user-attachments/assets/43e6ee7c-402c-46ce-900b-73d5c67fbc4e)


## COMMAND AND OUTPUT

List out all the associated file extensions 
![image](https://github.com/user-attachments/assets/43e6ee7c-402c-46ce-900b-73d5c67fbc4e)

## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt
![image](https://github.com/user-attachments/assets/bf212485-9a1c-418e-8c9e-db88d9fc4660)


## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
![image](https://github.com/user-attachments/assets/ad5b3547-16d7-45db-8507-098278b232e1)
![image](https://github.com/user-attachments/assets/8f216017-50ca-4370-82da-16e27f533339)



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
![image](https://github.com/user-attachments/assets/3e9d60fe-e0c2-45c7-b27f-73a675614f0f)




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

![image](https://github.com/user-attachments/assets/d9e9dc82-3b90-41b2-a76d-a364fa23e280)



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
![image](https://github.com/user-attachments/assets/d0687e58-7c93-43a3-98ec-034fdd334799)


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
![image](https://github.com/user-attachments/assets/01d5d489-342f-4a10-8df7-caf876eee9d7)



# RESULT:
The commands/batch files are executed successfully.

