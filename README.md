
# 🧠 Ensemble Stacking for Diabetes Prediction

A machine learning pipeline to predict diabetes using ensemble models like Random Forest, Gradient Boosting, AdaBoost, and Logistic Regression. This project includes EDA, model evaluation, and hyperparameter tuning using RandomizedSearchCV.

## 📊 Overview

This project analyzes the [Pima Indians Diabetes dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database) to predict diabetes outcomes based on patient data. It includes:

* Data cleaning and visualization
* Model training using multiple algorithms
* Model evaluation using various metrics
* Hyperparameter tuning for Random Forest
* Final model selection and performance reporting

## 📁 Files

* `Ensemble Stacking diabetes.py`: Complete code including data analysis, model training, and evaluation.

## 📌 Key Features

* 🔍 Exploratory Data Analysis (EDA)
* 🧪 Train-test split and standard scaling
* 🤖 Models used: Logistic Regression, Random Forest, Gradient Boosting, AdaBoost, Decision Tree
* 🏆 Metric evaluation: Accuracy, F1 Score, Precision, Recall, ROC AUC
* 🔧 Hyperparameter tuning using `RandomizedSearchCV`
* 📈 Visualization using `matplotlib`, `seaborn`

## 📉 Dataset Features

* Pregnancies
* Glucose
* BloodPressure
* SkinThickness
* Insulin
* BMI
* DiabetesPedigreeFunction
* Age
* Outcome (Target)

## 📈 Results Summary

* Random Forest with hyperparameter tuning outperformed other models.
* Best predictor: **Glucose**
* ROC AUC and F1 scores indicate solid performance on both training and test sets.

## 📌 Future Improvements

* Deploy as a web app using Streamlit or Flask
* Incorporate ensemble stacking/blending strategies
* Add SHAP/feature importance visualizations

