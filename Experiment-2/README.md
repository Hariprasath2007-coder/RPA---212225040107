# EXPERIMENT 2 : WELCOME MESSAGE WITH IF CONDITION AND SWITCH CASE

## NAME : Hari Prasath E
## REG NO : 212225040107

## AIM:

To create a workflow in UiPath Studio that displays a custom welcome message based on user input using IF Condition and Switch Case activities.

## SOFTWARE REQUIRED:

- UiPath Studio
- Windows Operating System

## ALGORITHM:

### Part A: Using IF Condition

### Step 1:
Launch UiPath Studio from the desktop or Start menu.

### Step 2:
Click on **New Project → Process**.

### Step 3:
In the project creation dialog box:
- Enter the process name as `WelcomeMessageIf`.
- Select the project location.
- Click **Create**.

### Step 4:
Once the project opens, double-click `Main.xaml` to open the main workflow.

### Step 5:
Open the Variables panel and search for the **Input Dialog** activity in the Activities panel.

### Step 6:
Drag and drop the Input Dialog activity into the main sequence.

### Step 7:
Configure the Input Dialog properties:
- Title: `Enter Name`
- Label: `What is your name?`
- Output variable: `userName` (String)

### Step 8:
Search for the **If** activity and drag it below the Input Dialog.

### Step 9:
Enter the following condition in the If activity:

```vb
userName.ToUpper = "RAM"
```

### Step 10:
In the Then section, add a Message Box with:

```vb
"Welcome Mr. Ramachandran"
```

In the Else section, add another Message Box with:

```vb
"Welcome " + userName
```

### Step 11:
Save the workflow using `Ctrl + S` and click the **Run** button.

### Part B: Using Switch Case

### Step 1:
Use the Input Dialog activity to get the user's name and store it in the `userName` variable.

### Step 2:
Search for the **Switch** activity and drag it below the Input Dialog.

### Step 3:
Set the Switch properties:
- Expression: `userName.ToUpper`
- TypeArgument: `String`

### Step 4:
Add the following cases in the Switch activity:

- Case `ALICE`: Display `Welcome Alice! Have a great day.`
- Case `BOB`: Display `Hi Bob! Welcome back.`
- Case `CHARLIE`: Display `Hello Charlie, glad to see you!`

### Step 5:
In the Default section, add a Message Box with:

```vb
"Hello " + userName + ", Welcome!"
```

### Step 6:
Save the workflow and click the **Run** button to execute it.

## PROCEDURE:

1. Open UiPath Studio and create a new Process project named `WelcomeMessageIf`.
2. Open the `Main.xaml` file.
3. Add an Input Dialog activity to get the user's name.
4. Configure the Title, Label and output variable properties.
5. For Part A, add an If activity and set the condition as `userName.ToUpper = "RAM"`.
6. Add the required Message Box activities in the Then and Else sections.
7. Run the workflow and test different names.
8. For Part B, add a Switch activity after the Input Dialog.
9. Set the Expression as `userName.ToUpper` and TypeArgument as `String`.
10. Add ALICE, BOB and CHARLIE cases with their respective Message Box activities.
11. Add a Default Message Box for other names.
12. Save and execute the workflow.

## WORKFLOW:

### Part A: IF Condition

The workflow uses an Input Dialog to get the user's name and an If activity to display a welcome message based on the entered name.

```text
          START
             |
             v
        Input Dialog
             |
             v
       Store userName
             |
             v
 userName.ToUpper = "RAM"?
        /          \
      YES           NO
       |             |
       v             v
 Welcome Mr.     Welcome +
 Ramachandran    userName
       \             /
        \           /
             v
            END
```

### Part B: Switch Case

The workflow uses an Input Dialog to get the user's name and a Switch activity to display different welcome messages.

```text
          START
             |
             v
        Input Dialog
             |
             v
       Store userName
             |
             v
         Switch Case
       /      |       \
    ALICE    BOB    CHARLIE
      |       |        |
      v       v        v
   Welcome  Hi Bob   Hello
    Alice! Welcome! Charlie
       \      |       /
        \     |      /
             v
          DEFAULT
             |
             v
       Welcome Message
             |
             v
            END
```

# OUTPUT SCREENSHOTS:

## 1. IF Condition Workflow.
![IF Condition Workflow](Output/if-workflow.png)

## 2. IF Condition Execution Output.
![IF Condition Output](Output/if-output.png)

## 3. Switch Case Workflow.
![Switch Case Workflow](Output/switch-workflow.png)

## 4. Switch Case Execution Output.
![Switch Case Output](Output/switch-output.png)

# RESULT:

Thus, the UiPath workflow was successfully created and executed using IF Condition and Switch Case activities to display custom welcome messages based on the user's input.
