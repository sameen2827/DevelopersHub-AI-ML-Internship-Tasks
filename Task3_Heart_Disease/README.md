# Task 3: Heart Disease Prediction

## Objective
The objective of this task is to build a Machine Learning model that predicts whether a patient is at risk of heart disease based on their medical and health-related attributes.

## Dataset Used
Heart Disease UCI Dataset

Features:
- Age
- Sex
- Chest Pain Type (cp)
- Resting Blood Pressure (trestbps)
- Cholesterol Level (chol)
- Fasting Blood Sugar (fbs)
- Resting ECG Results (restecg)
- Maximum Heart Rate Achieved (thalch)
- Exercise-Induced Angina (exang)
- ST Depression (oldpeak)
- Slope of ST Segment
- Number of Major Vessels (ca)
- Thalassemia (thal)

Target Variable:
- 0 = No Heart Disease
- 1 = Heart Disease Present

Total Samples: 920

## Libraries Used
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-Learn
- Jupyter Notebook

### Data Inspection
- Loaded dataset
- Checked dataset shape
- Displayed column names
- Viewed first five rows
- Generated dataset information
- Generated statistical summary
- Checked missing values

### Data Preprocessing
- Handled missing values
- Converted categorical features into numerical format
- Created binary target variable
- Prepared features and target data

### Exploratory Data Analysis (EDA)
- Target Distribution Analysis
- Age Distribution Analysis
- Correlation Heatmap
- Feature Relationship Analysis

### Model Building
- Split dataset into training and testing sets
- Trained Logistic Regression model
- Generated predictions on test data

### Model Evaluation
- Accuracy Score
- Classification Report
- Confusion Matrix
- ROC Curve
- AUC Score

### Feature Importance Analysis
- Identified important features affecting heart disease prediction
- Visualized feature importance using bar charts

## Key Findings
- Age, chest pain type, maximum heart rate, and exercise-induced angina significantly influence heart disease prediction.
- The Logistic Regression model successfully classified patients into heart disease and non-heart disease categories.
- The ROC Curve demonstrated the model's ability to distinguish between classes effectively.
- Feature importance analysis highlighted the most influential medical attributes.

## Results
The Heart Disease UCI Dataset was successfully analyzed and processed. A Logistic Regression model was trained and evaluated using multiple performance metrics. The project demonstrated the complete machine learning workflow, including data preprocessing, exploratory data analysis, classification modeling, and feature importance analysis for healthcare prediction tasks.