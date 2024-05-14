Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

AIM:
To execute Windows basic commands and batch scripting

DESIGN STEPS:
Step 1:
Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware

Step 2:
Write the Windows commands / batch file Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.

Step 3:
Execute the necessary commands/batch file for the desired output.

WINDOWS COMMANDS:
Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.

COMMAND AND OUTPUT
Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it. mkdir %userprofile%\Desktop\MyLab

![image](https://github.com/Alan-samuel/Windows-basic-commands-batchscript/assets/147091803/4aaad127-c8d8-4832-b33a-46ba178d69f9)


COMMAND AND OUTPUT
List the contents of the "MyLab" directory. cd %userprofile%\Desktop\MyLab image image

![image](https://github.com/Alan-samuel/Windows-basic-commands-batchscript/assets/147091803/2f6773a0-831e-47ce-92ff-bf03d003fec8)
![image](https://github.com/Alan-samuel/Windows-basic-commands-batchscript/assets/147091803/e15dda48-c8da-4887-9f39-9120635cb172)

COMMAND AND OUTPUT
Copy "MyFile.txt" to a new folder named "Backup" on the desktop. dir %userprofile%\Desktop\MyLab image

![image](https://github.com/Alan-samuel/Windows-basic-commands-batchscript/assets/147091803/2e38a3ef-5b18-43b8-a669-0e03dd2899a8)


COMMAND AND OUTPUT
Move the "MyLab" directory to the "Documents" folder. mkdir %userprofile%\Desktop\Backup mkdir %userprofile%\Desktop\Backup

![image](https://github.com/Alan-samuel/Windows-basic-commands-batchscript/assets/147091803/ccd5962b-ea88-4272-914a-8b6ce527854b)
![image](https://github.com/Alan-samuel/Windows-basic-commands-batchscript/assets/147091803/d5ca3319-d5c9-451a-831a-f492e728ec00)


COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents image
![image](https://github.com/Alan-samuel/Windows-basic-commands-batchscript/assets/147091803/32c1b8d9-4cad-469d-9519-d46625381e94)


Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!

OUTPUT
![image](https://github.com/Alan-samuel/Windows-basic-commands-batchscript/assets/147091803/2c6e935a-4804-4900-9ac1-2fb35ca5aa84)


RESULT:
The commands/batch files are executed successfully.
