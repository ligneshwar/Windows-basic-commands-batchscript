# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
mkdir %userprofile%\Desktop\MyLab
![image](https://github.com/ligneshwar/Windows-basic-commands-batchscript/assets/149365037/a0fccb5a-65a1-481d-9e35-f9cea78d5675)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
cd %userprofile%\Desktop\MyLab
![image](https://github.com/ligneshwar/Windows-basic-commands-batchscript/assets/149365037/8a77bf9b-4de8-48c0-8ea6-6419b0e9537b)
![image](https://github.com/ligneshwar/Windows-basic-commands-batchscript/assets/149365037/3a5a0820-3acb-4cd4-8658-5a4d902b0eec)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
dir %userprofile%\Desktop\MyLab
![image](https://github.com/ligneshwar/Windows-basic-commands-batchscript/assets/149365037/d552722c-0e22-494d-8ddc-d7c0447427dd)


## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
mkdir %userprofile%\Desktop\Backup
mkdir %userprofile%\Desktop\Backup
![image](https://github.com/ligneshwar/Windows-basic-commands-batchscript/assets/149365037/bdfecb42-f63a-4f11-8960-8edf0d706730)
![image](https://github.com/ligneshwar/Windows-basic-commands-batchscript/assets/149365037/75e25e0d-abd8-4b9f-98b5-f53339aea4f9)


## COMMAND AND OUTPUT

mv Myfile.txt %userprofile%\Documents
![image](https://github.com/ligneshwar/Windows-basic-commands-batchscript/assets/149365037/c3e2c4bc-eb88-4e0e-814f-040198ce0dd7)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.




@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!

## OUTPUT
![image](https://github.com/ligneshwar/Windows-basic-commands-batchscript/assets/149365037/f844eb42-7c9d-4bf6-83a1-8c1cf2de163a)

# RESULT:
The commands/batch files are executed successfully.

