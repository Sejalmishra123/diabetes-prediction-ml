# Diabetes Prediction Using Machine Learning

## Overview
This project utilizes machine learning techniques to predict diabetes based on a given dataset. It includes data preprocessing, feature scaling, exploratory data analysis, model training, and evaluation.

## Dataset
- The dataset used in this project is `diabetes.csv`, which contains medical records for diabetes prediction.
- Features include `Pregnancies`, `Glucose`, `BloodPressure`, `SkinThickness`, `Insulin`, `BMI`, `DiabetesPedigreeFunction`, and `Age`.

## Project Workflow
1. **Data Loading**: The dataset is loaded using Pandas.
2. **Data Cleaning & Preprocessing**:
   - Handling missing values
   - Standardizing numerical features
3. **Exploratory Data Analysis (EDA)**:
   - Data visualization using Matplotlib and Seaborn
   - Correlation heatmaps for feature relationships
4. **Feature Scaling**:
   - Standardization using `StandardScaler` from Scikit-Learn
5. **Model Training & Evaluation**:
   - Train-test split using `train_test_split`
   - Training classification models such as Logistic Regression, Decision Tree, Random Forest
   - Evaluating model performance with accuracy, confusion matrix, and classification reports

## Installation
To run this project, install the required dependencies using:
```sh
pip install -r requirements.txt
