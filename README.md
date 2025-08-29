# Employee Attrition Analysis Dashboard

## Repository Outline

P0M1_Ghozy_Alfisyahr_reuski.ipynb - Python notebook for data cleaning & analysis

cleaned_employee_data.csv - Final dataset used for Tableau visualization

dashboard.twbx - Tableau packaged workbook containing the dashboard


## Problem Background

Employee attrition, or turnover, is a critical challenge for many organizations. Understanding the patterns behind why employees leave can help HR departments take proactive steps to reduce turnover, improve satisfaction, and retain top talent.

This project analyzes employee data to uncover the factors that influence attrition, such as department, satisfaction levels, overtime, income, and tenure. The findings are visualized in a Tableau dashboard for actionable insights.

## Project Output

- A cleaned dataset ready for visualization
- Exploratory Data Analysis using Python
- An interactive Tableau dashboard showing:
  - Attrition rates per department
  - Correlation and importance of key factors
  - Filtering capabilities for department, gender, and satisfaction

## Data

- Source: IBM HR Analytics Employee Attrition & Performance dataset (available on Kaggle)
- Shape: 1,470 rows and approximately 35 columns
- Missing Values: Checked and handled during data cleaning
- Contains both categorical and continuous features such as:
  - Attrition status
  - Monthly income, age, job role
  - Satisfaction levels, work-life balance, overtime

## Method

This project uses:
- Descriptive statistics and correlation analysis (point biserial correlation for continuous variables and Cramér’s V for categorical variables)
- Data wrangling, including feature encoding (e.g., converting Attrition to AttritionLevel)
- Exploratory Data Analysis (EDA) via strip plots, bar charts, and bubble charts
- Final visualization and dashboard construction using Tableau, with interactivity enabled through filters and calculated fields

## Stacks

| Category       | Tools Used                              |
|----------------|------------------------------------------|
| Programming    | Python 3 (pandas, seaborn, matplotlib)   |
| Visualization  | Tableau                                  |
| Libraries      | NumPy, SciPy, seaborn, matplotlib, openpyxl |
| Data Handling  | Jupyter Notebook                         |

## Reference

- Kaggle Dataset: https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset
- Tableau Public Dashboard: (https://public.tableau.com/app/profile/ghozy.reuski/viz/Ghozy_Alfisyahr_Reuski_dashboard/Dashboard2?publish=yes)
- IBM HR Analytics Dataset Documentation (if applicable)
- 
