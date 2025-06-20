# 🩺 Female Diabetes Prediction Using Support Vector Machine (SVM)

---

## 📌 Overview

This project aims to build a machine learning system that predicts whether a female patient is likely to have diabetes, based on diagnostic measurements. Leveraging a Support Vector Machine (SVM) algorithm, the model achieves reliable classification performance by processing real-world health data.

---

## 📂 Dataset

The dataset was sourced from a publicly available file:  
[Download Diabetes Dataset (CSV)](https://www.dropbox.com/scl/fi/0uiujtei423te1q4kvrny/diabetes.csv?rlkey=20xvytca6xbio4vsowi2hdj8e&e=1&dl=0)

- The dataset contains **768 records** of female patients aged 21 or older.
- Features include:
  - Pregnancies
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
  - DiabetesPedigreeFunction
  - Age
- The target variable is: **Outcome** (0 = non-diabetic, 1 = diabetic)

---

## 🧠 Objective

To develop a **predictive system** that accurately classifies female patients as diabetic or non-diabetic using their medical records, based on supervised learning.

---

## ⚙️ Methodology

1. **Data Collection & Exploration**  
   - Loaded dataset from Dropbox CSV link  
   - Explored structure, data types  
   - Performed statistical summaries  

2. **Data Preprocessing**  
   - Standardized features using `StandardScaler`  
   - Split data into training (80%) and testing (20%) sets  

3. **Model Training**  
   - Used Support Vector Machine (SVM) with a linear kernel  
   - Trained the model on the standardized training data  

4. **Model Evaluation**  
   - Evaluated accuracy on data  
   - Built a prediction system for user-input data  

---

## 📊 Results

- **Model:** SVM Classifier (Linear Kernel)  
- **Accuracy Score:** 79%

The predictive system shows promising results in identifying diabetic cases based on the input features.

---

## 👨‍💻 Author

**Manuk Manukyan**

---

