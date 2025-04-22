# Customer-subscriptions

## Overview
This project aims to predict customer subscriptions to term deposits, a key income source for banks. Using data from a marketing campaign—including demographic, socio-economic, and communication method features—we apply data visualization and machine learning to analyze customer behavior. The goal is to extract insights that enhance targeted marketing strategies, improve engagement, and provide explainable models to support informed decision-making.

## Methodology

1. Data Pre-processing
Efficiently clean and prepare the dataset for analysis, ensuring high data quality and reliability.

2. Exploratory Data Analysis (EDA) 
Perform EDA to visualize relationships, uncover patterns, and extract valuable insights regarding customer behaviours and preferences.

3.Analysis of Machine Learning Models 
Evaluate and compare three different machine learning algorithms (Logistic Regression, Decision Tree, Neural Network) to identify which model best predicts customer subscriptions.

4. Model Explainability
Using SHAP framework with appropriate plots, analyse the model's predictions and feature contributions, providing clarity on how certain factors influence customer decisions.

## Conclusion
This project successfully leveraged machine learning to predict customer subscription behavior for term deposits, using both model evaluation metrics and explainable AI techniques. Among the tested models, MLPClassifier delivered the highest accuracy and consistency, making it the strongest candidate for deployment. The SHAP analysis revealed that features like employment variation rate, call duration, and economic indicators (euribor3m, cons.price.idx) play crucial roles in influencing customer decisions. These insights suggest that marketing strategies focused on longer, high-quality calls and timing campaigns during favorable economic conditions can significantly improve customer conversion rates.
