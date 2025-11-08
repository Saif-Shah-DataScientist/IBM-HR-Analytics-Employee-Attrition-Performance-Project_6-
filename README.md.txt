# IBM HR Analytics – Employee Attrition and Performance Analysis

## Project Overview
This project explores employee attrition and performance patterns within a large organization. The objective is to identify the main factors contributing to employee turnover and uncover actionable insights that help improve retention, satisfaction, and productivity.

## Objectives
- Analyze key drivers of employee attrition  
- Examine how salary, job satisfaction, overtime, and work–life balance impact retention  
- Identify high-risk roles and departments  
- Provide data-driven recommendations for improving employee engagement and retention  

## Dataset
- File: IBM_HR_Employee_Attrition.csv (or equivalent)  
- Source: IBM HR Analytics Employee Attrition & Performance Dataset (Kaggle)  
- Key Columns: Age, Department, EducationField, JobRole, MonthlyIncome, JobSatisfaction, WorkLifeBalance, YearsAtCompany, Overtime, PerformanceRating, Attrition

## Tools and Libraries
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter Notebook  

## Steps Performed
1. Data loading and inspection  
2. Data cleaning and type corrections  
3. Feature engineering (IncomePerYear, experience grouping, satisfaction scoring)  
4. Exploratory Data Analysis (EDA)  
5. Visualization of attrition patterns by role, department, income, and satisfaction level  
6. Insights and actionable recommendations  

## Key Insights
- **Early-career employees** have the highest attrition risk, especially within the first 3 years.  
- **Sales and laboratory roles** experience above-average turnover, likely due to workload and job satisfaction issues.  
- **Lower annual income** correlates strongly with attrition, particularly when combined with low satisfaction or long commute distances.  
- **High overtime** and **poor work–life balance** are strong predictors of leaving.  
- **Training and engagement** reduce attrition; employees with more training and better performance ratings are more likely to stay.

## Business Recommendations
- Focus retention programs on **early-career and sales/field employees**.  
- Review and adjust **compensation bands** for roles under market rates.  
- Reduce **overtime** by hiring temporary support or adjusting work schedules.  
- Expand **training programs** to improve job satisfaction and retention.  
- Develop a **dashboard** to track high-risk employees using satisfaction, income, overtime, and tenure indicators.  

## Requirements
To install the required libraries, run:
