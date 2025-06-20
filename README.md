🩺 Female Diabetes Prediction Using Support Vector Machine (SVM)

📌 Overview

This project aims to build a machine learning system that predicts whether a female patient is likely to have diabetes, based on diagnostic measurements. Leveraging a Support Vector Machine (SVM) algorithm, the model achieves reliable classification performance by processing real-world health data.

📂 Dataset

The dataset was sourced from a publicly available file:
Download Diabetes Dataset (CSV)

The dataset contains 768 records of female patients aged 21 or older.
Features include:
Pregnancies
Glucose
BloodPressure
SkinThickness
Insulin
BMI
DiabetesPedigreeFunction
Age
The target variable is: Outcome (0 = non-diabetic, 1 = diabetic)
🧠 Objective

To develop a predictive system that accurately classifies female patients as diabetic or non-diabetic using their medical records, based on supervised learning.

⚙️ Methodology

1. Data Collection & Exploration
Loaded dataset from Dropbox CSV link
Explored structure, data types, and missing values
Performed statistical summaries and visualizations
2. Data Preprocessing
Standardized features using StandardScaler
Handled any zeros or missing-like values for proper ML input
Split data into training (80%) and testing (20%) sets
3. Model Training
Used Support Vector Machine (SVM) with a linear kernel
Trained the model on the standardized training data
4. Model Evaluation
Evaluated accuracy on test data
Generated classification reports (precision, recall, F1-score)
Built a prediction system for user-input data
📊 Results

Model: SVM Classifier (Linear Kernel)
Accuracy Score: [insert accuracy score here]
The predictive system shows promising results in identifying diabetic cases based on the input features.
