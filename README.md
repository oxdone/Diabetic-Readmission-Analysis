# Diabetic-Readmission-Analysis
I analyzed hospital readmission rates among diabetic patients using Python and Jupyter Notebook. Through data cleaning, ETL, and visualization, I identified patterns and key factors linked to readmission risk, turning healthcare data into actionable insights that support better decision-making.
# Hospital Readmission Analysis for Diabetic Patients
This project analyzes hospital readmission rates among diabetic patients using Jupyter Notebook.
## Objective
To identify patterns and factors associated with readmission.
## Tools Used
- Python
- Pandas
- Matplotlib / Seaborn
- Jupyter Notebook
## Project File
- Diabetic_Readmission_Analysis.ipynb
This project developed a machine learning pipeline to predict 30-day hospital
readmission for diabetic patients using the UCI Diabetic Readmission dataset.
Early identification of high-risk patients enables targeted interventions that
can reduce readmissions, improve patient outcomes, and lower hospital costs.
MODELS EVALUATED
  1. Logistic Regression     ROC-AUC: 0.6309
  2. Random Forest           ROC-AUC: 0.6538
  3. Gradient Boosting       ROC-AUC: 0.6684  ← BEST
  4. GB Reduced (92 feat.)   ROC-AUC: 0.6682
