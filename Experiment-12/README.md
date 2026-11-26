# EXPERIMENT 12 : AUTOMATE AN UNATTENDED ROBOT USING ORCHESTRATOR
## NAME : Hari Prasath E
## REG NO : 212225040107

## AIM:

To automate an unattended Robot process using UiPath Orchestrator.

## SOFTWARE REQUIRED:

- UiPath Studio
- UiPath Assistant
- UiPath Orchestrator Account
- Internet Connection

## ALGORITHM:

### Step 1:
Launch UiPath Studio and create a new Process named `UnattendedAutomation`.

### Step 2:
Design and save the required automation workflow.

### Step 3:
Click the Publish button in UiPath Studio.

### Step 4:
Select Orchestrator as the publishing destination and publish the process.

### Step 5:
Open UiPath Assistant and connect it to the Orchestrator instance.

### Step 6:
In Orchestrator, create a new Unattended Robot.

### Step 7:
Assign the Robot to the appropriate environment.

### Step 8:
Create a schedule in Orchestrator and assign it to the Robot.

### Step 9:
Run the Robot according to the configured schedule.

## PROCEDURE:

1. Open UiPath Studio and create a new Process named `UnattendedAutomation`.
2. Design a simple automation workflow.
3. Save the workflow.
4. Click Publish in UiPath Studio.
5. Select Orchestrator as the publishing destination.
6. Open UiPath Assistant and connect it to the Orchestrator instance.
7. Open Orchestrator and navigate to the Robots section.
8. Create a new Unattended Robot.
9. Assign the Robot to an environment.
10. Navigate to Schedules and create a new schedule.
11. Assign the process and Robot to the schedule.
12. Verify that the Robot executes the workflow automatically at the scheduled time.

## WORKFLOW:

```text
Start
  |
Create UiPath Process
  |
Design Workflow
  |
Publish to Orchestrator
  |
Connect UiPath Assistant
  |
Create Unattended Robot
  |
Assign Robot
  |
Create Schedule
  |
Execute Automatically
  |
End
```

# OUTPUT SCREENSHOTS:

## 1. Published Process in Orchestrator
![Published Process](Output/published-process.png)

## 2. Robot and Schedule Configuration
![Robot Schedule](Output/robot-schedule.png)

## 3. Execution Status
![Execution Status](Output/execution-status.png)

# RESULT:

Thus, an unattended Robot process was configured and automated using UiPath Orchestrator.
