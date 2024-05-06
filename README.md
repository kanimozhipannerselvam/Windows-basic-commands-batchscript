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

![325137896-e20f8141-6596-43d5-b989-2d2dab0d0dda](https://github.com/kanimozhipannerselvam/Windows-basic-commands-batchscript/assets/119476060/8bb474b0-1be8-4e95-9ad7-d028c7062d9b)



## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
cd %userprofile%\Desktop\MyLab
![325138032-d27849bc-c467-4873-8c79-f7428a160e8c](https://github.com/kanimozhipannerselvam/Windows-basic-commands-batchscript/assets/119476060/42642f95-f2f3-434b-8254-1fe3dde4a63f)

![325138071-1fa80caf-e9f6-43b8-ae3b-32796202e14c](https://github.com/kanimozhipannerselvam/Windows-basic-commands-batchscript/assets/119476060/cab5438c-3312-4786-870f-13dc95f3d851)



## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
dir %userprofile%\Desktop\MyLab

![325138202-40de307a-60ec-44ed-a9d2-94ed73c8d346](https://github.com/kanimozhipannerselvam/Windows-basic-commands-batchscript/assets/119476060/03105aa6-403d-42fa-970f-a3364ec6dc91)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
mkdir %userprofile%\Desktop\Backup
mkdir %userprofile%\Desktop\Backup

![325138344-47278c6b-2a0d-45f3-bdb9-2f0cc267fbc3](https://github.com/kanimozhipannerselvam/Windows-basic-commands-batchscript/assets/119476060/d206e7b6-2a44-4668-abdc-f9d880d247c5)
![325138398-364ae2ec-b6ff-4583-b92f-bbc9533b06d0](https://github.com/kanimozhipannerselvam/Windows-basic-commands-batchscript/assets/119476060/9b8e5a04-7b50-416b-93f4-b890a2e29c54)



## COMMAND AND OUTPUT

mv Myfile.txt %userprofile%\Documents
![325138492-99f98df3-adcf-47a5-befb-fdd0122af505](https://github.com/kanimozhipannerselvam/Windows-basic-commands-batchscript/assets/119476060/63564ed0-789c-4b0a-b3ee-4eac6949ddf8)



## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.


@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!




## OUTPUT

![325138649-c9ec83f6-a056-4184-8124-df0c065cc7e9](https://github.com/kanimozhipannerselvam/Windows-basic-commands-batchscript/assets/119476060/14f88e5a-a2ea-4074-a91d-6c43a18a5814)





## RESULT:
The commands/batch files are executed successfully.

