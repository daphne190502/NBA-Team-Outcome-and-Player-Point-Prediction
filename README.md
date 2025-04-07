# NBA Match Outcome & Player Point Prediction

## Overview
This project focuses on predicting NBA match outcomes and player point performance using recent team and player form. Unlike traditional models that rely heavily on historical season data, this approach emphasizes short-term trends and includes opponent defensive metrics to enhance prediction accuracy. It combines classification (match outcome) and regression (player point) models using a variety of machine learning techniques.

## Objectives
• Develop models to predict both NBA match outcomes and player points.  
• Focus on recent team/player performance instead of long-term histor.  
• Incorporate opponent defensive metrics into player point predictions.  
• Compare multiple machine learning models (XGBoost, CatBoost, MLP, etc.).  
• Deliver insights useful for analysts, coaches, and fantasy/betting applications.  


## Dataset
• Source: Kaggle – NBA game and player stats from 2003 to 2022.  
• Team Dataset: Used for match outcome prediction (classification).  
• Player Dataset: Used for player point prediction (regression).  
• Preprocessing: Cleaned missing records, removed inactive games/players, and merged team & player stats.  

## Methodology
• Feature Engineering: Recent form-based stats (basic, derived, and advanced metrics like TS%, eFG%, IBASIC, IEXT).  
• Models Used:  
– Classification (Match Outcome): Logistic Regression, Random Forest, XGBoost, CatBoost, LightGBM, ANN  
– Regression (Player Points): Random Forest, XGBoost, CatBoost, LightGBM, MLP  
• Evaluation: Accuracy, Precision, Recall, F1 (classification) | MAE, MSE, R² (regression).  

## Tools & Technologies
• Programming Language: Python  
• Libraries: Pandas, Scikit-learn, XGBoost, CatBoost, LightGBM, TensorFlow/Keras  
• Visualization: Matplotlib, Seaborn  
• Hyperparameter Tuning: GridSearchCV (with 5-fold cross-validation)  
