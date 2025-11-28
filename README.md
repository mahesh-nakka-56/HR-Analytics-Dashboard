HR Analytics Dashboard

A comprehensive Power BI dashboard designed to help organizations analyze employee data, identify HR trends, and make data-driven decisions. This dashboard provides insights into Attrition, Employee Performance, Salary Distribution, Department-wise Analysis, and more.

⭐ Project Overview

The HR Analytics Dashboard helps HR teams and management understand workforce dynamics by visualizing key HR metrics.
It simplifies decision-making by highlighting patterns, risks, and improvement areas across the organization.

🎯 Objectives of the Dashboard

Identify attrition rate and factors influencing employee turnover

Analyze employee demographics such as age, gender, and marital status

Track employee performance and job satisfaction

Compare salary trends across departments, job roles, and experience levels

Support HR in workforce planning and strategic decision-making

📊 Key Features
🔹 1. Attrition Overview

Total employees vs. employees who left

Attrition %

Attrition by age group, gender, and department

🔹 2. Employee Demographics

Age distribution

Education field

Job roles

Marital status

🔹 3. Salary & Experience Insights

Salary ranges by job role

Experience vs. salary

Department-level cost analysis

🔹 4. Performance & Satisfaction Metrics

Performance rating overview

Job satisfaction scores

Work-life balance insights

🛠️ Tech Stack
Tool / Technology	Purpose
Power BI	Dashboard creation & data transformations
Power Query (M Language)	Data cleaning & shaping
DAX	Measures & calculations
Excel / CSV Dataset	Raw HR data
🔢 DAX Measures Used

Some examples of DAX used:

Attrition Rate = DIVIDE(COUNTROWS(FILTER(Employee, Employee[Attrition] = "Yes")), COUNTROWS(Employee))

Total Employees = COUNT(Employee[EmployeeID])

Average Salary = AVERAGE(Employee[MonthlyIncome])


(You can add more based on your project.)

📁 Project Files Included

HR Analytics Dashboard.pbix → Power BI dashboard

Dataset.xlsx / CSV → HR data

README.md → Documentation

🚀 How to Use This Dashboard

Download the .pbix file from this repository

Open it using Power BI Desktop

Connect to the dataset (if required)

Explore insights through interactive visuals

📈 Insights Gained From This Dashboard

Younger employees show higher attrition

R&D and Sales departments have maximum turnover

Employees with low satisfaction scores leave more frequently

Salary hikes and job roles affect retention

(You can customize based on your results.)

🧑‍💻 About the Developer

This project is created as part of Power BI learning and portfolio development to demonstrate skills in data cleaning, modeling, DAX, and dashboard design.
