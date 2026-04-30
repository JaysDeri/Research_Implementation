# Data Preprocessing Impact on Machine Learning Performance

## Implementation Part

## Overview

This repository contains the **implementation part** of the research study:

**“An Experimental Study on the Effect of Data Preprocessing Techniques on Machine Learning Model Performance”** 

The goal of this implementation is to experimentally evaluate how different **data preprocessing techniques** influence the performance of various machine learning models on the **Pima Indians Diabetes dataset**.

---

## Objectives

* Apply multiple preprocessing techniques to the dataset
* Train and compare several classification models
* Analyze how preprocessing affects model performance
* Validate findings presented in the research paper

---

## Project Structure

```id="cbf3lo"
Implementation_Part/
│── Implementation_Part_D.ipynb   # main experimental notebook
│── diabetes.csv                 # dataset
│── README.md                    # project documentation
```

---

## Technologies Used

* Python
* Pandas, NumPy
* Plotly
* Scikit-learn

---

## Preprocessing Techniques Implemented

This implementation covers the key preprocessing categories described in the research:

### 1. Missing Value Handling

* Replacement of invalid zero values with NaN
* Imputation methods:

  * Mean imputation
  * Median imputation

### 2. Feature Scaling

* Min-Max Normalization
* Z-score Standardization

### 3. Dimensionality Reduction

* Principal Component Analysis (PCA)
* Linear Discriminant Analysis (LDA)

### 4. Advanced / Transformation

* Quantile Transformation
* Decimal Normalization

---

## Machine Learning Models

The following classifiers were implemented and evaluated:

* Logistic Regression
* Random Forest
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Decision Tree
* Gradient Boosting / XGBoost

---

## Experimental Setup

* Multiple preprocessing pipelines were created
* Models were trained using:

  * Cross-validation
  * Hyperparameter tuning (RandomizedSearchCV)
* Performance compared across different preprocessing strategies
* All models are tuned using RandomizedSearchCV with 5-fold cross-validation, optimizing for ROC AUC.

---

## Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* ROC AUC

Additional analysis includes:

* Confusion matrices
* ROC curves

---

## Key Findings (from implementation)

* Preprocessing significantly affects model performance
* Tree-based models are less sensitive to scaling
* LDA may lead to high precision but low recall
* SVM achieved the best overall results

---

## Authors

* Iliyas Aruzhan
* Zhurymbay Akbike

---
