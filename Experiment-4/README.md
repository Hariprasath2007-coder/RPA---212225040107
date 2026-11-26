# EXPERIMENT 4 : READ AND WRITE EXCEL DATA

## NAME : Hari Prasath E

## REG NO : 212225040107

## AIM:

To read data from an Excel file and write the retrieved data into another Excel file using UiPath Workbook activities.

## SOFTWARE REQUIRED:

- UiPath Studio
- Windows Operating System
- WPS Office

## ALGORITHM:

### Step 1:
Create a new UiPath project named `ExcelReadWrite`.

### Step 2:
Create a folder named `ExcelData` and prepare an Excel file named `InputData.xlsx` containing sample data with Name, Age, and City columns.

### Step 3:
Open UiPath Studio and create a Sequence in the Main workflow.

### Step 4:
Add the Read Range (Workbook) activity to read data from the input Excel file.

### Step 5:
Set the workbook path, sheet name, and range. Store the retrieved data in a DataTable variable named `dtData`.

### Step 6:
Add the Write Range (Workbook) activity below the Read Range activity.

### Step 7:
Set the output workbook path as `OutputData.xlsx`, specify the sheet name and starting cell, and provide `dtData` as the input.

### Step 8:
Save and run the workflow to transfer the data from the input Excel file to the output Excel file.

## PROCEDURE:

1. Open UiPath Studio and create a new project named `ExcelReadWrite`.
2. Create a folder named `C:\RPA\ExcelData`.
3. Create an Excel file named `InputData.xlsx` with the following sample data:

   | Name | Age | City |
   |---|---|---|
   | Ravi | 28 | Delhi |
   | Sita | 24 | Mumbai |

4. Open the Main workflow and add a Sequence activity.
5. Search for and add the Read Range (Workbook) activity.
6. Configure the input workbook path, sheet name, and range.
7. Create a DataTable variable named `dtData` to store the retrieved data.
8. Add the Write Range (Workbook) activity below the Read Range activity.
9. Configure the output workbook path as `C:\RPA\ExcelData\OutputData.xlsx`.
10. Set the sheet name and starting cell, and provide `dtData` as the input.
11. Save and execute the workflow.
12. Open `OutputData.xlsx` and verify that the input data has been successfully written.

## WORKFLOW:

```text
          START
            |
            v
     Create InputData.xlsx
            |
            v
       Read Range
       (Workbook)
            |
            v
     Store Data in dtData
            |
            v
       Write Range
       (Workbook)
            |
            v
      Create OutputData.xlsx
            |
            v
       Verify Output
            |
            v
           END
```

# OUTPUT SCREENSHOTS:

### 1. Input Excel Data
<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/bb48fc32-30c0-4b58-9b38-951997f5013a" />


### 2. Complete UiPath Workflow
<img width="388" height="516" alt="image" src="https://github.com/user-attachments/assets/ffe8d2bd-d294-4b7d-8d27-6a5672b7cf0d" />


### 3. Output Excel Data
<img width="1915" height="1078" alt="image" src="https://github.com/user-attachments/assets/65c4d7f2-e17d-43ff-aac2-f1ec1617573d" />


# RESULT:

Thus, the Excel data was successfully read from `InputData.xlsx` using the Read Range (Workbook) activity and written into `OutputData.xlsx` using the Write Range (Workbook) activity in UiPath.
