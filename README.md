# Heart Disease Prediction
- This project demonstrates how to analyze and predict the presence of heart disease based on various features related to patient data, including age, cholesterol levels, heart rate, and other relevant attributes.

# Purpose
- The goal of this project is to explore a dataset containing various heart disease-related factors and build a model to predict the likelihood of heart disease based on those features.

# Dataset
- The dataset used in this project contains the following columns:
- Age: Age of the patient.
- Sex: Sex of the patient (1 = male, 0 = female).
- cp: Chest pain type (categorical variable).
- trestbps: Resting blood pressure (in mm Hg).
- chol: Serum cholesterol (in mg/dl).
- fbs: Fasting blood sugar (>120 mg/dl, 1 = true, 0 = false).
- restecg: Resting electrocardiographic results.
- thalach: Maximum heart rate achieved.
- exang: Exercise induced angina (1 = yes, 0 = no).
- oldpeak: ST depression induced by exercise relative to rest.
- slope: Slope of the peak exercise ST segment.
- ca: Number of major vessels colored by fluoroscopy.
- thal: Thalassemia (1 = normal, 2 = fixed defect, 3 = reversable defect).
- target: Target variable (1 = presence of heart disease, 0 = absence).

# Workflow

1. Data Loading:
- The dataset is loaded using pandas (pd.read_csv()).
- The data is explored briefly using df.head() to understand the structure.

2. Feature and Target Split:
- The features (X) are separated from the target variable (y), where X contains all columns except the target, and y contains the target column.

3. Data Visualization:
- Boxplots are used to visualize the distribution of specific features like resting blood pressure (trestbps), cholesterol levels (chol), and maximum heart rate achieved (thalach).

4. Data Preprocessing:
- Standard scaling or other transformations can be applied to ensure the features are in a suitable format for modeling.

5. Model Building:
- A variety of machine learning models, such as logistic regression or decision trees, can be used to predict the presence or absence of heart disease based on the features.

# Installation
- You can install the required libraries by running:
- pip install pandas numpy scikit-learn seaborn matplotlib
