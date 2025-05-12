# 🩺 Predicting Diabetes Risk Factors Using Supervised Machine Learning

This repository presents a comprehensive machine learning pipeline for predicting diabetes and analyzing its associated clinical risk factors using publicly available health survey data. The goal of the project is not just to predict diabetes onset but to gain interpretability into which features (e.g., age, BMI, glucose levels, lifestyle habits) have the strongest correlation with the disease.

## 📌 Project Objectives

- Identify and quantify the most significant risk factors contributing to diabetes.
- Train and evaluate multiple supervised learning algorithms for classification.
- Address class imbalance using techniques like SMOTE and class weighting.
- Interpret model outputs using feature importance, statistical tests, and visualizations.

## 📊 Dataset

- **Source:** National Health and Nutrition Examination Survey (NHANES)
- **Attributes:** Demographic, lifestyle, lab values, anthropometric measures
- **Target Variable:** Diabetes diagnosis (binary: diabetic / non-diabetic)
- **Size:** ~7,000 samples × 30+ features

## 🧪 Methodology

1. **Data Preprocessing**
   - Handling missing values and outliers
   - Label encoding and feature scaling
   - Statistical analysis: ANOVA, Chi-square

2. **Feature Selection**
   - Correlation heatmaps
   - p-value analysis
   - Mutual Information Scores

3. **Model Training**
   - Logistic Regression  
   - Random Forest Classifier  
   - XGBoost  
   - Support Vector Machine  
   - Decision Tree  
   - k-Nearest Neighbors

4. **Evaluation Metrics**
   - Accuracy, Precision, Recall, F1-score, ROC-AUC  
   - Confusion Matrix  
   - Cross-validation

5. **Class Imbalance Handling**
   - SMOTE (Synthetic Minority Over-sampling Technique)  
   - Class Weight Tuning

6. **Interpretability**
   - Feature importance visualization  
   - Odds ratio analysis (for Logistic Regression)  
   - SHAP values (optional)
