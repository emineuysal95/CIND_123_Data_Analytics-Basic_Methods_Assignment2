# 🚢 Titanic Survival Prediction - Logistic Regression and KNN Models

This repository contains the R Markdown analysis and output files for a survival prediction task using the Titanic dataset. The work was completed for **CIND123 - Data Analytics: Basic Methods** by **Emine Uysal**.

## 📘 Objective

The goal is to apply classification techniques to predict Titanic passenger survival using:
- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**

The models are compared based on their predictive performance using confusion matrices and classification metrics.

---

## 📂 Dataset Overview

The dataset includes:
- `Survived` (target: 0 = No, 1 = Yes)
- `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`

Missing values in `Age` and `Embarked` were imputed or cleaned. Categorical variables were encoded as factors.

---

## 🔍 Model Implementation

### 🔹 Logistic Regression
- Implemented with `glm()` using the binomial family.
- Predicts the probability of survival.
- Binary predictions made using a 0.5 threshold.

### 🔹 K-Nearest Neighbors (KNN)
- Implemented using the `class::knn()` function.
- Applied after normalizing numeric features.
- Data was split into training and test sets.
- Optimal `k` value selected based on performance.

---

## 📊 Model Evaluation

Both models were assessed using:
- **Confusion Matrix**
- **Accuracy**
- **Precision**
- **Recall**

---

## 🛠 How to Reproduce

1. Open the `.Rmd` file in **RStudio**.
2. Ensure the following libraries are installed:
   - `tidyverse`
   - `caret`
   - `class`
   - `e1071`
   - `ggplot2`
3. Comment out all `install.packages()` lines before knitting.
4. Knit the file to both:
   - ✅ **HTML**
   - ✅ **PDF**

---

## 📄 Output Files

- `CIND123_Assignment2_Titanic.html` – full report in web format  
- `CIND123_Assignment2_Titanic.pdf` – full report in print-ready format

Both include:
- Data preparation steps
- Model training & prediction
- Evaluation metrics
- Confusion matrices
- Interpretation

---

## 👩‍💻 Author

**Emine Uysal**
Toronto Metropolitan University  
CIND123 – Assignment 2  
Date: July 2024

---




