Employee attrition impacts organizational productivity and costs. This project aims to predict attrition using HR data to enable proactive retention strategies. The report details data preprocessing, model selection, and performance analysis. Employee attrition has become a critical concern for organizations across industries due to its substantial impact on productivity, finances, and organizational knowledge. This project tackles this challenge by developing machine learning models to predict employee attrition using HR data, allowing for proactive retention interventions.

Abstract
This project predicts employee attrition using machine learning models. The IBM HR Analytics dataset was preprocessed, and five models were evaluated:

Logistic Regression
Random Forest
XGBoost
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)
Logistic Regression achieved the highest performance with:

F1 Score: 0.4211
ROC AUC Score: 0.7707
Key Insights:
Overtime, Monthly Income, and Job Role significantly affect attrition.
The dataset was highly imbalanced and appropriate preprocessing was applied.
Feature importance helped in deriving impactful insights for HR departments.
Dataset
Source: IBM HR Analytics Employee Attrition Dataset
File: dataset/employee_attrition.csv
ML Models Used
Model	Performance
Logistic Regression	✅ Best Performance (F1 & AUC)
Random Forest	Good but lower F1
XGBoost	Moderate
SVM	Low recall
KNN	Not suitable for imbalance
Preprocessing
Label Encoding & One-Hot Encoding
Handling Imbalanced Data using Resampling Techniques
Feature Scaling
Train-Test Split (80:20)
Evaluation Metrics
F1 Score
ROC-AUC Score
Confusion Matrix
Classification Report
