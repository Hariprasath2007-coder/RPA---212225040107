# EXPERIMENT 11 : API INTEGRATION AND DATA PROCESSING
## NAME : Hari Prasath E
## REG NO : 212225040107

## AIM:

To call a REST API, process the JSON response and write the extracted data into a database using UiPath.

## SOFTWARE REQUIRED:

- UiPath Studio
- Internet Connection
- UiPath.WebAPI.Activities Package
- SQL Server or another supported database
- Weather API Access

## ALGORITHM:

### Step 1:
Launch UiPath Studio and create a new Process named `APIIntegration`.

### Step 2:
Open Manage Packages and install the UiPath.WebAPI.Activities package.

### Step 3:
Open Main.xaml and add the HTTP Request activity.

### Step 4:
Set the HTTP method to GET and provide the Weather API endpoint.

### Step 5:
Use the Deserialize JSON activity to process the response content.

### Step 6:
Extract the required weather information, such as temperature and humidity, using JSON expressions.

### Step 7:
Add the database Insert activity and configure the database connection.

### Step 8:
Insert the extracted weather data into the database.

### Step 9:
Save and run the workflow.

## PROCEDURE:

1. Open UiPath Studio and create a new Process named `APIIntegration`.
2. Open Manage Packages and install UiPath.WebAPI.Activities.
3. Add the HTTP Request activity to Main.xaml.
4. Set the method to GET.
5. Enter the Weather API endpoint with the required API key.
6. Add the Deserialize JSON activity and provide the HTTP response content.
7. Extract temperature and humidity from the JSON response.
8. Add the database Insert activity.
9. Configure the database connection string.
10. Insert the extracted weather information into the database.
11. Save and run the workflow.
12. Verify that the data is stored in the database.

## WORKFLOW:

```text
Start
  |
Send HTTP GET Request
  |
Receive API Response
  |
Deserialize JSON
  |
Extract Weather Data
  |
Connect to Database
  |
Insert Weather Data
  |
Data Saved
  |
End
```

# OUTPUT SCREENSHOTS:

## 1. API Integration Workflow
![API Workflow](Output/api-workflow.png)

## 2. Extracted Data and Database Output
![API Output](Output/api-output.png)

# RESULT:

Thus, weather information was successfully retrieved from a REST API, processed from JSON format and stored in a database using UiPath.
