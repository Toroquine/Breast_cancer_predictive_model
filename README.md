# Predictive Modelling for Breast Cancer Disease Progression

## Overview
This project focuses on using machine learning techniques to predict the progression of breast cancer based on the Wisconsin Breast Cancer Dataset. The goal is to improve diagnostic accuracy and assist clinicians in identifying whether a tumor is benign or malignant.

By employing Logistic Regression, Random Forest, and other machine learning models, the project evaluates predictive accuracy, sensitivity, and specificity. Explainable AI (SHAP) is used to provide insights into the key features influencing predictions.

---

## Project Features
- **Dataset**: Wisconsin Breast Cancer Dataset (569 instances with 32 features).
- **Models Implemented**:
  - Logistic Regression (Best-performing model with 95.6% accuracy)
  - Random Forest
  - Support Vector Machine (SVM)
  - Naïve Bayes
  - K-Nearest Neighbors (KNN)
- **Techniques**:
  - Hyperparameter tuning
  - Feature selection
  - Model evaluation using accuracy, sensitivity, specificity, and ROC curves
  - Explainable AI (SHAP) for feature importance analysis

---

## Key Findings
- **Best Model**: Logistic Regression achieved a balanced performance with:
  - **Accuracy**: 95.6%
  - **Sensitivity (Recall)**: 95.6%
  - **Specificity**: 95.7%
- **Feature Insights**:
  - Key predictive features: `radius_mean`, `texture_worst`, `concavity_worst`.
  - SHAP analysis highlights the importance of these features in determining malignancy.
- **Random Forest**: Exhibited potential overfitting with 100% training accuracy and 96% testing accuracy.

---

## How to Use
1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the project:
   ```bash
   python main.py
   ```