# Bank Customer Churn Prediction 💳

This project focuses on predicting whether a customer will churn (leave the bank) based on various features like demographics, account balance, and credit score. By applying multiple machine learning models, the project aims to identify the factors that influence customer retention.

## Project Overview

- **Dataset**: The model was trained on the Bank Customer Churn dataset.
- **Techniques**: Feature selection, data scaling, and model evaluation.
- **Classifiers Used**:
    - Logistic Regression
    - Random Forest
    - XGBoost

## Project Workflow

1. **Data Preprocessing**:
    
    - Dropped irrelevant columns and handled categorical variables.
    - Scaled the data using StandardScaler to improve model performance.
2. **Feature Selection**:
    
    - Analyzed feature correlations and removed weakly correlated features to focus on the most impactful ones.
3. **Model Training and Evaluation**:
    
    - Trained and tested multiple classifiers, comparing their performance based on accuracy.

## Results

The model performance was evaluated using accuracy scores, with the following results:

- **Logistic Regression**: 0.81
- **Random Forest**: 0.8605
- **XGBoost**: 0.8675

## Conclusion

This project provides insights into customer churn prediction and highlights the effectiveness of different machine learning models in addressing this business challenge.