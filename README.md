
# Automation of Data Collection from  PDFs

Automating the extraction of data from PDFs and storing it in Excel files can greatly streamline data processing workflows. Python, with its robust libraries, offers powerful tools to accomplish this task efficiently.

The ideation behind this workflow is to save the effort of manually entering data from PDFs and create a structured format (Excel, CSV, SQL tables) for reporting and insights purposes.

This is the prototype of work that I performed during my work experience in collaboration with several teams like Finance, Membership/Loyalty, Claims, and Marketing to fulfill data requests with significant effort savings.


## Description
In many organizations, critical data is often stored in PDF documents due to their universal accessibility and ability to preserve formatting across different platforms. However, manually extracting and processing data from PDFs is a time-consuming and error-prone task. This manual effort hinders efficiency, delays decision-making, and increases the likelihood of data inaccuracies. To address this challenge, there is a need to automate the data extraction process, ensuring accurate and timely retrieval of information.

**Solution**
To address these challenges, we propose the development of an automated data extraction system using Python. The solution will include the following features:

1)**Automated Extraction:** Utilize Python libraries (e.g., PDFMiner) to programmatically extract data from PDF documents.

2)**Data Parsing and Transformation:** Implement NLP algorithms to parse and transform the extracted data into structured formats (e.g., CSV, Excel) suitable for analysis and reporting.

**Expected Outcomes**
**Increased Efficiency:** Significantly reduce the time and effort required to extract data from PDFs, leading to faster data processing and availability.

**Timely Reporting:** Enable quicker turnaround times for data reporting and analysis, supporting more timely and informed decision-making.

**Steps:**

1) Imported the PDFs into Jupyter Notebook(Python)

2) Converted the PDFs content to the text.

3) Searched the pattters to extract the information.

4) Stored the data inot the DataFrame(Structured Format).

5) Loaded the data to SQL Server Data base.

6) Now data is avaialble in the tabular format for further analysis.
## Workflow

![App Screenshot](https://github.com/agaur2095/Automation/blob/main/pdf%20to%20db.jpg?raw=True)

## Tech Stack

**PDF Scrapping(Extraction):** Python libraries(Pandas, RE, pdfminer)

**Transform:** Pandas, Numpy

**Load:** sqlalchemy


## Code Snippet and Output

**Input PDF:**

![App Screenshot](https://github.com/agaur2095/Automation/blob/main/PDF_sample.png?raw=True)


**Output of all the Invoices**

![App Screenshot](https://github.com/agaur2095/Automation/blob/main/PDF_op.png?raw=True)


**Final Usable Format**

![App Screenshot](https://github.com/agaur2095/Automation/blob/main/Excel_op.png?raw=True)
## Applications

**Finance** 
1) Budgeting and Forecasting: Extracting financial data from reports to create detailed budgets and forecasts in Excel.

2) Expense Tracking: Aggregating and analyzing expense reports for better financial management.

**Data Analysis and Reporting**

1) Dashboards and KPIs: Creating dashboards to track key performance indicators (KPIs) by compiling data from various PDF reports.

2) Customer Data Analysis: Converting customer information from PDF forms and surveys into Excel for detailed analysis.
## 🚀 About Me

I am a data enthusiast who boosts the performance of reporting and insights systems by incorporating various data strategies to enhance reporting, dashboarding, predictions, and insights.

