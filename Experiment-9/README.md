# EXPERIMENT 9 : KEYBOARD AUTOMATION - SIMULATE KEYSTROKES
## NAME : Hari Prasath E
## REG NO : 212225040107

## AIM:

To simulate typing and keyboard shortcuts in a desktop application like Notepad using UiPath.

## SOFTWARE REQUIRED:

- UiPath Studio
- Windows Operating System
- Notepad

## ALGORITHM:

### Step 1:
Launch UiPath Studio and create a new Process named `KeyboardAutomation`.

### Step 2:
Open Main.xaml and add the Start Process activity.

### Step 3:
Set the FileName property to `C:\Windows\System32\notepad.exe` to launch Notepad.

### Step 4:
Add the Type Into activity and indicate the Notepad window.

### Step 5:
Enter the text "Hello, this is automated typing!".

### Step 6:
Add the Send Hotkey activity and set the shortcut to Ctrl + S.

### Step 7:
Add another Type Into activity to enter the file name as `TestFile.txt`.

### Step 8:
Add the Click activity to select the Save button.

### Step 9:
Save and run the workflow.

## PROCEDURE:

1. Open UiPath Studio and create a new Process named `KeyboardAutomation`.
2. Open Main.xaml.
3. Add the Start Process activity.
4. Set the FileName property to `C:\Windows\System32\notepad.exe`.
5. Add the Type Into activity and indicate the Notepad window.
6. Enter the text "Hello, this is automated typing!".
7. Add the Send Hotkey activity and configure Ctrl + S.
8. Add Type Into to enter `TestFile.txt` in the Save As dialog.
9. Add the Click activity and indicate the Save button.
10. Save and run the workflow.
11. Verify that the text file is created successfully.

## WORKFLOW:

```text
Start
  |
Launch Notepad
  |
Type Text
  |
Send Ctrl + S
  |
Enter File Name
  |
Click Save
  |
File Saved
  |
End
```

# OUTPUT SCREENSHOTS:

## 1. Keyboard Automation Workflow
![Keyboard Workflow](Output/keyboard-workflow.png)

## 2. Saved Notepad File
![Notepad Output](Output/notepad-output.png)

# RESULT:

Thus, keyboard automation was successfully performed in Notepad using UiPath, and the text file was saved automatically.
