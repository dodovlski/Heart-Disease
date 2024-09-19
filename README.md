# Heart Disease Prediction

WARNING !!! 
  In this project, artificial intelligence was used to write clean code and create a README file.

This project involves building and evaluating machine learning models to predict heart disease using a dataset containing various health-related features. The analysis utilizes regression and classification techniques to assess model performance.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Model Evaluation](#model-evaluation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The goal of this project is to predict the presence of heart disease based on features such as age, sex, blood pressure, cholesterol levels, and other relevant health metrics. The analysis includes data preprocessing, feature encoding, model training, and evaluation.

## Dataset

The dataset used in this project includes several medical attributes, along with a binary target variable indicating the presence (1) or absence (0) of heart disease.

### Features:
- **Categorical Features**: 
  - Sex
  - Chest Pain Type (cp)
  - Fasting Blood Sugar (fbs)
  - Resting Electrocardiographic Results (restecg)
  - Exercise Induced Angina (exang)
  - Slope of the Peak Exercise ST Segment (slope)
  - Number of Major Vessels Colored by Fluoroscopy (ca)
  - Thalassemia (thal)

- **Numerical Features**:
  - Age
  - Resting Blood Pressure (trestbps)
  - Serum Cholesterol (chol)
  - Maximum Heart Rate Achieved (thalach)
  - ST Depression Induced by Exercise Relative to Rest (oldpeak)

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib

## Model Evaluation

The following models were implemented and evaluated:

### Regression Models
- Linear Regression
- K-Nearest Neighbors Regressor
- Decision Tree Regressor
- Random Forest Regressor

### Classification Models
- K-Nearest Neighbors Classifier
- Random Forest Classifier

The evaluation metrics for regression models include:
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)

The evaluation metrics for classification models include:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
