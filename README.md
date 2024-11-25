# Ex08-Windows-basic-commands-batchscript

### Name: Anbuselvan.S
### Register No: 212223240008
### Date:

## AIM:
To execute Windows basic commands and batch scripting
**@@ -24,42 +23,53 @@ Execute the necessary commands/batch file for the desired output**

## WINDOWS COMMANDS:

### Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.

#### COMMAND AND OUTPUT:

**Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.**
```
%userprofile%\Desktop\MyLab
```

#### COMMAND AND OUTPUT:

**List the contents of the "MyLab" directory.**
```
%userprofile%\Desktop\MyLab
```

#### COMMAND AND OUTPUT:

**Copy "MyFile.txt" to a new folder named "Backup" on the desktop.**
```
%userprofile%\Desktop\MyLab
```

#### COMMAND AND OUTPUT:

**Move the "MyLab" directory to the "Documents" folder.**
```
mkdir %userprofile%\Desktop\Backup mkdir %userprofile%\Desktop\Backup
```

#### COMMAND AND OUTPUT:

```
mv Myfile.txt %userprofile%\Documents
```

### Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

```
@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!
```

## OUTPUT
![image](https://github.com/user-attachments/assets/da88c4df-6263-4713-904e-97461b033ba4)

## RESULT:
The commands/batch files are executed successfully.

