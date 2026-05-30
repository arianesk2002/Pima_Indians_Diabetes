# 🧠 Pima Indians Diabetes Prediction

A machine learning project for predicting diabetes using the **Pima Indians Diabetes Dataset**.  
This project demonstrates a complete ML pipeline including preprocessing, model training, and evaluation for a **binary classification problem**.

---

## 📌 Problem Statement

Given medical diagnostic data of patients, the goal is to predict whether a patient has diabetes:

- `0` → No diabetes  
- `1` → Diabetes detected  

---

## 📊 Dataset

The dataset contains **768 samples** with the following features:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age
- Outcome (target)

---

## ⚙️ Workflow

The project follows a standard machine learning pipeline:

1. 📥 Load dataset
2. 🔍 Data exploration (EDA)
4. ✂️ Train-test split
5. 📏 Feature scaling
6. 🤖 Model training
7. 📊 Evaluation


---

## 🧹 Data Preprocessing

Some medical attributes contain invalid zero values. These are replaced using median imputation:

- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI

---

## 🚀 Results

The model performance is evaluated using a test set and standard classification metrics.  

---

## 🛠️ Technologies Used

- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

