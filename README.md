# 🧠 ADHD Prediction Using Machine Learning (Random Forest Classifier)

---

## 📌 1. Project Overview

**Title:** ADHD Prediction using Machine Learning  

### ❗ Problem Statement
Attention Deficit Hyperactivity Disorder (ADHD) affects many children worldwide, impacting their academic performance and daily life. It is characterized by symptoms such as inattention, hyperactivity, and impulsivity. Early identification is challenging but crucial for timely intervention.

### 🎯 Objective
- Develop a machine learning model to predict ADHD using behavioural and demographic features  
- Assist healthcare professionals in faster and more accurate diagnosis  
- Reduce manual effort using data-driven insights  

### 🌍 Scope & Applications
- Early screening tool for educators and parents  
- Decision support system for healthcare professionals  
- Educational assistance planning  

---

## 📖 2. Introduction

ADHD is a neurodevelopmental disorder that affects attention span, impulse control, and behaviour. Early detection enables better intervention strategies, improving academic and social outcomes.

Due to privacy concerns, real-world child data is not easily accessible. Hence, this project uses a **synthetic (dummy) dataset** to simulate real-world conditions.

---

## 🏥 3. How This Project Helps Hospitals

- **Early Detection** – Identifies ADHD at an early stage  
- **Decision Support** – Assists doctors alongside clinical evaluation  
- **Time Saving** – Reduces manual screening effort  
- **Improved Accuracy** – Minimizes human error  
- **Patient Management** – Helps in personalized treatment planning  

### 📍 Other Applications
- Schools & Educational Institutions  
- Mental Health Centres  
- Healthcare Web Applications  
- Research Organizations  

---

## 📊 4. Dataset Description

- **Type:** Synthetic Dataset  
- **Size:** 1000 records  

### 🔑 Features
- Age  
- Gender  
- Attention level score  
- Hyperactivity score  
- Impulsiveness score  
- Academic performance  
- Behavioural observations  

### 🎯 Target Variable
- ADHD (Yes / No)

---

## ⚙️ 5. Data Preprocessing

- Handling missing values  
- Feature engineering  
- Train-test split (80/20)  

---

## 📈 6. Exploratory Data Analysis (EDA)

### 🔍 Key Insights
- Hyperactivity and attention scores strongly influence ADHD prediction  
- Behavioural features show high correlation with ADHD  

---

## 🤖 7. Model Selection

**Algorithm Used:** Random Forest Classifier  

### 💡 Why Random Forest?
- Handles non-linear relationships  
- Reduces overfitting compared to decision trees  
- Works well with structured data  
- Provides high accuracy  

---

## 🏗️ 8. Model Training

- Dataset split into training and testing sets  
- Model trained using Random Forest  

### 🔧 Hyperparameters
- `n_estimators`  
- `max_depth`  

### 🛠️ Tools Used
- Python  
- Scikit-learn  
- Pandas, NumPy  
- Matplotlib  

---

## 📊 9. Model Evaluation

### 📏 Metrics Used
- Accuracy  
- Precision  
- Recall  
- F1-score  

### 📉 Confusion Matrix
- True Positive (TP)  
- False Positive (FP)  
- True Negative (TN)  
- False Negative (FN)  

---

## 📌 10. Results

- Model achieved good accuracy on test data  
- Random Forest captured complex patterns effectively  

---

## 🔄 11. System Flow
