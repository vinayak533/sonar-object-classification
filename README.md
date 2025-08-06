# 🔍 Sonar Object Classification using Logistic Regression

This machine learning project demonstrates how to classify sonar signals as either **Mine (M)** or **Rock (R)** using a **Logistic Regression** model. The sonar signals are represented by 60 numerical features that capture the energy reflected back at different frequencies.

---

## 📊 Problem Statement

Given a set of sonar signal readings, the task is to predict whether the object detected is a **mine** (submerged metal cylinder) or a **rock** based on the characteristics of the returned signal.

---

## 📁 Dataset Overview

- **Name**: Sonar, Mines vs. Rocks
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+(sonar,+mines+vs.+rocks))
- **Features**: 60 numerical values per observation (float type)
- **Target Classes**:
  - `M` → Mine
  - `R` → Rock
- **Samples**: 208 instances

---

## 🧠 Methodology

1. Load and explore the dataset
2. Preprocess data (no missing values)
3. Split data into training and test sets (70/30)
4. Train a Logistic Regression classifier
5. Evaluate accuracy on train and test sets
6. Make predictions on new input data

---

## 📈 Model Performance

- Model: **Logistic Regression**
- Accuracy: Achieved good accuracy on both training and test datasets
- Use Case: Quick binary classification using sonar signal characteristics

---

## 📌 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook


