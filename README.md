# 🚢 Titanic Survival Prediction
Predicting passenger survival on the Titanic using machine learning algorithms and exploratory data analysis.

## 📌 Overview
This project explores the historic Titanic dataset to build predictive models for passenger survival. It demonstrates the end-to-end lifecycle of a data science task — from preprocessing to deployment — and compares the performance of multiple classifiers.

## 📊 Dataset
Source: Kaggle Titanic Dataset
Records: 891 passengers
Features: Pclass, Age, Sex, Fare, SibSp, Parch, Cabin, Embarked, etc.
Target: Survived (0 = No, 1 = Yes)

## 🔍 Exploratory Data Analysis
Imputation of missing values (Age, Fare, Cabin, Embarked)
Dropped irrelevant columns (Name, Ticket, PassengerId, Cabin)
Encoding categorical features (Sex, Embarked)
Correlation heatmap and survival statistics by features

## Visualizations:

Countplots by gender, class, and SibSp
Scatter plots of Fare vs Age by survival
Distribution plots for age
Crosstabs for survival rates by Pclass, Sex, and Port

## 🧠 Models Used
Model	Accuracy	Highlights
Logistic Regression	81.0%	Strong baseline with interpretability
Decision Tree	80.4%	Handles feature interactions and splits
Random Forest	81.5%	Best performer with ensemble robustness
Evaluation metrics: Accuracy, Confusion Matrix, Classification Report

Random Forest showed best overall results with improved recall

## 📌 Project Highlights
✅ Cleaned and transformed raw data
📈 Compared 3 classifiers to optimize predictions
📊 Strong visual storytelling and feature analysis


## ✨ Future Improvements
Add feature engineering (family size, title extraction)
Hyperparameter tuning with GridSearchCV
Deploy using Streamlit with pyngrok integration

## ✅ Conclusion
This project demonstrates my ability to clean data, explore key survival factors, and apply machine learning models for predictive analysis. Random Forest gave the best results, confirming the value of ensemble methods. It's a strong example of my end-to-end data science skills — from insight generation to model evaluation .
