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
```
mkdir %userprofile%\Desktop\MyLab
```
![325137896-e20f8141-6596-43d5-b989-2d2dab0d0dda](https://github.com/sujigunasekar/Windows-basic-commands-batchscript/assets/119559822/b3b27bc1-569c-4699-8c50-a99140fed59d)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
```
cd %userprofile%\Desktop\MyLab
```
![325138032-d27849bc-c467-4873-8c79-f7428a160e8c](https://github.com/sujigunasekar/Windows-basic-commands-batchscript/assets/119559822/51afef5e-4fd7-4d7f-9040-81d59ef25f65)
![325138071-1fa80caf-e9f6-43b8-ae3b-32796202e14c](https://github.com/sujigunasekar/Windows-basic-commands-batchscript/assets/119559822/523a6846-989d-483d-b966-caec6ffd35ab)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
```
dir %userprofile%\Desktop\MyLab
```
![325138202-40de307a-60ec-44ed-a9d2-94ed73c8d346](https://github.com/sujigunasekar/Windows-basic-commands-batchscript/assets/119559822/947d5bfa-6ff5-4f60-a998-2538041f8e12)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
```
mkdir %userprofile%\Desktop\Backup mkdir %userprofile%\Desktop\Backup
```
![325138344-47278c6b-2a0d-45f3-bdb9-2f0cc267fbc3](https://github.com/sujigunasekar/Windows-basic-commands-batchscript/assets/119559822/940aae5a-041a-4ac3-a269-ce8478211472)
rectory to the "Documents" folder.
![325138398-364ae2ec-b6ff-4583-b92f-bbc9533b06d0](https://github.com/sujigunasekar/Windows-basic-commands-batchscript/assets/119559822/3a33cef7-f690-4607-a571-621b253a96b6)



## COMMAND AND OUTPUT
```
mv Myfile.txt %userprofile%\Documents
```
![325138492-99f98df3-adcf-47a5-befb-fdd0122af505](https://github.com/sujigunasekar/Windows-basic-commands-batchscript/assets/119559822/243c7e68-7cc8-4a44-bf18-38cce47a9817)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

```
@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!
```

## OUTPUT
![325138649-c9ec83f6-a056-4184-8124-df0c065cc7e9](https://github.com/sujigunasekar/Windows-basic-commands-batchscript/assets/119559822/71eb1e01-8fe1-4887-b29a-82a38dd48019)






# RESULT:
The commands/batch files are executed successfully.

