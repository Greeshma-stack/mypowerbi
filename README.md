📊 Employee Attendance Analysis Dashboard | Power BI
🔎 Project Summary

An interactive Power BI dashboard designed to analyze employee attendance, absenteeism, overtime, and work-from-home trends using HR data.
This project demonstrates end-to-end BI development, from data cleaning to DAX measures and interactive visualization.

🔹 Built as a university academic project with real-world HR analytics use cases.

🎯 Key Outcomes

Built a dynamic attendance monitoring system

Identified department-wise productivity & absenteeism trends

Enabled self-service analytics using slicers

Delivered insights useful for HR decision-making

🛠 Skills Demonstrated

Power BI Desktop

DAX (Measures & KPIs)

Power Query (ETL & Data Cleaning)

Data Visualization & Dashboard Design

Business Intelligence Concepts

HR Analytics

🗂 Dataset Overview

Synthetic annual employee attendance dataset created for academic purposes.

Key Fields:

EmployeeID, Name

Department, Role

Days Present, Days Absent

Leave Types (Sick, Casual, Paid, Unpaid)

Overtime Hours

Work From Home Days

Year

📁 Source: Excel (annual_employee_attendance_2025.xlsx)

📊 Dashboard Features
🔹 KPI Cards

Total Employees

Attendance Percentage

Total Absences

Total Overtime Hours

Average Work From Home Days

🔹 Visual Analytics

Department-wise Attendance (Present vs Absent)

Leave Type Distribution

Overtime Analysis by Department

Work-From-Home Trends

🔹 Interactivity

Department slicer

Role slicer

Year slicer

Real-time filtering across all visuals

📐 Data Modeling & DAX

Single-table optimized data model

Key DAX measures:

Total Employees = DISTINCTCOUNT(Data[EmployeeID])
Attendance % = DIVIDE(SUM(Data[DaysPresent]), SUM(Data[TotalWorkingDays]), 0)
Total Overtime Hours = SUM(Data[OvertimeHours])

🔍 Key Insights

Overall attendance rate remains consistently high

Engineering & Operations departments show higher overtime

Sick and paid leaves account for most absences

Technology-focused roles show higher WFH adoption

Attendance behavior varies significantly across departments

💼 Business Value

This dashboard can support:

HR attendance monitoring

Workforce productivity analysis

Absenteeism control

Work-from-home policy evaluation

Data-driven management decisions

🚀 How to Run

Clone or download the repository

Open Employee_Attendance_Dashboard.pbix in Power BI Desktop

Use slicers to explore insights interactively

🎓 Academic Context

Developed as part of a university curriculum project to demonstrate:

Business Intelligence workflows

Dashboard storytelling

Analytical thinking

Professional reporting standards

👩‍💻 Author

Greeshma G Rao
📍 Data Analytics | Power BI | BI Enthusiast

⭐ Recruiter Note

This project showcases practical Power BI skills including DAX, interactivity, and business insight generation, suitable for entry-level Data Analyst / BI roles.
