# Assignment 2 — Predictive Modeling Project

This repository contains our end-to-end machine learning pipeline for CSE 158/258 Assignment 2.  
All analysis, modeling, and experiments are conducted in a single Jupyter notebook (hosted on Google Colab or Kaggle), with tracked metrics and hyperparameters stored remotely via DagsHub’s MLflow integration.

---

## Project Overview

This project follows the full machine-learning lifecycle required by the assignment:

1. **Dataset Selection & Task Definition**  
   We will choose one dataset (public or provided), describe its context, report statistics, and define a clear predictive task appropriate for the course.  
   *(Examples: classification, regression, ranking, recommendation, etc.)*

2. **Data Cleaning & Exploratory Analysis (EDA)**  
   - Inspect raw data  
   - Handle missing values, duplicates, and type conversions  
   - Generate descriptive statistics  
   - Visualize distributions, correlations, and feature patterns  

3. **Feature Engineering & Modeling**  
   - Prepare inputs for ML models (numeric, categorical, text, etc.)  
   - Implement course-relevant baseline models (e.g., Logistic Regression, Naive Bayes, Linear Regression)  
   - Build improved/advanced models (SVM, Random Forest, XGBoost, Matrix Factorization, etc.)  
   - Log all model runs to MLflow/DagsHub for experiment tracking  

4. **Evaluation & Comparison**  
   - Choose evaluation metrics appropriate for the predictive task  
   - Compare baselines vs. advanced models  
   - Visualize results (confusion matrices, ROC curves, feature importances, etc.)  
   - Select best model based on MLflow-tracked metrics  

5. **Discussion & Related Work**  
   - Review how similar datasets or tasks have been studied in prior work  
   - Compare our results with published findings when applicable  
   - Discuss limitations, failure cases, and potential improvements  

---

## MLflow Experiment Tracking (via DagsHub)

To maintain reproducibility and manage model experimentation cleanly, we use **DagsHub’s built-in MLflow tracking**.

Logged information includes:

- Model hyperparameters  
- Training/validation metrics  
- Feature configurations  
- Model artifacts  
- Best-performing run for each model type  

This allows the group to collaborate across machines (local, Colab, Kaggle, or Linux server) while keeping all experiment artifacts synchronized.
