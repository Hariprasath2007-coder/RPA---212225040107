# EXPERIMENT 13 : INVOICE PROCESSING AUTOMATION USING OCR
## NAME : Hari Prasath E
## REG NO : 212225040107

## AIM:

To process an invoice PDF using OCR, extract the Invoice Number, Date and Total Amount, and enter the extracted information into an Excel file using UiPath.

## SOFTWARE REQUIRED:

- UiPath Studio
- Sample Invoice PDF
- Microsoft Excel
- UiPath.OCR.Activities Package

## ALGORITHM:

### Step 1:
Launch UiPath Studio and create a new Process named `InvoiceProcessing`.

### Step 2:
Open Manage Packages and install the UiPath.OCR.Activities package.

### Step 3:
Open Main.xaml and add the Read PDF with OCR activity.

### Step 4:
Set the input property to the path of the invoice PDF file.

### Step 5:
Select an OCR engine such as Microsoft OCR or Google Cloud OCR.

### Step 6:
Extract the Invoice Number, Date and Total Amount from the OCR output using string manipulation or regular expressions.

### Step 7:
Create an Excel file to store the extracted invoice information.

### Step 8:
Use the Write Range activity to write the extracted details into the Excel file.

### Step 9:
Save and run the workflow.

## PROCEDURE:

1. Open UiPath Studio and create a new Process named `InvoiceProcessing`.
2. Open Manage Packages.
3. Search for and install UiPath.OCR.Activities.
4. Open Main.xaml.
5. Add the Read PDF with OCR activity.
6. Set the input property to the invoice PDF file path.
7. Select an OCR engine.
8. Extract the Invoice Number, Date and Total Amount from the OCR output.
9. Create an Excel file with columns for Invoice Number, Date and Total Amount.
10. Add the Write Range activity.
11. Enter the extracted information into the Excel file.
12. Save and run the workflow.
13. Verify the extracted invoice details in Excel.

## WORKFLOW:

```text
Start
  |
Read Invoice PDF
  |
Perform OCR
  |
Extract Invoice Details
  |
Get Invoice Number
  |
Get Invoice Date
  |
Get Total Amount
  |
Write Data to Excel
  |
Save Excel File
  |
End
```

# OUTPUT SCREENSHOTS:

## 1. Invoice Processing Workflow
![Invoice Workflow](Output/invoice-workflow.png)

## 2. Extracted Invoice Details in Excel
![Invoice Excel Output](Output/invoice-excel-output.png)

# RESULT:

Thus, invoice details were successfully extracted from a PDF using OCR and stored in an Excel file using UiPath.
