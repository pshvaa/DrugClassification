# Drug Type Prediction using Machine Learning

This project focuses on predicting the appropriate drug type for a patient based on various health features. It's a great beginner-friendly dataset to apply machine learning techniques.

## Dataset Overview

The dataset contains patient data with the following features:

- **Age**: The age of the patient.
- **Sex**: The gender of the patient (Male/Female).
- **Blood Pressure Levels (BP)**: The patient's blood pressure levels (Low/Normal/High).
- **Cholesterol Levels**: The cholesterol levels of the patient (Normal/High).
- **Na to Potassium Ratio**: The ratio of sodium to potassium in the blood.

The **target** variable is the **Drug type**, which indicates the drug prescribed to a patient.

## Objective

The goal of this project is to predict the drug type based on the given patient features using machine learning models. This project is suitable for beginners looking to explore classification algorithms and improve their understanding of data preprocessing, feature selection, and model evaluation.

## Approach

1. **Data Exploration**:
   - Analyze and understand the distribution of features.
   - Check for missing or inconsistent data.

2. **Data Preprocessing**:
   - Encode categorical variables (e.g., Sex, Blood Pressure Levels, Cholesterol Levels).
   - Normalize numerical features like Age and Na to Potassium Ratio.

3. **Modeling**:
   - Apply various classification algorithms such as:
     - Decision Trees
     - Random Forest
     - k-Nearest Neighbors (k-NN)
     - Logistic Regression
   - Tune the models and select the best-performing one based on accuracy or other evaluation metrics (e.g., precision, recall).

4. **Evaluation**:
   - Evaluate model performance using metrics like accuracy, confusion matrix, precision, and recall.

