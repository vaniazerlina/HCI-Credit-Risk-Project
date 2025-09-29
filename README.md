# Home Credit Indonesia - Credit Risk Prediction

## Project Overview
This project was completed as part of the **Rakamin Academy Data Science Virtual Internship** with **Home Credit Indonesia**, a leading consumer finance company providing credit and installment services for a wide range of customers in Indonesia.  
The main objective of this project is to **predict the likelihood of loan applicants defaulting** by leveraging multiple datasets to build accurate, data-driven credit risk models.

## Dataset
The project uses:
- **Core loan application data** (300K+ records for train/test)
- **Supplementary datasets** (53M+ records) including bureau, bureau balance, credit card, POS_CASH, previous applications, and installments.

## Project Workflow
The project is structured in two main phases:

1. **Data Analysis**
   - Exploratory data analysis, feature exploration, and insights discovery.
   - [View Data Analysis Notebook](https://colab.research.google.com/drive/1INZpjbL6hEEYEsJPhnmrTSR5FBBKe0LU)

2. **Data Preprocessing & Modeling**
   - Feature engineering, handling class imbalance, and building predictive models.
   - Models include Random Forest, LightGBM, and Logistic Regression.
   - [View Preprocessing & Modeling Notebook](https://colab.research.google.com/drive/1VA_CjYOwYvBKh2s1TGLi8aSSgrj9BmeP)

## Model Performance
The best performing model is **Random Forest**, achieving:
- Recall: 90%
- Precision: 63%
- ROC-AUC: 0.98  

These results demonstrate strong capability in **identifying high-risk applicants** while minimizing false positives, enabling actionable insights for loan approval and risk mitigation.

## References
- Project dataset: Home Credit Default Risk (available via Rakamin Academy)
- Tools & Libraries: Python, Pandas, NumPy, Scikit-learn, LightGBM

---
