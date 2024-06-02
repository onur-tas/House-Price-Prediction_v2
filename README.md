# House-Price-Prediction

# Data Science Final Project

## InfoTech Academy
### 02.06.2024

### About the Project
This project focuses on predicting house prices. Various data processing and machine learning techniques were used to accurately predict house prices.

### Contents
1. [Introduction](#introduction)
2. [Data Preprocessing](#data-preprocessing)
3. [Clustering](#clustering)
4. [Regression Model](#regression-model)
5. [Model Evaluation](#model-evaluation)
6. [Results and Outputs](#results-and-outputs)
7. [Team](#team)
8. [Summary of Findings](#summary-of-findings)
9. [Acknowledgments](#acknowledgments)

### Introduction
- **Topic:** House Price Prediction
- **Goal:** To predict house prices using data analysis techniques and machine learning models.
- **Project Objective:** To increase the accuracy of models using training and testing processes.

### Data Preprocessing
- **Handling Missing Data:** Missing data were filled using various methods (mean, median, mode).
- **Feature Engineering:** New features were created (e.g., `zipcode` from `lat` and `long`).
- **Data Normalization:** Data were normalized using standard scaling techniques.

### Clustering
- **Methods Used:** Clustering was performed using K-Means and Large Language Models (LLM).
- **Determining Number of Clusters:** The optimal number of clusters was determined using the Elbow method.
- **Outliers Cleaning:** Outliers were cleaned using ECOD (Empirical Cumulative Outlier Detection).

### Regression Model
- **Model 1: XGBoost (Cluster 0)**
  - **R² Score:** 0.870325
  - **RMSE:** 106848.09959

- **Model 2: XGBoost (Cluster 1)**
  - **R² Score:** 0.76
  - **RMSE:** 75000

- **Model 3: CatBoost (Cluster 2)**
  - **R² Score:** 0.86
  - **RMSE:** 115000

### Model Evaluation
- **Model Performance:** Models were evaluated using various metrics (R² score, RMSE).
- **Comparison:** The performances of different regression models were compared, and the best performing model was selected.
- **Visualization:** The accuracy and error rates of the models were visualized with graphs.

### Results and Outputs
- **Clustering Results:** Three different clusters were identified, and the best regression model was selected for each cluster.
- **Model Performances:** Performance metrics for the best model in each cluster are summarized below.
  - **Cluster 0:** XGBoost is the best model.
  - **Cluster 1:** XGBoost is the best model.
  - **Cluster 2:** CatBoost is the best model.
- **Feature Importance:** The importance levels of features used in the models were visualized and evaluated.

### Team
- **Onur**
- **Yusuf**
- **Sema**
- **Murat**
- **Durukan**

### Summary of Findings
- **Key Findings:** The best models for different clusters were identified and model performances were compared.
- **Future Work:** It is recommended to increase performance with more data and different model trials.

### Acknowledgments
- Thank you to all team members for their contributions.
- Thanks to mentors and advisors who provided support throughout the project.
