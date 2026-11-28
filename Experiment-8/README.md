# EXPERIMENT 8 : BASIC WEB AUTOMATION - FILL A WEB FORM
## NAME : Hari Prasath E
## REG NO : 212225040107

## AIM:

To automate filling out a simple web form with user data and submit it using UiPath.

## SOFTWARE REQUIRED:

- UiPath Studio
- Google Chrome or Microsoft Edge
- Internet Connection

## ALGORITHM:

### Step 1:
Launch UiPath Studio and create a new Process named `WebFormAutomation`.

### Step 2:
Open the Main.xaml file and add the Open Browser activity.

### Step 3:
Set the URL to `https://www.w3schools.com/html/html_forms.asp`.

### Step 4:
Add the Type Into activity and indicate the Name input field in the browser.

### Step 5:
Enter the name as "John Doe".

### Step 6:
Add Type Into activities for the remaining fields, such as Email and Country.

### Step 7:
Add the Click activity and indicate the Submit button.

### Step 8:
Save and run the workflow to automatically fill and submit the form.

## PROCEDURE:

1. Open UiPath Studio and create a new Process named `WebFormAutomation`.
2. Open Main.xaml.
3. Add the Open Browser activity and enter the required website URL.
4. Add the Type Into activity and indicate the Name field.
5. Enter the name as "John Doe".
6. Add Type Into activities for Email and Country fields.
7. Add the Click activity and indicate the Submit button.
8. Save and run the workflow.
9. Verify that the form is filled and submitted successfully.

## WORKFLOW:

```text
Start
  |
Open Browser
  |
Navigate to Web Form
  |
Enter Name
  |
Enter Email
  |
Enter Country
  |
Click Submit
  |
Form Submitted
  |
End
```

# OUTPUT SCREENSHOTS:

## 1. Web Form Automation Workflow
| Screenshot 1 | Screenshot 2 |
|---|---|
| <img width="652" height="605" alt="image" src="https://github.com/user-attachments/assets/2f9cdfa1-0cfa-4a6c-aece-17b725b37c53" /> | <img width="563" height="567" alt="image" src="https://github.com/user-attachments/assets/c4809068-76c2-4d24-a07d-420e2bcc715f" /> |

## 2. Filled and Submitted Web Form
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f6ec77d8-7111-45c7-b625-8d3a55b6c829" />


# RESULT:

Thus, the web form was successfully filled with user data and submitted automatically using UiPath.
