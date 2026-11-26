# EXPERIMENT 14 : CAPSTONE PROJECT - AUTOMATED STUDENT REPORT GENERATION.
## NAME : Hari Prasath E
## REG NO : 212225040107

## AIM:

To develop a real-world automation project using UiPath by reading student details from an Excel file, processing the information and generating a student report automatically.

## SOFTWARE REQUIRED:

- UiPath Studio
- Microsoft Excel
- Windows Operating System

## ALGORITHM:

### Step 1:
Launch UiPath Studio and create a new Process named `StudentReportAutomation`.

### Step 2:
Prepare an Excel file containing student details such as Register Number, Name, Department and Marks.

### Step 3:
Open Main.xaml and add the Use Excel File activity.

### Step 4:
Use the Read Range activity to read the student details from the Excel file.

### Step 5:
Process the student records and calculate the total and average marks.

### Step 6:
Use conditional statements to determine the result based on the average marks.

### Step 7:
Create an output Excel file to store the processed student details.

### Step 8:
Use the Write Range activity to write the generated report into the output file.

### Step 9:
Save and run the workflow.

## PROCEDURE:

1. Open UiPath Studio and create a new Process named `StudentReportAutomation`.
2. Create an Excel file named `StudentData.xlsx`.
3. Enter student details such as Register Number, Name, Department and Marks.
4. Open Main.xaml and add the Use Excel File activity.
5. Set the input Excel file path.
6. Add the Read Range activity to read the student records into a DataTable.
7. Process the records and calculate the total and average marks.
8. Use an If condition to determine the result.
9. Add the Write Range activity to save the processed information into `StudentReport.xlsx`.
10. Save and run the workflow.
11. Verify the generated student report.

## WORKFLOW:

```text
Start
  |
Read Student Excel File
  |
Extract Student Details
  |
Process Student Records
  |
Calculate Total and Average
  |
Determine Result
  |
Generate Student Report
  |
Write Data to Excel
  |
Save Report
  |
End
```

# OUTPUT SCREENSHOTS:

## 1. Student Report Automation Workflow
![Student Report Workflow](Output/student-report-workflow.png)

## 2. Input Student Data
![Student Input](Output/student-input.png)

## 3. Generated Student Report
![Student Report Output](Output/student-report-output.png)

# RESULT:

Thus, the student report generation process was successfully automated using UiPath by reading, processing and writing student information into an Excel file.
