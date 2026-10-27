# HR Analytics Dashboard | Excel

## 📊 Project Overview

The **HR Analytics Dashboard** is an interactive Excel dashboard designed to analyze employee data and provide insights into workforce distribution, employee attrition, salary, age demographics, and business travel patterns.

The project uses Excel PivotTables, charts, and KPI cards to transform raw HR data into meaningful visualizations that support data-driven HR decision-making.

## 🎯 Project Objectives

- Analyze employee headcount and workforce distribution.
- Monitor employee attrition and retention.
- Understand employee age demographics.
- Compare workforce distribution across departments.
- Analyze business travel patterns by department.
- Present important HR metrics in a clear, visual dashboard.

## 🛠️ Tools & Technologies

- **Microsoft Excel**
- PivotTables and PivotCharts
- Excel formulas and KPI calculations
- Data visualization
- Data cleaning and analysis

## 📌 Key Performance Indicators (KPIs)

The dashboard includes the following KPIs:

- **Total Employees:** Total employee records in the dataset.
- **Employees Left:** Number of employees with an attrition status of Yes.
- **Current Employees:** Number of employees with an attrition status of No.
- **Attrition Rate:** Percentage of employee records with attrition.
- **Average Age:** Average age of employees.
- **Average Monthly Income:** Average monthly employee income.

## 📈 Dashboard Visualizations

The dashboard contains the following visualizations:

1. **Attrition Rate KPI** – Displays the overall employee attrition rate.
2. **Employees Left** – Shows the number of employees who left.
3. **Current Employees** – Shows the number of employees who remained.
4. **Total Employees** – Displays total employee records.
5. **Employee Age Distribution** – Summarizes the age profile of the workforce.
6. **Average Monthly Income** – Shows average employee income.
7. **Attrition by Department** – Compares attrition across departments.
8. **Business Travel by Department** – Visualizes business travel patterns across HR, R&D, and Sales.
9. **Workforce by Department** – Compares employee distribution across departments.
10. **Employee Status** – Shows the distribution of employees by attrition status.

## 📂 Dataset Description

The dataset contains employee-level HR information, including:

- Employee Number
- Age and Gender
- Department and Job Role
- Attrition
- Monthly Income
- Years at Company
- Job Satisfaction
- Business Travel
- OverTime
- Job Level
- Work-Life Balance
- Training and Promotion Information

The dataset contains 1,470 employee records and 44 columns.

## 🔍 Key Insights

The dashboard is designed to help users explore questions such as:

- How many employees are currently represented in the dataset?
- How many employees have left the organization?
- How does attrition vary across departments?
- Which departments have the largest workforces?
- How are employees distributed across age groups?
- How do business travel patterns differ across departments?
- What is the average monthly income of employees?

These analyses can help HR teams identify patterns, investigate retention challenges, and make more informed workforce decisions.

## 🧮 KPI Calculation

The attrition rate is calculated as:

**Attrition Rate = (Employees Who Left / Total Employee Records) × 100**

In Excel, the formula can be written as:

```excel
=COUNTIF(tblHR[Attrition],"Yes")/COUNTA(tblHR[Employee Number])
```

Format the result as a percentage.

For employee counts, use **Count of Employee Number**, not Sum of Employee Number, because employee numbers are identifiers rather than quantities.

## 🚀 How to Use

1. Download or clone this repository.
2. Open the Excel workbook.
3. Navigate to the Dashboard worksheet.
4. Review the KPI cards and visualizations.
5. Explore the analysis worksheets and PivotTables for additional details.
6. Refresh PivotTables after updating the source data, if applicable.

## 📁 Project Files

- `HR_DASHBOARD.xlsx` — Excel workbook containing the HR dashboard and analysis.
- `DASHBOARD.png` — Screenshot preview of the dashboard.
- `README.md` — Project documentation.

## 💡 Skills Demonstrated

- HR Data Analytics
- Data Cleaning and Preparation
- KPI Development
- Excel Formulas
- PivotTables and PivotCharts
- Dashboard Design
- Data Visualization
- Business Intelligence and Reporting

## 👩‍💻 Project Purpose

This project demonstrates the use of Microsoft Excel to convert employee data into a visual analytics dashboard. It is intended as a data analytics portfolio project showcasing practical Excel, reporting, and data visualization skills.

---

**Project:** HR Analytics Dashboard  
**Tool:** Microsoft Excel  
**Category:** Data Analytics | Human Resources | Business Intelligence


## 👤 Author
**Khushi Sudh**
🔗 LinkedIn: https://www.linkedin.com/in/khushi-sudh-68bab8249/
