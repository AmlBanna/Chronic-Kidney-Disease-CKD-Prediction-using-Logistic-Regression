# 🩺 Chronic Kidney Disease (CKD) Prediction using Logistic Regression

This project builds a machine learning model to predict **Chronic Kidney Disease (CKD)** using patient medical data. Early detection of CKD can significantly improve treatment outcomes and patient care.

---

## 📌 Objective

To apply logistic regression to medical records and determine whether a patient is likely to have CKD or not.

---

## 📊 Dataset Information

- **Name**: Early Stage of Indian CKD
- **Instances**: 400 (250 with CKD, 150 without CKD)
- **Attributes**: 25 (11 numeric, 14 nominal)
- **Target**: `class` → ckd / notckd
- **Source**: Dr. P. Soundarapandian, Apollo Hospitals, India  
- **Creator**: L. Jerlin Rubini, Alagappa University  
- **Date**: July 2015  
- **Missing Values**: Yes, denoted by `?`

---

## 📂 Features

Some of the key features used in this dataset:

| Feature | Description |
|--------|-------------|
| `age` | Age of the patient |
| `bp` | Blood Pressure (mm/Hg) |
| `sg` | Specific Gravity |
| `al` | Albumin level |
| `su` | Sugar level |
| `rbc` | Red Blood Cells (normal/abnormal) |
| `pc` | Pus Cell |
| `bgr` | Blood Glucose Random |
| `bu` | Blood Urea |
| `sc` | Serum Creatinine |
| ... | ...and more |

---

## ⚙️ Technologies Used

- Python
- Pandas & NumPy
- Seaborn & Matplotlib (for visualization)
- Scikit-learn (for model building and evaluation)

---

## 🧪 Workflow

1. Load and explore the dataset
2. Handle missing values and clean the data
3. Encode categorical variables
4. Split the data into training and testing sets
5. Build a **Logistic Regression** model
6. Evaluate the model using Accuracy, Confusion Matrix, etc.

---

## 📈 Model Performance

- Classifier: **Logistic Regression**
- Accuracy: *~99%*
- Evaluation metrics:
  - Confusion Matrix
  - Classification Report

