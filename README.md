## HR Attrition Analysis

## 📚 Table of Contents
-[Project Overview ] (#Project-Overview)
-[Problem Statement]
-[Business Problem]
-[Objectives]
-[Tools & Technologies]
-[Dataset]
-[Data cleaning and transformation]
-[Business Questions]
-[Key Insights]
-[Dashboard Preview]
-[Recommendations]
-[conclusion]

## Problem Statement
The Diamond Organization is a mid-sized organization experiencing increasing employee attrition across multiple departments, with high concentration observed in specific job roles and age demographics. However, the organization lacks a centralized and data driven report system to monitor workforce trends, root causes and strategic recommendations.
 

## Objectives

- Identify key factors driving employee attrition
- Analyze attrition trends across departments and job roles
- Assess the impact of job satisfaction on attrition
- Provide strategic recommendations to improve employee retention

## 📂 Dataset

Source: Kaggle 
Rows: 1471
Columns: 
File Type: csv

## 🛠 Tools Used

- Excel
- Pivot tables
- Pivot Charts
- Dashbaord

## 🧹 Data Cleaning

- Formatted and standardized columns
- Filtered out blanks and duplicates e.g.  the departure date column has blanks, a helper column was created and the blanks were replaced with “Active Employees”
- Formatted the gender column and replace ‘m’ with “Male and ‘f’ with “female”
- Created a helper column to group the age column such as age 35-44, 44-55 and 55 & above
- Created pivot tables to calculate KPI such as total employee count, total attrition count, active employees, attrition rate (%) and average age
- Inserted slicers for dynamic filtering of data

## Analysis Questions

1. How does the organization attrition rate compare to the industry benchmark?
2. Which Department has the highest attrition?
3. Which Job Role experiences the most employee loss?
4. Which Age Group is most affected?
5. What is the impact of Salary band and Job satisfaction on Attrition
6. Which year shows the highest trend of attrition

## 📈 Key Insights

The company’s attrition rate is higher than the normal benchmark. The actual attrition rate is 16%, which is above the average benchmark of 11% indicating that employee turnover is slightly higher than what is typically expected.

- The research and development department has the largest number of employees leaving. This implies turnover is more concentrated in this department compared to others. Sales also show a relatively high level of turnover which may be linked to demanding and target driven nature of sales role
- The Laboratory Technicians role (62) recorded the highest attrition among all job roles in the organization. This is because the role appears to be more entry-level, so employees may use it as a starting point before moving to higher roles or better opportunities.
- The sale executive (57) and sales representative (33) are relatively high in attrition and this may be due to the pressure and target driven nature of sales role. Roles like manager and research director show low attrition suggesting higher stability among leadership roles
- Attrition is heavily concentrated in the younger workforce which is age 25 to 35 which implies that employees in their early stages of their careers are most likely to move between jobs as the look for better opportunities or career growth.The older employees show lowest attrition suggesting more experienced employees tend to stay longer in an organization. Attrition decreases as employee get older.
- The first 3 years shows a slow build which has very stable, minimal turnover. This is very likely because organization is in early or stable phase.
- There was a spike in 2021 which is certainly connected to the Post-Covid Era, the pandemic forced employers to down-size their staff and it also enforces employees to re-evaluate work life balance, purpose and priorities. There was also a remote work normalization during this period which meant employees could now apply anywhere in the world


## 📊 Dashboard

<img width="1217" height="612" alt="image" src="https://github.com/user-attachments/assets/ac4a50c0-f71a-4a83-abe8-78577c703e97" />



## Recommendations

Retention strategies should be focused on learning, career development and progression path for employees in the entry-level roles

Sponsor or standardize further education (Master’s programs) employees who upskill internally are less likely to leave

Benchmark salaries regularly against market rate for entry level roles

Review department with higher attrition to understand workload issues, management style and employee engagements

Build recession proof retention strategies so as to prevent occurrences that happened in 2021

## ✅ Conclusion

The analysis of employee attrition reveals that the 25-34 age group experiences the highest attrition while job roles like laboratory technicians and sales representatives also have higher departures contributing to an overall attrition rate of 16%, slightly above the ideal range of 10% - 12%.  Low income employees report high satisfaction but still left.
Overall, while employees may feel satisfied with their roles, retention is being influenced by deeper factors such as compensation, role specific challenges and career growth opportunities. Addressing these key factors will reduce attrition and improve stability
