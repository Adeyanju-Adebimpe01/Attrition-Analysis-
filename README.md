## 📚 Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Tools Used](#tools-used)
- [Data Cleaning](#data-cleaning)
- [Key Insights](#key-insights)
- [Dashboard Preview](#dashboard-preview)
- [Recommendations](#recommendations)
- [Conclusion](#conclusion)

## Project Overview

This project analyzes employee attrition at Diamond Organization using Microsoft Excel. The objective was to identify the major factors influencing employee turnover, uncover workforce trends across departments and job roles, and provide data-driven recommendations to improve employee retention.

The dashboard provides interactive insights into employee demographics, attrition rates, job satisfaction, salary bands, and historical attrition trends to support strategic HR decision-making.


## Dataset 
The dataset contains employee-level information, including:
- Age
- Department
- Job Role
- Education
- Monthly Income
- Years at Company
- Job Satisfaction
- Attrition Status

**Source:** Kaggle

**Rows:** 1,470 employees

**File Type:** CSV

## Tools Used 
- Pivot Tables
- Pivot Charts
- Microsoft Excel
- Dashboard
  
## Data Cleaning
- Standardized column formatting.
- Removed duplicate records where applicable.
- Replaced blank values in the Departure Date column with **"Active Employee"** using a helper column.
- Standardized the Gender column by replacing "M" and "F" with "Male" and "Female".
- Created age groups (18–24, 25–34, 35–44, 45–54, and 55+) using a helper column.
- Built Pivot Tables to calculate key performance indicators (KPIs), including Total Employees, Active Employees, Total Attrition, Attrition Rate, and Average Age.
- Added slicers to enable interactive dashboard filtering.

## Key Insights 
- Laboratory Technicians role recorded the highest employee attrition (62 employees), indicating that entry-level technical positions may experience greater turnover due to career progression and external job opportunities.
- The research and development department has the largest number of employees leaving. This implies turnover is more concentrated in this department compared to others.
- Attrition is heavily concentrated in the younger workforce which is age 25 to 35 which implies that employees in their early stages of their careers are most likely to move between jobs as the look for better opportunities or career growth
- Employee attrition peaked in 2021, reflecting broader labor market changes following the COVID-19 pandemic, including organizational restructuring, increased remote work opportunities, and shifting employee priorities.
- Majority of the low income earners rated the Job satisfaction high but still left, This shows high job satisfaction is not enough to retain low income employees.

## Dashboard Preview

<img width="1217" height="612" alt="image" src="https://github.com/user-attachments/assets/ac4a50c0-f71a-4a83-abe8-78577c703e97" />


## Recommendations 

- Strengthen career development and internal promotion opportunities for employees in entry-level roles.

- Review compensation packages regularly to ensure salaries remain competitive, particularly for high-turnover positions.

- Conduct employee engagement surveys within departments experiencing high attrition to identify workplace challenges.

- Invest in continuous learning initiatives such as professional certifications and postgraduate education.

- Develop workforce retention strategies that improve organizational resilience during periods of economic uncertainty.

## Conclusion

The analysis revealed an overall employee attrition rate of **16%**, exceeding the commonly accepted benchmark of **10–12%**.

Employees aged **25–34 years** experienced the highest turnover, while Laboratory Technicians and Sales Representatives recorded the greatest attrition among job roles. Although many departing employees reported satisfactory job satisfaction levels, compensation, career progression, and role-specific challenges appear to be stronger drivers of employee turnover.

By addressing these factors through competitive compensation, structured career development, and targeted retention initiatives, the organization can significantly improve workforce stability and reduce employee attrition.
