# 🧠 Breast Cancer Classification with Logistic Regression

This repository contains the solution for **Task 4** of my **AI & ML Internship**, which involves building a binary classifier using Logistic Regression on the **Breast Cancer Wisconsin Dataset**.

---

## 📂 Dataset

- **Source**: [Kaggle - Breast Cancer Wisconsin Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- **Target Variable**: `diagnosis` (M = Malignant, B = Benign)

---

## 📌 Objectives

1. Load and preprocess a binary classification dataset.
2. Train a Logistic Regression model.
3. Evaluate the model using key metrics.
4. Visualize the ROC-AUC curve.
5. Tune the classification threshold and understand the sigmoid function.

---

## 🛠️ Tools Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 🧪 Model Evaluation

- **Confusion Matrix**
- **Precision, Recall, F1-Score**
- **ROC-AUC Score and Curve**
- **Threshold Tuning**

---

## 🧾 Steps Performed

### ✅ 1. Data Preprocessing
- Loaded dataset from CSV.
- Dropped unnecessary columns like `id` and `Unnamed: 32`.
- Encoded the `diagnosis` column to binary (`M = 0`, `B = 1`).
- Checked for and handled missing/constant features.
- Split into training and testing sets.
- Scaled features using `StandardScaler`.

### ✅ 2. Model Training
- Used `LogisticRegression` from Scikit-learn.
- Fitted on the training set.

### ✅ 3. Model Evaluation
- Printed the confusion matrix.
- Generated a classification report (precision, recall, F1).
- Calculated ROC-AUC score and plotted ROC curve.

### ✅ 4. Threshold Tuning
- Custom classification threshold applied (e.g., 0.6).
- Re-evaluated metrics to see effect of threshold.

### ✅ 5. Sigmoid Function
- Explained and visualized how the sigmoid function maps real values to [0, 1].



## 📎 Files Included

- `data.csv` – Dataset file (if uploaded locally)
- `logistic_regression_breast_cancer.ipynb` – Main notebook
- `README.md` – This file

---

## ✅ How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/breast-cancer-logistic-regression.git


## 👩‍💻 Author
Name: Kannati Naveena
GitHub: https://github.com/kannatinaveena
Internship: AI & ML Internship Task 4 – Binary Classification
Date: May 2025
