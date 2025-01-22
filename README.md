# Predicting Heart Disease using Machine Learning

## Overview
This project leverages machine learning algorithms to predict whether a patient has heart disease based on various medical attributes. The dataset used comes from the **Cleveland Heart Disease** data in the UCI Machine Learning Repository, and our goal is to achieve a model accuracy of at least 95%.

## Dataset
The dataset is publicly available from:
- UCI Machine Learning Repository: [Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease)
- Kaggle: [Heart Disease Classification](https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-datas)

### Features:
The dataset contains the following features:
- **age**: Age of the patient
- **sex**: Gender (1 = male, 0 = female)
- **cp**: Chest pain type (0 = typical angina, 1 = atypical angina, 2 = non-anginal pain, 3 = asymptomatic)
- **trestbps**: Resting blood pressure (mm Hg)
- **chol**: Serum cholesterol in mg/dl
- **fbs**: Fasting blood sugar (> 120 mg/dl, 1 = true, 0 = false)
- **restecg**: Resting electrocardiographic results (values 0, 1, 2)
- **thalach**: Maximum heart rate achieved
- **exang**: Exercise induced angina (1 = yes, 0 = no)
- **oldpeak**: ST depression induced by exercise relative to rest
- **slope**: Slope of the peak exercise ST segment (0 = upsloping, 1 = flat, 2 = downsloping)
- **ca**: Number of major vessels colored by fluoroscopy (0-3)
- **thal**: Thalium stress test result (1 = normal, 3 = fixed defect, 7 = reversible defect)
- **target**: Target variable (1 = disease, 0 = no disease)

## Approach
The workflow for the project includes the following steps:
1. **Problem Definition**: Can we predict heart disease from medical attributes?
2. **Data**: We used the Cleveland Heart Disease dataset.
3. **Evaluation Metric**: The aim is to reach at least 95% accuracy in predicting heart disease.
4. **Data Preprocessing**: The dataset is cleaned and prepared for modeling, including handling missing values, scaling, and encoding categorical variables.
5. **Exploratory Data Analysis (EDA)**: Visualization of the distribution of features, correlation analysis, and feature selection.
6. **Modeling**: Various machine learning algorithms are applied, including:
   - Logistic Regression
   - K-Nearest Neighbors (KNN)
   - Random Forest
7. **Hyperparameter Tuning**: We used `RandomizedSearchCV` and `GridSearchCV` to fine-tune model hyperparameters.
8. **Evaluation**: The models were evaluated using classification metrics such as accuracy, precision, recall, and F1-score.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/heart-disease-prediction.git
    ```
## Results
The model achieved a maximum accuracy of 95% with the Random Forest classifier after hyperparameter tuning. This met the project's evaluation goal.

## Conclusion
The heart disease prediction model provides a useful tool for classifying patients with a high degree of accuracy based on clinical parameters. Future work could include testing the model on different datasets and improving its robustness.
