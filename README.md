# Sales and Finance Analytics
### **TITLE:**
Sales and Finance Analytics -- AtliQ Hardware

### **Overview:**
AtliQ Hardware is a rapidly expanding hardware company with a diverse range of products catering to customers across multiple countries through various sales channels, including retail, direct sales, and distributor networks. 
Designed reports extract valuable insights from AtliQ's extensive dataset, enabling informed decision-making. Through advanced analytics, it aims to drive substantial performance improvements and empower AtliQ to optimize operations, refine sales strategies, and capitalize on growth opportunities in its target markets.
### **Technology stack:**
1. Excel
2. Languages: M and DAX

### **Excel functionality used:**
1. **ETL (Extract Transform Load)** Load all the CSV files that were provided, to Power Query. Ensured there were no missing values, all dimension tables contained a unique column, removed duplicate values, corrected the spelling errors, and in the end loaded the files in the Power Pivot.
2. **Data Modelling** Connect all the tables using star schema. Create a new table dim_date using Power Query that includes the date, month, and year in a separate column. Add a new column for adding AtiliQ Hardware Fiscal year that runs from September to August and then connect the table with others.
3. **Pivot Table and Power Pivot** Integrate the data model with a Pivot Table for quick data analysis. Utilize Power Pivot to create new measures and columns. Employ Power Query for seamless data transformation and connectivity, streamlining the entire process of preparing and analysing data efficiently.
4. **DAX(Data Analysis Expression)** Create 10 + new Measures such as Net sales for each year, Gross Margin, GM %, and COGS using Formulas like Calculate, Sum, Divide, etc. Create new Columns using Functions like Related, Calculate, Format and extract quarterly months by adding 4 months to the calendar year for a fiscal year perspective.
5. **Conditional Formatting** Applied Conditional Formatting to enhance data presentation by applying rules, and formatting numbers and text. This approach highlights important data, identifies trends, and improves overall data readability for more effective analysis.

### **Sales analysis:**
#### **Purpose:** 
Empower businesses to monitor and evaluate their sales activities and performance.
#### **Objective:**
+ Create a customer performance report.
+ Conduct a comprehensive comparison between market performance and sales targets.
#### **Importance:** 
Identify sales patterns and track key performance indicators (KPIs).
### Role of reports: Determine effective customer discounts, facilitate negotiations with consumers, and identify potential business expansion opportunities in promising countries.

### **Finance analysis:**
#### **Purpose:** 
Evaluation of financial performance, support decision-making, and facilitate communication with stakeholders.
#### **Objective:**
+ Create Profit and Loss (P&L) reports by Fiscal Year.   
+ Create Profit and Loss (P&L) reports by Markets.
#### **Importance:**
Aid in benchmarking against industry peers and previous periods Foundation for budgeting and forecasting.
#### **Role of reports:** 
Align financial planning with strategic goals Instill confidence in the organization's financial outlook.

### **Valuable Insights:** 
1. Amazon emerged as the top customer with net sales of 82.1 million USD in 2021, followed by AtliQ Exclusive and AtliQ e-store. 
2. India led in net sales, amounting to 161.3 million USD in 2021. 
3. AQ Mx NB Product had the highest percentage increase in net sales from 2020 to 2021. 
4. Significant sales spikes, particularly from October to December. 
5. 16 new products were introduced in 2021, with AQ Qwerty leading sales at 22 million USD. 
6. The P&A division recorded the highest net sales, totalling 338.4 million USD in 2021. 
