# KPMG Data Analytics Project: Data Quality Assessment, Insights, and Dashboard Creation

Welcome to the GitHub repository for the Business Analyst Internship project. This project involves assessing data quality, generating insights to target high-value customers, and creating a dashboard to assist the client in targeting specific customer segments.In this virtual internship, a dataset of KPMG client, Sprocket Central has been provided for data quality checks, visualization of customer trends and behavior existing customer. 

The data set has 3 sheets or tables for customer demographics, transaction and new customer list. The project aim was to recommend high value customers based on the customer demographics and attributes 


## Table of Contents

1. [Project Overview](#project-overview)
2. [Task 1: Data Quality Assessment](#task-1-data-quality-assessment)
3. [Task 2: Data Insights](#task-2-data-insights)
4. [Task 3: Dashboard Creation](#task-3-dashboard-creation)
5. [Installation and Setup](#installation-and-setup)


## Project Overview

This project aims to:
- Assess and ensure the quality and completeness of the data.
- Generate insights to identify high-value customers based on demographics and attributes.
- Create a dashboard for the client to help target specific customer segments and the broader market.

## Task 1: Data Quality Assessment

### Step 1: Assess Data Quality
- **Data Completeness**:
  - Check for missing values in the dataset.
  - Identify incomplete records and fields with a high percentage of missing data.

- **Data Consistency**:
  - Ensure consistency in data formats (e.g., dates, categorical values).
  - Check for duplicate entries and inconsistencies.

- **Data Accuracy**:
  - Verify the accuracy of the data against known standards or through sample checks.
  - Identify any outliers or anomalies that may indicate errors.

### Step 2: Mitigate Data Quality Issues
- **Data Cleaning**:
  - Handle missing values through imputation or removal of affected records.
  - Standardize data formats and correct inconsistencies.

- **Draft Email to Client**:
  - Prepare an email to the client summarizing the identified data quality issues.
  - Suggest strategies to mitigate these issues, such as data cleaning techniques, data validation rules, and recommendations for improving data collection processes.

### Step 3: Documentation
- Document the data quality assessment process and the actions taken to address any issues.
- Save the data quality report and the drafted client email in the `docs` directory of the repository.

## Task 2: Data Insights

### Step 1: Analyze Customer Demographics
- **Segment Customers**:
  - Analyze customer demographics such as age, gender, income, location, etc.
  - Identify patterns and segments within the customer base.

### Step 2: Identify High-Value Customers
- **Attribute Analysis**:
  - Analyze customer attributes such as purchase history, frequency, and average order value.
  - Use statistical methods to identify high-value customers.

### Step 3: Generate Insights
- **Targeting Strategies**:
  - Develop strategies to target high-value customers based on the analysis.
  - Identify potential high-value customer segments in the broader market.

### Step 4: Documentation
- Document the insights and strategies developed from the data analysis.
- Save the insights report in the `docs` directory of the repository.

## Task 3: Dashboard Creation

### Step 1: Define Dashboard Requirements
- **Client Needs**:
  - Identify the key metrics and KPIs the client needs to monitor.
  - Determine the data sources and visualization requirements.

### Step 2: Design Dashboard
- **Tools and Technologies**:
  - Use tools like Tableau, Power BI, or a Python-based dashboard (e.g., Dash, Streamlit) to create the dashboard.
  - Design intuitive and interactive visualizations to present the data insights.

### Step 3: Implement Dashboard
- **Data Integration**:
  - Integrate the cleaned and analyzed data into the dashboard.
  - Ensure the dashboard is dynamic and updates with new data.
    
 ### Tableau Dashboard URL:
 https://public.tableau.com/app/profile/subhransu.sekhar.mallick/viz/SSMKPMGVirtualInternshipTask3/Dashboard1
![Dashboard 1](https://github.com/mallicksubhransu/KPMG-Data-Analytics-Project-by-Forage/assets/114018899/b83e4d63-5c61-4593-bdbb-cb86e9f931dd)


- **User Interface**:
  - Create a user-friendly interface with filters, drill-down options, and clear navigation.

### Step 4: Dashboard Deployment
- **Deployment Options**:
  - Deploy the dashboard on a web server or share it via a cloud platform.
  - Provide the client with access instructions and usage documentation.

### Step 5: Documentation
- Document the dashboard creation process and provide user instructions.
- Save the dashboard files and the user guide in the `dashboard` directory of the repository.

## Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/ba-internship-project.git
   cd ba-internship-project
   ```

2. **Install Required Libraries**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Setup Environment**:
   - Ensure you have the necessary API keys and access credentials for any third-party data sources.
   - Create a `.env` file to store your environment variables securely.


Feel free to explore the repository, and don't hesitate to open an issue if you have any questions or suggestions. Happy analyzing!
