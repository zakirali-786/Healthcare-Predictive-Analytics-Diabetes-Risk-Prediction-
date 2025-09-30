# Healthcare-Predictive-Analytics-Diabetes-Risk-Prediction-

# Diabetes Risk Prediction (Healthcare Predictive Analytics)

## Overview
This project uses the **Pima Indians Diabetes Dataset** to predict the risk of diabetes based on medical attributes such as glucose level, BMI, blood pressure, and age. The goal is to build classification models, evaluate their performance, and interpret results using SHAP for explainability.

## Dataset
**Features:**
- Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI,
- DiabetesPedigreeFunction, Age

**Target:**
- Outcome (1 = Diabetes, 0 = No Diabetes)

## Steps
1. Data Cleaning (replace invalid 0s with median values)
2. Normalization (StandardScaler for numerical features)
3. Modeling (Logistic Regression, Random Forest, XGBoost)
4. Evaluation (Accuracy, Precision, Recall, F1, ROC-AUC)
5. Explainability (SHAP feature importance plots)

## Results
- Logistic Regression baseline: ROC AUC ~0.75
- Random Forest: ROC AUC ~0.80
- Important features: Glucose, BMI, Age

## Ethical Considerations
- Dataset contains no personally identifiable information.
- Predictions are for educational purposes only, not a substitute for medical diagnosis.
- Fairness and bias should be monitored if deploying in real-world healthcare.
