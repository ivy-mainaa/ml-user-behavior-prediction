# ML User Behavior Prediction
Predicting e-commerce purchase intent using user session behavior.

## Overview
This project builds an end-to-end machine learning pipeline to predict whether an e-commerce user session will result in a purchase. The goal is to demonstrate a structured ML workflow, from problem framing and exploratory data analysis to modeling, evaluation, and interpretation, using real-world behavioral data.

## Business Motivation
Understanding purchase intent enables e-commerce platforms to:
- Personalize user experiences
- Optimize marketing spend
- Improve conversion rates
- Identify high-intent sessions in real time

## Dataset
- **Online Shoppers Purchasing Intention Dataset**
- Source: UCI Machine Learning Repository  
- Contains session-level behavioral features such as page engagement, visit duration, and user type  
- Target variable: `Revenue` (binary purchase indicator)

## Methodology
1. Data cleaning and preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Feature engineering and encoding  
4. Baseline Logistic Regression  
5. Feature selection and refined Logistic Regression  
6. Tree-based models (Random Forest, XGBoost)  
7. Model comparison and evaluation  
8. Feature importance analysis  
9. Business insights and recommendations  

## Models Used
- Logistic Regression (Baseline and Refined)
- Random Forest
- XGBoost

## Key Results
- Tree-based models outperform linear models for this task.
- **PageValues** and product engagement metrics are the strongest predictors of purchase intent.
- Random Forest achieves the best balance between precision and recall for revenue prediction.
- XGBoost achieves the highest overall accuracy and ROC-AUC.

## Data Storage Note
The dataset is uploaded manually to the Google Colab runtime for exploratory analysis.  
In a production environment, this data would be stored and accessed from cloud storage or a database.

## Project Structure
  ml-user-behavior-prediction/
│── online_shoppers_revenue_prediction.ipynb
│── README.md


## Tools & Technologies
- Python, Pandas, NumPy  
- Scikit-learn  
- XGBoost  
- Matplotlib, Seaborn  
- Google Colab  

## Status
Completed

## Author
Ivy Maina


