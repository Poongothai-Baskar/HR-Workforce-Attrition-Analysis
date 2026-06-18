# HR Workforce Attrition Analysis

## Problem Statement

Employee attrition is one of the major challenges faced by organizations. High employee turnover leads to increased recruitment costs, productivity loss, knowledge gaps, and reduced employee morale. HR departments need data-driven insights to understand why employees leave and how retention can be improved.

The objective of this project is to analyze employee workforce data, identify the factors contributing to attrition, and build an interactive HR analytics dashboard that supports workforce decision-making.

---

# Dataset Description

The dataset contains employee-related information such as:

* Satisfaction Level
* Last Evaluation Score
* Number of Projects
* Average Monthly Hours
* Time Spent in Company
* Work Accident History
* Promotion Status
* Department
* Salary Level
* Attrition Status

## Data Cleaning

The following preprocessing steps were performed:

* Removed missing values (if any)
* Removed duplicate records
* Renamed columns for better readability
* Created derived variables:

  * Experience Group
  * Salary Band
  * Overtime Category
  * Risk Category

## Final Dataset

* Original Records: 14,999
* Duplicate Records Removed: 3,008
* Final Records: 11,991

---

# KPI Definitions

Total Employees (11,991)

The organization consists of 11,991 employees after removing duplicate records. This represents the total workforce included in the analysis.

Attrition Rate (16.60%)

Approximately 16.60% of employees left the organization. This indicates a moderate level of employee turnover and highlights the need for retention-focused HR strategies.

Retention Rate (83.40%)

The organization retained 83.40% of its employees. A retention rate above 80% suggests relatively stable workforce retention, although improvements can still be made.

 Average Employee Tenure

This KPI measures the average number of years employees have worked in the company. Higher tenure generally reflects stronger employee loyalty and organizational stability.

Job Satisfaction Score

This KPI represents the average satisfaction level of employees. Higher satisfaction is associated with better retention and employee engagement.

 High-Risk Employees

These employees are identified based on low satisfaction levels and high workloads. Monitoring this group helps HR proactively reduce future attrition.

# Dashboard

1. Executive Overview
<img width="763" height="437" alt="executive_dash" src="https://github.com/user-attachments/assets/705296a8-3807-415f-8edd-c11a6de6ea91" />

2. Attrition Analysis
<img width="719" height="416" alt="Attrition" src="https://github.com/user-attachments/assets/df0b8f92-f6fb-45a4-af48-1d8bac0468ca" />

3. Employee Health
<img width="755" height="354" alt="Employee_health" src="https://github.com/user-attachments/assets/da83d887-2c3b-4fca-a201-278144ad44e5" />

4. Employee Segmentation
<img width="731" height="426" alt="Employee_seg" src="https://github.com/user-attachments/assets/e0281188-e545-4819-be4f-18dc2329dd5a" />

# Key Findings

## Department Analysis

Departments with the highest attrition rates:

* HR
* Accounting
* Technical
* Support

Departments with the lowest attrition rates:

* Management
* Research & Development

## Salary Analysis

Employees in the Low Salary category experience the highest attrition, while employees in the High Salary category have the lowest attrition.

## Satisfaction Analysis

Employee satisfaction shows a negative relationship with attrition. Lower satisfaction levels are associated with higher employee turnover.

## Overtime Analysis

Employees working overtime are more likely to leave the organization than employees with balanced workloads.

## Promotion Analysis

Employees who received promotions demonstrate significantly lower attrition rates compared to employees who were not promoted.

## Risk Segmentation

High-risk employees show the highest probability of attrition compared to medium-risk and low-risk employees.

---

# Recommendations

1. Improve employee satisfaction through engagement programs and regular feedback systems.
2. Review compensation policies for employees in lower salary bands.
3. Reduce excessive overtime and encourage better work-life balance.
4. Increase career development opportunities and promotion pathways.
5. Monitor high-risk employees using predictive workforce analytics.
6. Implement department-specific retention strategies, particularly for HR, Accounting, Technical, and Support teams.

---

# Future Scope

1. Develop machine learning models to predict employee attrition.
2. Build real-time HR monitoring dashboards.
3. Integrate employee survey and performance data.
4. Perform advanced workforce forecasting and retention analysis.
5. Implement automated alerts for high-risk employees.
6. Enhance dashboard interactivity using predictive and prescriptive analytics.

---

# Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Power BI

---

# Project Outcome

This project successfully identified the major factors influencing employee attrition and provided actionable workforce insights through KPI analysis, employee segmentation, and interactive Power BI dashboards. The findings help HR teams make informed decisions to improve employee retention and organizational performance.

# Author

POONGOTHAI B


