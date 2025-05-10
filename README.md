# 🩺 Diabetes Prediction using Machine Learning

This project focuses on building a machine learning model that predicts whether a person has diabetes based on various health-related features. It uses the Pima Indians Diabetes Dataset and applies a Support Vector Machine (SVM) classifier for binary classification.

---

## 📌 Project Overview

Diabetes is a major health issue affecting millions globally. Early detection can help in managing the condition and preventing complications. This project demonstrates how machine learning can be used to predict diabetes using a set of diagnostic medical features.

---

## 📂 Dataset

- **Source:** [Kaggle – Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Features:** 8
  - Pregnancies  
  - Glucose  
  - BloodPressure  
  - SkinThickness  
  - Insulin  
  - BMI  
  - DiabetesPedigreeFunction  
  - Age
- **Target:**  
  - `1` → Diabetic  
  - `0` → Non-Diabetic

---

## 🧰 Technologies Used

- Python 3.x  
- Jupyter Notebook  
- NumPy  
- Pandas  
- Scikit-learn (SVM, preprocessing, accuracy metrics)

---

## 🛠️ Project Workflow

1. **Data Loading:** Read CSV file using Pandas  
2. **Data Exploration & Cleaning:** Handle missing values, check balance of target classes  
3. **Feature Selection & Preprocessing:** Normalize input features using `StandardScaler`  
4. **Train-Test Split:** 80% training and 20% testing using `train_test_split()`  
5. **Model Training:** SVM with linear kernel  
6. **Evaluation:** Accuracy score on training and test sets  
7. **Prediction System:** Accepts new patient data and predicts diabetes status

---

## 🔍 Model Performance

| Dataset       | Accuracy |
|---------------|----------|
| Training Data | ~78.5%   |
| Test Data     | ~77.9%   |

---

## 🧪 Sample Prediction

```python
# Sample input for prediction
input_data = (5, 166, 72, 19, 175, 25.8, 0.587, 51)

# Output
# The person is diabetic
