# EXPERIMENT 5 : WEB SCRAPING DATA

## NAME : Hari Prasath E

## REG NO : 212225040107

## AIM:

To scrape data from a website using UiPath and save the extracted data into a CSV file.

## SOFTWARE REQUIRED:

- UiPath Studio
- Google Chrome or Microsoft Edge
- UiPath Web Automation Extension
- Internet Connection

## ALGORITHM:

### Step 1:
Open UiPath Studio and create a new Process project named `WebScrapingDemo`.

### Step 2:
Open the website `https://books.toscrape.com` using Google Chrome or Microsoft Edge.

### Step 3:
Open Main.xaml in UiPath Studio and select the Data Scraping option from the Design tab.

### Step 4:
Use the Data Scraping Wizard to select the first book title and the second similar book title.

### Step 5:
Select the price of the first and second books to extract the required data.

### Step 6:
Click Finish to generate the data scraping sequence.

### Step 7:
Add the Write CSV activity below the ExtractDataTable activity.

### Step 8:
Set the input as `ExtractDataTable` and file path as `C:\RPA\ScrapedData.csv`.

### Step 9:
Enable Add Headers and run the workflow.

### Step 10:
Open the generated CSV file and verify the extracted data.

## PROCEDURE:

1. Open UiPath Studio and create a new Process project named `WebScrapingDemo`.
2. Open Google Chrome or Microsoft Edge.
3. Navigate to `https://books.toscrape.com`.
4. Keep the website open and return to UiPath Studio.
5. Open Main.xaml and click Design > Data Scraping.
6. Click Next and select the first book title on the webpage.
7. Select the second similar book title when prompted.
8. Click Yes to extract correlated data.
9. Select the price of the first and second books.
10. Click Finish to generate the data scraping sequence.
11. Drag the Write CSV activity below the ExtractDataTable activity.
12. Set Input as `ExtractDataTable`.
13. Set File Path as `C:\RPA\ScrapedData.csv`.
14. Enable Add Headers.
15. Save and run the workflow.
16. Open the generated ScrapedData.csv file and verify the extracted data.

## WORKFLOW:

```text
        START
          |
          v
   Open UiPath Studio
          |
          v
   Create New Project
          |
          v
   Open Books Website
          |
          v
   Start Data Scraping Wizard
          |
          v
   Select Book Titles
          |
          v
   Select Book Prices
          |
          v
   Generate DataTable
          |
          v
   Write Data to CSV
          |
          v
   Run the Workflow
          |
          v
   Verify CSV File
          |
          v
         STOP
```

# OUTPUT SCREENSHOTS:

## 1. Data Scraping Workflow:
<img width="551" height="633" alt="image" src="https://github.com/user-attachments/assets/1a887a7a-cef5-4eff-9e24-bc7484957e27" />

## 2. Extracted CSV Output:
<img width="1916" height="1078" alt="image" src="https://github.com/user-attachments/assets/f57eb348-a9da-4684-b5c0-3667b38dbd60" />

# RESULT:

Thus, the web scraping process was successfully performed using UiPath. The book titles and prices were extracted from the website and saved into a CSV file.
