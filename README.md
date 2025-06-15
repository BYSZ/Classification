# Classification
A real-world dataset is explored by implementing various classification algorithms.

## 📝 Description

The goal of this assignment is to implement and evaluate various classification algorithms on the **Breast Cancer Wisconsin Dataset**. The tasks include:

- Data pre-processing (missing values, normalization, label transformation)
- Implementation of the following classifiers:
  - Logistic Regression
  - Naïve Bayes
  - Decision Tree
  - K-Nearest Neighbours (with parameter tuning)
  - Support Vector Machine (with Grid Search)
  - Random Forest (with Grid Search)
  - Ensemble Methods: Bagging, AdaBoost, Gradient Boosting
- Performance evaluation using stratified 10-fold cross-validation

## 📊 Dataset

We use the **Breast Cancer Wisconsin** dataset.  
Due to academic policy, the version of the dataset provided by the course **is not included in this repository**.

If you would like to test the code, you may download the public version from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Original)) and rename it to `breast-cancer-wisconsin.csv`.

> Please ensure your version matches the format required by the assignment (including column headers and class labels).

## 📌 Project Motivation

This project applies machine learning techniques to medical diagnostics using the Breast Cancer Wisconsin dataset. It aims to build models that classify tumors as benign or malignant based on features from digitized biopsy images.

By comparing multiple classification algorithms (e.g., Logistic Regression, Decision Tree, KNN, SVM, and ensemble methods), the project reflects real-world model selection and optimization practices for clinical decision support.

The pipeline is designed to be generalizable, with robust preprocessing and cross-validation, making it applicable to broader use cases in healthcare, finance, and other classification tasks.

## ⚠️ Academic Integrity Notice

This repository contains code written for educational purposes.  

Please **do not copy** or reuse this work for academic submission in any course, as this may violate university academic honesty policies.  
You are welcome to use it as reference for personal learning, but not for plagiarism.
