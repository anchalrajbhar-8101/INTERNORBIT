# INTERNORBIT – Tech Internship Tasks

[![Python](https://img.shields.io/badge/Python-3.11-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](https://opensource.org/licenses/MIT)

A repository containing machine learning projects completed during the Tech Internship. This repository includes tasks on classification and prediction using real-world datasets. Each task contains data exploration, preprocessing, model training, evaluation, and visualization, organized in separate folders.

---

## 📌 Tasks Overview

### **Task 1: Iris Flower Classification**
- **Objective:** Classify Iris flowers into Setosa, Versicolor, or Virginica based on sepal and petal measurements.
- **Key Steps:**
  - Data exploration and visualization
  - Feature preprocessing and scaling
  - Training models: Logistic Regression, Decision Tree, Random Forest
  - Evaluation using accuracy, confusion matrix, and classification report
- **Key Insights:** Petal measurements are the most discriminative features; Logistic Regression and Decision Tree performed best with ~93% accuracy.

### **Task 2: Titanic Survival Prediction**
- **Objective:** Predict passenger survival on the Titanic based on features like age, gender, ticket class, fare, and cabin.
- **Key Steps:**
  - Data cleaning and handling missing values
  - Feature engineering (Title extraction, FamilySize, IsAlone)
  - Exploratory Data Analysis: univariate, bivariate, multivariate
  - Training models: Logistic Regression, Decision Tree, Random Forest
  - Evaluation using accuracy, confusion matrix, and classification report
- **Key Insights:** Gender, Pclass, and Fare are strong predictors; Logistic Regression and Random Forest showed the best performance.

---

## 🗂️ Folder Structure

INTERNORBIT/
├── Task_1_Iris_Classification/
│ ├── Iris_Classification_Notebook.ipynb
│ └── Dataset/
├── Task_2_Titanic_Survival/
│ ├── Titanic_Survival_Notebook.ipynb
│ └── Dataset/
├── README.md
└── LICENSE

---

## 🔑 Key Learnings
- Hands-on experience with classification and predictive modeling.
- Feature engineering and preprocessing are crucial for model performance.
- Visualization aids understanding of data patterns and feature importance.
- Comparing multiple models helps identify the best approach for a dataset.

---

## ⚡ Future Work
- Hyperparameter tuning using GridSearchCV or RandomizedSearchCV.
- Explore additional models like SVM, KNN, and ensemble methods.
- Implement cross-validation for robust model evaluation.
- Apply techniques to larger datasets for scalability testing.

---

## 📥 Dataset Sources
- **Iris Dataset:** [Link](https://storage.googleapis.com/kagglesdsdata/datasets/17860/23404/IRIS.csv)
- **Titanic Dataset:** [Link](https://storage.googleapis.com/kagglesdsdata/datasets/1818188/2965537/Titanic-Dataset.csv)
