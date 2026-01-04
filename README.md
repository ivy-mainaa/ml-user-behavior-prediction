# E-commerce User Behavior Prediction

Predicting online purchase intent using session-level user behavior data.

---

## Overview

This project builds an end-to-end machine learning pipeline to predict whether an e-commerce user session will result in a purchase. The focus is on translating behavioral signals (engagement, navigation patterns, and visit context) into actionable predictions.

The project demonstrates a complete ML workflow using real-world data, with
emphasis on model comparison, interpretability, and business relevance.

---

## Business Motivation

Accurately predicting purchase intent enables e-commerce platforms to:

- Personalize user experiences in real time.
- Optimize marketing and retargeting spend.
- Improve conversion rates.
- Identify high-intent sessions earlier in the funnel.

---

## Dataset

**Online Shoppers Purchasing Intention Dataset**  
Source: UCI Machine Learning Repository

- Session-level behavioral features (page views, duration, bounce behavior)
- Mixture of numerical and categorical variables.
- Target variable: `Revenue` (binary purchase indicator).

---

## Modeling Approach

The modeling pipeline includes:

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA) to understand behavioral patterns
- Feature engineering and encoding
- Baseline Logistic Regression
- Refined Logistic Regression with feature selection
- Tree-based models (Random Forest, XGBoost)
- Model comparison using accuracy, precision-recall, and ROC-AUC
- Feature importance analysis for interpretability

---

## Key Results

- Tree-based models outperform linear models on this task.
- PageValues and product-related engagement metrics are the strongest predictors.
- Random Forest achieves the best balance between precision and recall.
- XGBoost achieves the highest overall accuracy and ROC-AUC.

---

## Data Handling Note

The dataset is uploaded manually to the Google Colab runtime for exploratory analysis.
In a production setting, this data would be accessed via cloud storage or a database pipeline rather than manual uploads.

---

## Tools & Technologies

- Python, Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn
- Google Colab




