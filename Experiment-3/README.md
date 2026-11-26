# EXPERIMENT 3 : FLOW SEQUENCE OR FLOW CHART USING REPEAT, WHILE AND DO-WHILE LOOPS

## NAME : Hari Prasath E
## REG NO : 212225040107

## AIM:

To understand and implement different loop structures in UiPath using Flowchart or Sequence.

## SOFTWARE REQUIRED:

- UiPath Studio
- Windows Operating System

## ALGORITHM:

### Part A: Repeat (Using Assign + While)

### Step 1:
Launch UiPath Studio from the desktop or Start menu.

### Step 2:
Click on **New Project → Process**.

### Step 3:
In the project creation dialog box:
- Enter the process name as `LoopingDemo`.
- Select the project location.
- Click **Create**.

### Step 4:
Once the project opens, double-click `Main.xaml` to open the main workflow.

### Step 5:
Select the Sequence workflow and open the Variables panel.

### Step 6:
Create the following variables:

- `variable1` → Int32 → Default: 1
- `variable2` → Int32 → Default: 5
- `variable3` → Boolean → Default: True

### Step 7:
Search for the **Assign** activity in the Activities panel and drag it into the Sequence.

### Step 8:
Set the Assign properties:
- To: `variable1`
- Value: `1`

### Step 9:
Search for the **While** activity and drag it below the Assign activity.

### Step 10:
Set the While condition as:

```vb
variable1 <= variable2
```

### Step 11:
Inside the While activity, add a Message Box and enter:

```vb
"Count: " + variable1.ToString
```

### Step 12:
Below the Message Box, add another Assign activity inside the While loop.

Set the properties:
- To: `variable1`
- Value: `variable1 + 1`

### Step 13:
After the While activity, add a Message Box with the text:

```vb
"Loop ended"
```

### Part B: Do-While Example

### Step 1:
Search for the **Do While** activity in the Activities panel.

### Step 2:
Drag the Do While activity below the previous workflow activities.

### Step 3:
Inside the Do While activity, add a Message Box with the text:

```vb
"This block runs at least once"
```

### Step 4:
Below the Message Box, add an Assign activity inside the Do While activity.

Set the properties:
- To: `variable3`
- Value: `False`

### Step 5:
Set the Do While condition as:

```vb
variable3 = True
```

### Step 6:
Save the workflow using `Ctrl + S` and click the **Run** button.

## PROCEDURE:

1. Open UiPath Studio and create a new Process project named `LoopingDemo`.
2. Open the `Main.xaml` file and select the Sequence workflow.
3. Create three variables: `variable1` (Int32), `variable2` (Int32) and `variable3` (Boolean).
4. Set their default values as 1, 5 and True respectively.
5. Add an Assign activity to initialize `variable1 = 1`.
6. Add a While activity with the condition `variable1 <= variable2`.
7. Inside the While loop, add a Message Box to display the counter value.
8. Add an Assign activity to increment `variable1` by 1.
9. Add a Message Box after the While loop to display `Loop ended`.
10. Add a Do While activity below the While workflow.
11. Inside the Do While activity, add a Message Box and an Assign activity to set `variable3 = False`.
12. Set the Do While condition as `variable3 = True`.
13. Save and execute the workflow.

## WORKFLOW:

The workflow uses Assign and While activities to display numbers from 1 to 5. The Do While activity displays a message at least once before checking its condition.

```text
              START
                 |
                 v
        Assign variable1 = 1
                 |
                 v
     While variable1 <= variable2
                 |
                 v
       Display Count: variable1
                 |
                 v
    Assign variable1 = variable1 + 1
                 |
                 v
             While End
                 |
                 v
        Display "Loop ended"
                 |
                 v
             Do While
                 |
                 v
   Display "This block runs at least once"
                 |
                 v
       Assign variable3 = False
                 |
                 v
       Check variable3 = True
                 |
                 v
                END
```

# OUTPUT SCREENSHOTS:

## 1. While Loop Workflow.
<img width="753" height="660" alt="image" src="https://github.com/user-attachments/assets/6e1d5267-7b18-4ee7-90cc-3fc4b9a66339" />

## 2. While Loop Execution Output.
<img width="691" height="351" alt="image" src="https://github.com/user-attachments/assets/aad21b5a-f24f-4fe0-baa3-81324420dbb3" />

## 3. Do-While Workflow.
<img width="505" height="508" alt="image" src="https://github.com/user-attachments/assets/046cb01b-e10d-45ca-8fd2-89d6c7f14829" />

## 4. Do-While Execution Output.
<img width="675" height="293" alt="image" src="https://github.com/user-attachments/assets/b3bd5779-7c14-471e-a664-a65dabb1774b" />

# RESULT:

Thus, the UiPath workflow was successfully created and executed using Assign, While and Do While activities to understand and implement different looping structures.

