# EXPERIMENT 6 : COPY AND RENAME FILES

## NAME : Hari Prasath E

## REG NO : 212225040107

## AIM:

To copy all files from a source folder to a destination folder and rename them by appending a timestamp to their file names using UiPath.

## SOFTWARE REQUIRED:

- UiPath Studio
- Windows Operating System

## ALGORITHM:

### Step 1:
Create a folder named `SourceFolder` and place some sample files inside it.

### Step 2:
Create another folder named `DestinationFolder` to store the copied files.

### Step 3:
Create a new UiPath Process project named `CopyAndRenameFiles`.

### Step 4:
Create variables `sourcePath` and `destinationPath` of type String to store the folder paths.

### Step 5:
Create a variable `files` of type Array of String to store the file paths.

### Step 6:
Use the Assign activity with `Directory.GetFiles(sourcePath)` to get all files from the source folder.

### Step 7:
Use a For Each activity to process every file in the files array.

### Step 8:
Extract the file name and extension from each file.

### Step 9:
Generate a timestamp and append it to the original file name.

### Step 10:
Use the Copy File activity to copy each file to the destination folder with the updated file name.

### Step 11:
Run the workflow and verify the copied and renamed files in the destination folder.

## PROCEDURE:

1. Create a folder named `SourceFolder` and place some sample files inside it.
2. Create another folder named `DestinationFolder`.
3. Open UiPath Studio and create a new Process project named `CopyAndRenameFiles`.
4. Open Main.xaml and create the required variables.
5. Assign the source folder path to `sourcePath`.
6. Assign the destination folder path to `destinationPath`.
7. Use the Assign activity to retrieve all files using `Directory.GetFiles(sourcePath)`.
8. Add a For Each activity to iterate through the files.
9. Extract the file name and extension.
10. Generate a timestamp for each file.
11. Create the new file name by appending the timestamp.
12. Use Copy File to copy the file into the destination folder with the new name.
13. Save and run the workflow.
14. Verify that all files are copied and renamed successfully.

## WORKFLOW:

```text
        START
          |
          v
    Create Folders
          |
          v
    Set Folder Paths
          |
          v
    Get Files from Source
          |
          v
    For Each File
          |
          v
    Extract File Name
          |
          v
    Generate Timestamp
          |
          v
    Create New File Name
          |
          v
    Copy File to Destination
          |
          v
    Process Next File
          |
          v
    Verify Destination Folder
          |
          v
         STOP
```

# OUTPUT SCREENSHOTS:

### 1. Main Workflow

| Screenshot 1 | Screenshot 2 |
|---|---|
| <img width="737" height="607" alt="image" src="https://github.com/user-attachments/assets/4f38d75f-a980-4b22-8c99-0460070eea3f" /> | <img width="707" height="626" alt="image" src="https://github.com/user-attachments/assets/2640e61c-2354-481c-b9ca-3935f1a2845d" />|

### 2. Copy File Activity

| Screenshot 3 | Screenshot 4 |
|---|---|
| <img width="1006" height="533" alt="image" src="https://github.com/user-attachments/assets/06bd8c00-fc58-47cb-ae15-7e5d2ccdcc1c" /> | <img width="1005" height="487" alt="image" src="https://github.com/user-attachments/assets/4bcfafbe-eaae-4d64-a049-3e226af80cbe" />|
# RESULT:

Thus, all files were successfully copied from the source folder to the destination folder and renamed by appending a timestamp to their file names using UiPath.
