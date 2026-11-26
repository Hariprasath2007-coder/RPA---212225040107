# EXPERIMENT 10 : EMAIL AUTOMATION - SEND EMAIL
## NAME : Hari Prasath E
## REG NO : 212225040107

## AIM:

To send an email from a Gmail account using UiPath.

## SOFTWARE REQUIRED:

- UiPath Studio
- Gmail Account
- Internet Connection
- UiPath.Mail.Activities Package

## ALGORITHM:

### Step 1:
Launch UiPath Studio and create a new Process named `EmailAutomation`.

### Step 2:
Open Manage Packages and install the UiPath.Mail.Activities package.

### Step 3:
Open Main.xaml and add the Send SMTP Mail Message activity.

### Step 4:
Enter the sender's Gmail address and recipient's email address.

### Step 5:
Set the Subject as "Test Email from UiPath".

### Step 6:
Set the Body as "This is a test email sent from UiPath!".

### Step 7:
Configure the SMTP settings:
- Host: smtp.gmail.com
- Port: 587
- Secure Connection: StartTls
- User: Gmail address
- Password: Gmail App-Specific Password

### Step 8:
Save and run the workflow to send the email.

## PROCEDURE:

1. Open UiPath Studio and create a new Process named `EmailAutomation`.
2. Open Manage Packages.
3. Search for and install UiPath.Mail.Activities.
4. Open Main.xaml.
5. Add the Send SMTP Mail Message activity.
6. Enter the sender and recipient email addresses.
7. Enter the subject and email body.
8. Configure the SMTP host, port, secure connection, username and app-specific password.
9. Save and run the workflow.
10. Verify that the recipient receives the email.

## WORKFLOW:

```text
Start
  |
Configure SMTP Settings
  |
Enter Sender Email
  |
Enter Recipient Email
  |
Enter Subject and Body
  |
Send Email
  |
Email Sent
  |
End
```

# OUTPUT SCREENSHOTS:

## 1. Email Automation Workflow
![Email Workflow](Output/email-workflow.png)

## 2. Received Email in Gmail
![Email Output](Output/email-output.png)

# RESULT:

Thus, an email was successfully sent from a Gmail account using UiPath SMTP automation.
