# DSA-Project
A Power BI financial reporting solution for Finsight Financial
## PROJECT OVERVIEW
FinSight Financial Analytics is a business intelligence project focused on analysing the financial performance of FinSight Distribution & Consumer Products Ltd. Using financial transaction data from 2024 to 2025, the project explores revenue trends, operating expenses, profitability, and cost efficiency. The goal is to transform raw financial data into meaningful insights that support better financial reporting, identify key drivers of profitability, and facilitate data-driven business decisions.
## Business Problem
Despite experiencing significant revenue growth between 2024 and 2025, FinSight Distribution & Consumer Products Ltd. faces a concerning decline in profit margins, with net profit before tax remaining flat or declining.
**Revenue has increased significantly from 2024 to 2025. Why hasn't profit increased at the same rate?**
The company also relies on manual Excel-based financial reporting, limiting visibility into operational expenses and cost drivers. Management therefore needs a more reliable and interactive reporting solution to understand why revenue growth is not translating into proportional profit growth and identify opportunities to improve financial performance.
## Project Objectives
- Develop an interactive monthly Profit and Loss (P&L) statement to monitor financial performance.
- Compare financial performance across 2024 and 2025 using year-over-year (YoY) and month-over-month (MoM) analysis.
- Identify major operational and macroeconomic expense drivers contributing to profit margin compression.
- Evaluate branch-level and department-level cost efficiency.
- Generate actionable, data-driven recommendations to support management decision-making.## Tools & Technologies
## Tools & Technologies
- **Power BI:** Financial data visualization and interactive dashboard development.
- **Power Query:** Data cleaning, transformation, and preparation.
- **DAX (Data Analysis Expressions):** Financial calculations, KPI development, and time intelligence.
- **Data Modelling:** Establishing table relationships and building a structured data model.
- **Financial Analysis:** Profit and Loss reporting, profitability analysis, and financial performance evaluation.
  ## Dataset Overview
The project uses a financial dataset covering January 2024 to December 2025, comprising 4,500 financial transaction records. The dataset is structured across multiple interconnected tables, supporting financial performance analysis across accounts, departments, branches, and cost centres.
### Dataset Structure

| Table | Description |
|---|---|
| FactFinancialTransactions | Contains financial transaction records and monetary values. |
| ChartOfAccounts_PL | Defines account classifications and Profit & Loss reporting structure. |
| DimAccount | Provides general ledger account details. |
| DimDepartment | Contains departmental information. |
| DimBranch | Provides branch and geographical details. |
| DimCostCentre | Contains cost centre classifications and responsibilities. |
| DataDictionary | Documents dataset fields and their business meanings. |
## Data Preparation & Cleaning
Data preparation involves reviewing and transforming the raw financial dataset to ensure consistency, accuracy, and readiness for analysis.
Key preparation activities include:

- Inspecting the dataset for missing values, duplicate records, and inconsistencies.
- Reviewing blank entries in key categorical fields, particularly DepartmentID and CostCentreID.
- Ensuring appropriate data types for dates, financial values, and categorical variables.
- Validating transaction records and checking relationships between the fact and dimension tables.
- Preparing the dataset for financial calculations, reporting, and visualization.
**Tools Used:** Power Query.
  ## Data Modelling
The project adopts a **Star Schema architecture** in Power BI to establish a structured and efficient data model for financial analysis.
The model consists of a central fact table, FactFinancialTransactions, connected to four dimension tables:

- **FactFinancialTransactions:** Stores financial transaction records and monetary values.
- **DimAccount:** Provides account classifications and Profit & Loss reporting details.
- **DimDepartment:** Contains departmental information for cost attribution.
- **DimBranch:** Provides geographical and branch-level information.
- **DimCostCentre:** Classifies operational and administrative cost centres.
![Data Model](Images/DataModel.png)
Data Model using Star-schema  connecting financial transactions with account, department, branch, cost-centre, and date dimensions.
## Financial Analysis & DAX Measures

DAX (Data Analysis Expressions) is used to develop financial measures and calculations that support dynamic reporting and performance evaluation.
Key financial metrics include:

- **Total Revenue:** Measures income generated from business operations.
- **Cost of Sales (COGS):** Evaluates the direct costs associated with sales.
- **Gross Profit:** Determines revenue remaining after deducting the cost of sales.
- **Operating Expenses:** Tracks the costs incurred in running business operations.
- **Net Profit Before Tax (NPBT):** Evaluates profitability before tax deductions.
- **Gross Profit Margin:** Measures gross profitability relative to revenue.
- **Net Profit Margin:** Evaluates the percentage of revenue retained as profit before tax.
- **YoY & MoM Analysis:** Tracks financial performance across yearly and monthly periods.
  
## Dashboard Development & Visualization

An interactive financial dashboard is developed in Power BI to provide a comprehensive view of the company's financial performance.
The dashboard focuses on the following analytical areas:
- **Executive Financial Overview:** Presents key financial indicators, including revenue, gross profit, operating expenses, and net profit before tax.
- **Profit & Loss Analysis:** Provides a structured breakdown of revenue, cost of sales, operating expenses, and profitability.
- **Revenue & Profitability Trends:** Examines monthly and yearly changes in revenue and profit performance.
- **Expense Analysis:** Identifies major expense categories and their contributions to overall operating costs.
- **Branch & Department Performance:** Evaluates financial performance and cost efficiency across different business units.
![Data Model](Images/ExecutiveDashboard.png)
Executive Dashboard
___
![Data Model](Images/Profit&Loss.png)
   Profit and Loss Analysis
___
![Data Model](Images/RevenueMoM&YoY.png)
   Revenue and Profitability Trends ( MoM and YoY Analysis)
___
![Data Model](Images/ExecutiveDashboard.png))
Expense Analysis
___
![Data Model](Images/Branch&DepartmentEfficiency.png)
Branch and Department Performance
___
## Business Recommendations & Conclusion
- **Strengthen cost control:** Monitor operating expenses and identify areas of unnecessary spending.
- **Improve profitability:** Evaluate cost drivers affecting profit margins and take corrective action.
- **Enhance financial monitoring:** Use interactive Power BI reports to track revenue, expenses, and profitability regularly.
- **Support informed decisions:** Use branch and departmental performance reports to guide resource allocation and operational improvements.

**Conclusion:** FinSight Financial Analytics provides an interactive approach to financial reporting, helping management investigate the gap between revenue growth and profitability while improving cost visibility and financial decision-making.
## Project Structure

```text
FinSight-Financial-Analytics/
│
├── Dataset/
│   └── FinSight_Financial_Analytics_Project.xlsx
│
├── PowerBI/
│   └── FinSight_Financial_Analytics.pbix
│
├── images/
│   ├── datamodel.png
│   ├── executive_dashboard.png
│   ├── profit_loss.png
│   ├── revenue_analysis.png
│   ├── expense_analysis.png
│   └── branch_performance.png
│
├── Documentation/
│   └── DAX_Measures.md
│
└── README.md
```
### Repository Contents

- **Dataset:** Contains the source financial dataset.
- **PowerBI:** Stores the Power BI report file.
- **images:** Contains the data model and dashboard screenshots.
- **Documentation:** Contains supporting project documentation and DAX measures.
- **README.md:** Provides an overview of the project, methodology, and key findings.
  ## Author & Contact

**Author:** [Ayanleye Pelumi.M]  
**Role:** Financial Data Analyst | Power BI Developer

**Connect with me:**
- **LinkedIn:** [Your LinkedIn Profile](https://linkedin.com/in/your-profile)
- **GitHub:** [Your GitHub Profile](https://github.com/your-username)
- **Email:** [Your Professional Email](mailto:miklospelumi@gmail.com)

For questions, collaborations, or professional opportunities related to this project, feel free to connect with me.
