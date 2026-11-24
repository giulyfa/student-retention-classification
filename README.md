# Higher Education Student Retention - Data-Centric AI

Data-centric analysis of a higher education student retention dataset using the **CRISP-DM methodology**, data quality assessment, and machine learning techniques.

This project is developed as part of the **Data-Centric AI** course examination at the University of Bologna.

## Dataset
[Predict Students' Dropout and Academic Success - Kaggle](https://www.kaggle.com/datasets/thedevastator/higher-education-predictors-of-student-retention)
* **4,424** instances
* **36** features (demographic, socio-economic, macroeconomic, and academic performance)
* **3** target classes (`Dropout`, `Enrolled`, `Graduate`)

## Project Objectives
* **Business Understanding:** Formulate domain hypotheses and define multi-class evaluation metrics (focusing on `Dropout` recall and Macro F1-Score).
* **Data Understanding & Quality Assessment:** Data profiling, missing values, duplicates, and verification of accuracy, completeness, and consistency.
* **Exploratory Data Analysis (EDA):** Univariate and bivariate analysis to test domain hypotheses and detect outliers or anomalies.
* **Data Preparation & Pipeline Design:** Leakage-free train/validation/test split, scaling, encoding, feature engineering/selection, and class imbalance handling.
* **Modeling & Evaluation:** Baseline vs. tuned classifiers, pipeline comparison, and error/fairness analysis.