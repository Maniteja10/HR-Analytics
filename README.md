# HR Analytics – Workforce Analysis Using Power BI

## Project Overview
This project focuses on analyzing employee data to understand workforce distribution, hiring trends, employee demographics, and work locations.

The analysis was performed using Power BI to convert raw HR data into meaningful insights that can support better business and workforce planning decisions.

## Project Objectives
- Analyze the total number of employees.
- Calculate the percentage of remote and headquarters employees.
- Identify the average age of employees.
- Analyze yearly employee hiring trends.
- Understand employee distribution by gender, state, department, and race.
- Generate business insights and recommendations based on the analysis.

## Dataset Description
- **Total Records:** 22,214
- **Total Columns:** 13
- **Database:** MySQL
- **Table:** HR

The dataset contains employee information such as age, race, department, job title, work location, hire date, termination date, city, and state.

## Tools and Technologies
- **MySQL:** Database connectivity and data retrieval.
- **Power BI:** Data analysis, DAX calculations, and dashboard creation.
- **Power Query:** Data transformation and preparation.
- **GitHub:** Project documentation and version control.

## Key Performance Indicators (KPIs)

| KPI | Result |
|---|---:|
| Total Employees | 22,214 |
| Remote Employees | 24.75% |
| Headquarters Employees | 75.25% |
| Average Employee Age | 38.43 years |

## Data Visualizations

The Power BI dashboard includes the following visualizations:

1. **Hiring Trends by Year** – Displays the number of employees hired each year.
2. **Gender Distribution** – Shows employee distribution by gender using a donut chart.
3. **Employees by State** – Compares employee counts across different states.
4. **Employees by Department** – Shows workforce distribution across departments.
5. **Employees by Race** – Analyzes employee representation across racial groups.

## Key Insights
- The dataset contains 22,214 employee records.
- Approximately 75.25% of employees work at headquarters, while 24.75% work remotely.
- The average employee age is 38.43 years.
- Male employees represent 50.81% of the workforce, female employees 46.46%, and non-conforming employees 2.72%.
- Ohio has the highest employee count among the states shown in the analysis.
- Engineering is the largest department in the department-wise analysis.
- Hiring trends vary across the years.

## Business Recommendations
- Use department-wise employee distribution for better workforce planning.
- Review remote and headquarters work arrangements based on business needs.
- Monitor yearly hiring trends to plan future recruitment.
- Encourage equal opportunities and an inclusive workplace.
- Analyze employee exits to understand retention and turnover patterns.

## Project Structure

HR-Analytics/
│
├── PowerBI/
│   └── HR_Analytics_Dashboard.pbix
│
├── Screenshots/
│   ├── 01_HR_Dashboard.png
│   ├── 02_KPI_Cards.png
│   ├── 03_Hiring_Trends.png
│   ├── 04_Gender_Distribution.png
│   ├── 05_Employees_by_State.png
│   ├── 06_Employees_by_Department.png
│   └── 07_Employees_by_Race.png
│
├── Report/
│   └── HR_Analytics_Analysis_Report.pdf
│
├── Presentation/
│   └── HR_Analytics_Presentation.pptx
│
└── README.md

## Conclusion
This project demonstrates how HR data can be analyzed using MySQL and Power BI to understand workforce composition, employee distribution, and hiring patterns. The insights can help organizations make informed decisions about recruitment, workforce planning, diversity, and employee retention.
