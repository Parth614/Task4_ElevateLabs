
# 🧠 Breast Cancer Classification using Logistic Regression

## 📌 Project Overview

This project implements a **Logistic Regression model** to classify breast tumors as **Malignant (Cancerous)** or **Benign (Non-Cancerous)** using the Breast Cancer Wisconsin dataset.

The objective is to build a binary classifier and evaluate its performance using standard machine learning metrics.

---

## 📂 Dataset

* Dataset: Breast Cancer Wisconsin Dataset
* Type: Binary Classification
* Target Column: `diagnosis`

  * M → 1 (Malignant)
  * B → 0 (Benign)

---

## 🛠 Tools & Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## ⚙️ Steps Performed

1. Loaded and explored the dataset
2. Dropped unnecessary columns (`id`, `Unnamed: 32`)
3. Converted categorical target values to numeric (M → 1, B → 0)
4. Split data into training and testing sets
5. Standardized features using `StandardScaler`
6. Trained Logistic Regression model
7. Evaluated using:

   * Confusion Matrix
   * Precision
   * Recall
   * F1-Score
   * ROC-AUC Curve

---

## 📊 Model Performance

* High Accuracy (~97%)
* Very few misclassifications
* Strong Recall for malignant cases
* High ROC-AUC score indicating good classification ability

The model performs reliably for this medical classification problem.

---

## 📈 Evaluation Metrics Explained

* **Confusion Matrix** – Shows correct and incorrect predictions
* **Precision** – How many predicted cancer cases were actually cancer
* **Recall** – How many actual cancer cases were correctly detected
* **ROC-AUC** – Measures overall model performance

---

## 🎯 Conclusion

The Logistic Regression model successfully classified tumors with high accuracy and strong recall. The results indicate that the model is effective for binary classification tasks and suitable for medical prediction scenarios.

---
## 👨‍💻 Done By

Parth Gupta
AI & ML Internship – Task 1

---

