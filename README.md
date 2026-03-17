# Wage Prediction & Regression Model Comparison using Machine Learning

## Overview

This project explores wage prediction using a structured machine learning pipeline, focusing on comparing multiple regression models to identify the most accurate and robust approach.

The analysis combines **data preprocessing, feature engineering and model optimization** to understand the key drivers of income and improve predictive performance.

---

## Business Problem

Understanding wage determinants is essential for:

* Labor market analysis
* Compensation benchmarking
* Workforce strategy and policy design

Traditional statistical approaches often fail to capture complex relationships between demographic, educational, and occupational factors.

This project addresses:

* How accurately can wages be predicted using available features?
* Which variables most influence income levels?
* Which regression model performs best in a real-world dataset?

---

## Project Objective

To build and evaluate multiple regression models and select the best-performing one based on cross-validation performance, ensuring robustness and generalization. 

---

## Dataset

The dataset contains demographic and professional attributes used to predict wages.

### Features include:

* Age
* Education level
* Occupation / job category
* Work-related attributes
* Other socio-economic indicators

### Target Variable:

* **Wage (continuous variable)**

---

## Methodology

The project follows a structured machine learning workflow aligned with best practices:

### 1. Data Preprocessing

* Handling missing values using appropriate imputation methods
* Cleaning and preparing data for modeling

### 2. Exploratory Data Analysis (EDA)

* Analysis of numerical and categorical variables
* Identification of patterns, distributions, and relationships

### 3. Feature Engineering

* One-hot encoding for categorical variables
* Feature selection to reduce noise and improve performance
* Standard scaling applied where necessary

---

### 4. Model Development

Three or more regression models were tested using **grid search optimization**:

* Linear Regression
* Tree-based models (e.g., Random Forest / Gradient Boosting)
* Additional regression algorithms for comparison

Each model was evaluated using:

* Training score
* Test score
* Cross-validation score

Ensuring no overfitting and strong generalization performance

---

### 5. Model Selection

The final model was selected based on:

* Highest cross-validation score
* Stability across training and test sets

---

### 6. Model Evaluation

* Residual analysis to assess prediction errors
* Feature importance analysis to interpret model behavior

---

## Key Insights

### Drivers of Wage

* Education level plays a significant role in income prediction
* Professional category strongly influences wage distribution
* Age and experience contribute but are not linear predictors

---

### Modeling Insights

* Linear models show limitations in capturing complex relationships
* Tree-based models significantly improve predictive performance
* Feature interactions are critical to understanding wage dynamics

---

## Results

* Advanced regression models outperform baseline linear approaches
* Cross-validation confirms model robustness
* Residual distribution indicates improved prediction accuracy with optimized models

---

## Business Impact

This project demonstrates how machine learning can support:

### Workforce Strategy

* Better understanding of salary structures
* Identification of key drivers of compensation

### HR & Talent Analytics

* Data-driven salary benchmarking
* Fair compensation analysis

### Policy & Economic Analysis

* Insights into income inequality
* Evidence-based labor market decisions

---

## Limitations

* Missing external variables (e.g., company size, location, industry specifics)
* Potential bias in categorical encoding
* Wage prediction limited by available features

---

## Future Improvements

* Incorporate additional socio-economic variables
* Apply advanced models (e.g., XGBoost, neural networks)
* Improve interpretability using SHAP values
* Deploy as an interactive salary prediction tool

---

## Project Structure

```
wage-prediction-ml/
│
├── notebook.ipynb        # Full analysis and modeling
├── report.html           # Final report with narrative
├── data/                 # Dataset
└── README.md             # Project overview (this file)
```

---

## License

This project is licensed under the **MIT License**.

You are free to use, modify, and distribute this project with proper attribution.

---

## About Me

MSc in AI Management @ ESSCA (Paris)
Background in **Design, Data Analytics, and AI-driven Strategy**

I focus on building solutions that combine **data, business understanding, and user-centered design** to create meaningful impact.

---

## Key Takeaway

> Wage prediction is not driven by isolated variables, but by **interactions between demographic, educational, and professional factors**.
> Machine learning models that capture these relationships provide more accurate and actionable insights for real-world decision-making.

---
