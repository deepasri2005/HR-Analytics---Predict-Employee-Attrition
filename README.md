# HR Analytics — Predict Employee Attrition

A data analysis and machine learning project that predicts employee attrition using the IBM HR dataset, built during my Data Analyst internship at Elevate Labs.

## What this project does

- Analyzes HR data to find out why employees leave
- Builds a Logistic Regression model to predict attrition
- Uses SHAP to explain which factors matter most
- Visualizes findings in a Power BI dashboard

## Dataset

IBM HR Analytics Employee Attrition Dataset — 1,470 employees, 35 features.
Source: [Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

## Tools used

Python (Pandas, Seaborn, Matplotlib) · Scikit-learn · SHAP · Power BI

## Key findings

- Employees who work overtime are 3x more likely to leave
- Lower monthly income strongly increases attrition risk
- Employees aged 25–34 and those in their first 2 years are at highest risk
- Sales Representatives have the highest attrition rate among all job roles

## Project files

```
hr_attrition_analysis.ipynb   → Python notebook (EDA + ML model + SHAP)
powerbi_dashboard.pbix        → Power BI dashboard
HR_Attrition_Report.pdf       → Final project report
```

## How to run

```bash
pip install pandas numpy matplotlib seaborn scikit-learn shap
```
Open the notebook in Jupyter or Google Colab and run all cells.

## Author

**Deepasri**
M.Sc. Data Science & Business Analysis
[GitHub](https://github.com/deepasri2005)
