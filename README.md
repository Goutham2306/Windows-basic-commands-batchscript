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
## PROGRAM:
```
DEVELOPED BY: Goutham.K
REGISTER NUMBER: 212223110019
```
# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND 

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
```
mkdir %userprofile%\Desktop\MyLab
cd %userprofile%\Desktop\MyLab
type nul > MyFile.txt
```
## OUTPUT:
![328008430-a1c2721d-1001-427a-86d3-765ebd0f3f5f](https://github.com/Goutham2306/Windows-basic-commands-batchscript/assets/138971154/d474ce16-74c5-46b7-87f3-bcdba10f4fc5)

## COMMAND 

List the contents of the "MyLab" directory.
```
dir %userprofile%\Desktop\MyLab
```
## OUTPUT:
![328008471-c973234c-300b-4f1c-80cc-e1d24bf73810](https://github.com/Goutham2306/Windows-basic-commands-batchscript/assets/138971154/5748ff6f-e826-4310-a324-4aa1e8101075)

## COMMAND

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
Move the "MyLab" directory to the "Documents" folder.
```
mkdir %userprofile%\Desktop\Backup
copy MyFile.txt %userprofile%\Desktop\Backup

```
## OUTPUT:
![328008536-6979b7c2-1b36-46b5-be15-a3bd81ddb664](https://github.com/Goutham2306/Windows-basic-commands-batchscript/assets/138971154/fbd7c279-cdec-4f21-b8d1-bf85238dbe08)



## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
```
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup

```
## OUTPUT
![328008608-e4a6d656-0066-4561-8be2-2dca4559497d](https://github.com/Goutham2306/Windows-basic-commands-batchscript/assets/138971154/9858e7fa-fa0d-4202-964d-bb9170669550)

## COMMAND
```
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx

```
## OUTPUT:
![328008645-2ce32f40-473f-4901-95cb-4ee2d7227ea4](https://github.com/Goutham2306/Windows-basic-commands-batchscript/assets/138971154/c69a9458-c48c-40c4-8b57-0331bc34b454)


# RESULT:
The commands/batch files are executed successfully.

