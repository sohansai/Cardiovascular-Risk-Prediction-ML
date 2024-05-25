# Cardiovascular Risk Prediction Machine Learning

## Overview
This repository contains code for predicting cardiovascular disease risk using various features such as age, gender, cholesterol levels, blood pressure, and more.

## Project Structure
- **Preprocessing:** 
  - The dataset is preprocessed using techniques such as handling missing values, encoding categorical variables, and scaling numerical features.
- **Exploratory Data Analysis (EDA):**
  - Exploratory data analysis is performed to understand the relationships between features and the target variable (TenYearCHD - Ten Year Coronary Heart Disease Risk).
- **Model Training:**
  - Two models are trained on the data: Logistic Regression and Random Forest Classifier. The data is split into training and testing sets for model evaluation.
- **Model Evaluation:**
  - The trained models are evaluated using classification reports to assess their performance in predicting the risk of coronary heart disease.

## Instructions for Use
1. **Setup Environment:**
   - Ensure Python and necessary libraries (e.g., pandas, scikit-learn, matplotlib, seaborn) are installed.
2. **Dataset:**
   - Provide a dataset containing relevant features including age, gender, cholesterol levels, blood pressure, etc., and the target variable TenYearCHD.
3. **Preprocessing:**
   - Execute the `preprocess_dataset` function to preprocess the dataset. Set the `scale` parameter to `True` if scaling is desired.
4. **Exploratory Data Analysis (EDA):**
   - Run the EDA section to visualize correlations between features and the target variable, and explore feature distributions.
5. **Model Training:**
   - Train models using the `train_model` function. Specify the list of models to train and provide training and testing datasets.
6. **Model Evaluation:**
   - Evaluate model performance using the `print_classification_report` function to generate classification reports for each model.
