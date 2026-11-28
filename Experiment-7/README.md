# EXPERIMENT 7 : READ AND EXTRACT TEXT FROM PDF

## NAME : Hari Prasath E

## REG NO : 212225040107

## AIM:

To extract text from a PDF file using UiPath and save the extracted content into a text file.

## SOFTWARE REQUIRED:

- UiPath Studio
- Windows Operating System
- Sample PDF File

## ALGORITHM:

### Step 1:
Create a new UiPath Process project named `PDFTextExtraction`.

### Step 2:
Prepare a sample PDF file containing some text.

### Step 3:
Open Main.xaml and create a Sequence workflow.

### Step 4:
Create a String variable named `pdfText` to store the extracted text.

### Step 5:
Use the Read PDF Text activity and provide the input PDF file path.

### Step 6:
Store the extracted PDF content in the `pdfText` variable.

### Step 7:
Use the Write Text File activity to save the extracted content.

### Step 8:
Set the output file path as `C:\RPA\ExtractedText.txt`.

### Step 9:
Run the workflow and open the generated text file.

### Step 10:
Verify that the extracted text matches the content of the PDF file.

## PROCEDURE:

1. Open UiPath Studio.
2. Create a new Process project named `PDFTextExtraction`.
3. Open Main.xaml and add a Sequence activity.
4. Prepare a sample PDF file containing text.
5. Search for the Read PDF Text activity in the Activities panel.
6. Drag the activity into the Sequence.
7. Set the PDF file path in the activity.
8. Create a String variable named `pdfText` and assign it as the output.
9. Search for the Write Text File activity.
10. Drag it below the Read PDF Text activity.
11. Set the output file path as `C:\RPA\ExtractedText.txt`.
12. Set the text content as `pdfText`.
13. Save and run the workflow.
14. Open the generated text file and verify the extracted content.

## WORKFLOW:

```text id="pdf7flow"
        START
          |
          v
    Open UiPath Studio
          |
          v
    Create New Project
          |
          v
      Select PDF File
          |
          v
     Read PDF Text
          |
          v
    Store Extracted Text
          |
          v
    Write Text File
          |
          v
    Save Extracted Content
          |
          v
    Verify Text File
          |
          v
         STOP
```

# OUTPUT SCREENSHOTS:

## 1. PDF Text Extraction Workflow:
<img width="540" height="493" alt="image" src="https://github.com/user-attachments/assets/8dbb80af-aaef-4438-b55a-71df82b47a38" />

## 2. Extracted Text File Output:
| Sample.pdf | Output.txt |
|---|---|
| <img width="1042" height="890" alt="image" src="https://github.com/user-attachments/assets/31025cd7-651b-404e-a121-3a064d64f779" /> | <img width="512" height="465" alt="image" src="https://github.com/user-attachments/assets/373011ec-7948-4d88-88d6-b97cc1dd0ffd" />|
# RESULT:

Thus, text was successfully extracted from a PDF file using UiPath and saved into a text file.
