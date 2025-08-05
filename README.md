# Diabetes ML Analysis

A comprehensive machine learning analysis on the Diabetes dataset to predict the onset of diabetes using various classification algorithms.

## Project Overview

This project aims to apply and compare multiple machine learning classification algorithms on the Diabetes dataset to predict whether a patient has diabetes or not. The workflow includes data preprocessing, exploratory data analysis (EDA), model training, evaluation, and performance visualization.

The implemented algorithms include:

- Logistic Regression    
- Random Forest  

By analyzing and comparing the models, this project demonstrates how different algorithms perform on medical data classification problems.

---

## Dataset

The Diabetes dataset used in this project is a well-known dataset from the UCI Machine Learning Repository. It contains several medical predictor variables and one target variable indicating the presence or absence of diabetes.

### Features include:

- Number of pregnancies  
- Glucose level  
- Blood pressure  
- Skin thickness  
- Insulin  
- Body Mass Index (BMI)  
- Diabetes pedigree function  
- Age

The target variable is a binary indicator (1: diabetic, 0: non-diabetic).

---

## Methods

### Data Preprocessing

- Handling missing or zero values in features where zero is not a valid value (e.g., glucose, blood pressure)  
- Feature scaling where appropriate  
- Splitting data into training and testing sets

### Machine Learning Models

- **Logistic Regression:** Baseline linear model for binary classification 
- **Random Forest:** Ensemble of decision trees to improve generalization

---

## Installation

To run this project locally, ensure you have Python 3.x installed along with the following packages:

```bash
pip install -r requirements.txt
```

---

## Key dependencies:

- numpy
- pandas
- scikit-learn
- matplotlib
- seaborn

---

## Results
The analysis shows that [your best performing model] achieves the highest accuracy of 77% on the test set, indicating strong predictive performance.

### Visualizations include:

Confusion matrices for all models
Accuracy comparison bar plots
The results highlight the trade-offs between different classifiers and their suitability for this medical dataset.
Email: iclalaca.ai@gmail.com

LinkedIn: www.linkedin.com/in/iclal-aca
