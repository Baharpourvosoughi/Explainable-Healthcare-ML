# Clinical Machine Learning and Explainability Repositories

This repository contains machine learning workflows and explainable AI (XAI) analyses for clinical risk prediction tasks. The primary objective is to build supervised baseline models on benchmark medical datasets and apply post-hoc interpretability techniques to analyze feature attribution.

## Contents

### 1. Diabetes Risk Prediction (`explainable-diabetes-prediction-using-shap.ipynb`)
* **Dataset:** Pima Indians Diabetes Database.
* **Approach:** Exploratory data analysis, handling physiological zeroes, feature scaling, and training Random Forest classifiers (100 and 300 estimators).
* **Evaluation:** Standard classification metrics including Accuracy, Precision, Recall, F1-Score, and ROC-AUC.
* **Explainability:** Implemented `shap.TreeExplainer` to analyze global and local feature attributions, verifying the directional impact of primary clinical variables such as Glucose, BMI, and Age.

### 2. Heart Disease Classification (`heart-disease-prediction-using-clinical-features.ipynb`)
* **Dataset:** Cardiovascular clinical records.
* **Approach:** Data preprocessing, categorical encoding, and outlier assessment.
* **Evaluation:** Benchmarked classification models focusing on sensitivity-specificity trade-offs, analyzing features including resting blood pressure, serum cholesterol, and chest pain indicators.

## Tech Stack
* **Language:** Python
* **Libraries:** Scikit-Learn, Pandas, NumPy, SHAP, Matplotlib, Seaborn

## Author
**Bahar Pourvosoughi**  
Islamic Azad University, Central Tehran Branch  
[GitHub Profile](https://github.com/Baharpourvosoughi)
