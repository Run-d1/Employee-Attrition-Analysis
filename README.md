# Employee Attrition Analysis

## Overview
This project leverages data mining techniques to analyze employee attrition using the IBM HR Analytics dataset. The goal is to identify key factors influencing attrition and build predictive models to aid human resource departments in improving employee retention strategies.

## The repository includes:
- **`HR-Employee-Attrition.csv`**: Original dataset before preprocessing.
- **`HR-Employee-Attrition-Updated.csv`**: Dataset after preprocessing.
- **`HR-employee-attrition.ipynb`**: The Python script for data preprocessing.
- **`paper/EmployeeAttrition_Paper_Group1.pdf`**: The final project paper detailing the methodology and findings.

## Dataset
The dataset is a fictional IBM HR Analytics dataset designed to simulate employee attrition scenarios. 
- **Source**: [Kaggle IBM HR Analytics Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

## Methodology
- **Data Preprocessing**: Cleaning, encoding, and feature selection.
- **Modeling**: Decision Tree, Random Forest, and Logistic Regression.
- **Evaluation**: Logistic Regression was selected as the best model based on recall.

## Key Findings
- Monthly income and overtime work significantly impact attrition.
- Logistic Regression demonstrated the highest performance with a recall of ~59%.
