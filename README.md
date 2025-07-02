# Predicting Employee Turnover - Google Advanced Data Analytics Capstone

This project is the final capstone for the [Google Advanced Data Analytics Professional Certificate](https://www.coursera.org/professional-certificates/google-advanced-data-analytics). The goal is to analyze HR data from a fictional company, **Salifort Motors**, and develop a predictive model to identify which employees are likely to leave the company.

## Project Overview

Salifort Motors is experiencing high employee turnover, impacting productivity and increasing costs. Using a dataset of 15,000 employees, this project builds and evaluates a classification model that helps the HR team understand key factors behind attrition and proactively reduce it.

## Tools and Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## Problem Statement

**Can we predict which employees are most likely to leave the company based on historical HR data?**

## Dataset

- 15,000 rows × 10 columns
- Features include:
  - Satisfaction Level
  - Last Evaluation
  - Number of Projects
  - Average Monthly Hours
  - Time at Company
  - Work Accident
  - Promotion History
  - Department
  - Salary

## Process

### PACE Framework:
- **Plan**: Defined business problem and key stakeholders.
- **Analyze**: Cleaned data, removed duplicates, conducted EDA.
- **Construct**: Selected features and built a Decision Tree Classifier.
- **Execute**: Evaluated model performance, interpreted results, and made recommendations.

## Key Findings

- Employees with **low satisfaction**, **long tenure**, and **no promotion history** are more likely to leave.
- Departments with **lower satisfaction** and **low salary levels** had higher attrition rates.
- **Satisfaction level**, **number of projects**, and **average monthly hours** were among the top predictors of turnover.

## Model Performance

**Model**: Decision Tree Classifier  
- Accuracy: 97%  
- Precision: 93% (for identifying employees who left)  
- Recall: 91%  
- F1-Score: 92%

## Recommendations

- Monitor employee satisfaction regularly.
- Avoid overloading employees with too many projects.
- Recognize and reward contributions with promotions or growth opportunities.
- Use predictive insights to engage at-risk employees early.

## Deliverables

- `HR_Turnover_Capstone.ipynb`: Full analysis and modeling notebook.
- `Executive_Summary.pdf`: One-page summary for stakeholders.
- `README.md`: This documentation.

