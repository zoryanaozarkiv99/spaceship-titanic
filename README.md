# Spaceship Titanic Prediction Project 

This project is dedicated to solving a classification problem based on data from the Kaggle competition "Spaceship Titanic". The goal is to predict whether a passenger was transported to another dimension during a spacecraft collision with an anomaly.

## Project Stages

### 1. Research
- Data analysis (EDA) was performed and the relationship between passenger spending (TotalSpending) and their rescue was visualized.
- Data preprocessing was performed: gap filling, categorical feature encoding, and new feature creation (IsSpending).
- The full research code is available in the file: spaceship-titanic.ipynb.

### 2. Evaluation
A validation sample (20% of the data) was used to evaluate the quality of the model (Random Forest Classifier).
Results:
- Accuracy: 0.7263
- Metrics: Used classification_report (Precision, Recall, F1-score) and built an error matrix (Confusion Matrix) to analyze false predictions.

### 3. Implementation
- The model was trained on the full dataset.
- A Pipeline was created to automate data processing.
- The trained model was saved in a serialized file format: spaceship_titanic_model.pkl.

### 4. Deployment
- The submission.csv file was prepared for upload to Kaggle.
- The .pkl model file is ready to be used in third-party Python applications (e.g., via Flask or Streamlit).

## Tools Used
- Python: the main development language.
- Pandas & NumPy: data processing and analysis.
- Scikit-learn: machine learning model building and metrics.
- Matplotlib & Seaborn: results visualization.
- Joblib: saving the trained model.

## Repository structure
- spaceship-titanic.ipynb — main workbook with code.
- spaceship_titanic_model.pkl — saved trained model.
- submission.csv — prediction results for test data.
- requirements.txt — list of required libraries.
