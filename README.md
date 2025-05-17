# Explainable-ML-Churn-Customer-Predictions
Bank Customer Churn Prediction with Explainable ML Using Random Forest, AdaBoost, SVM &amp; Interpretability Tools like LIME, PDP, and Permutation Importance


This project focuses on predicting customer churn for a bank using advanced machine learning models and enhancing model interpretability with Explainable ML techniques. The goal is not only to achieve high prediction accuracy but also to understand the "why" behind the predictions, which is crucial for decision-making in high-stakes environments like finance.

Key Features
Churn prediction using Random Forest, AdaBoost, and Support Vector Machines

Data preprocessing, balancing using SMOTE, and pipeline-based modelling

Integration of LIME, Partial Dependence Plots (PDP), and Permutation Feature Importance for model explainability

Evaluation using F1-score, Accuracy, and Precision-Recall AUC

Exploratory Data Analysis (EDA) with Seaborn, Matplotlib, and Plotly

Results - 

| Model         | F1 Score | Accuracy |
| ------------- | -------- | -------- |
| Random Forest | 0.98     | 0.98     |
| AdaBoost      | 0.93     | 0.92     |
| SVM           | 0.95     | 0.95     |


Explainable AI Tools Used
LIME
Provides local instance-level explanations. Example: being single or having a graduate education can affect churn probability.

Permutation Feature Importance
Reveals most influential features:

Total_Trans_Ct

Total_Trans_Amt

Total_Relationship_Count

PDP (Partial Dependence Plot)
Shows global feature impact; e.g., Dependent_count and Total_Revolving_Bal significantly affect churn.
