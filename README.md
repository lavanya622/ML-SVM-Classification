# SVM Classification

## Overview

This project demonstrates the practical implementation of **Support Vector Machine (SVM)** for classification using the Car Evaluation dataset.

The project focuses on data preprocessing, categorical feature encoding, feature scaling, SVM classification, and model evaluation using the **RBF kernel**.

## Dataset

The dataset is based on **Car Evaluation** and contains the following features:

* `buying`
* `maint`
* `doors`
* `persons`
* `lug_boot`
* `safety`

### Target Variable

**`car`**

The target represents the evaluation category of the car.

The dataset contains classes such as:

* `unacc` — Unacceptable
* `acc` — Acceptable
* `good` — Good
* `vgood` — Very Good

## Workflow

The project follows this Machine Learning workflow:

**Dataset → Data Preprocessing → Categorical Encoding → Train-Test Split → StandardScaler → RBF SVM → Prediction → Model Evaluation**

## Data Preprocessing

The dataset contains categorical features, so the categorical values were converted into a numerical representation before training the model.

The data was then divided into training and testing sets.

## Feature Scaling

**StandardScaler** was used to scale the features before applying SVM.

Feature scaling is important for SVM because the algorithm is sensitive to the scale of input features.

## SVM Model

A **Support Vector Machine with an RBF (Radial Basis Function) kernel** was used for classification.

The RBF kernel allows the SVM model to handle non-linear relationships between features.

## Model Evaluation

The trained model was evaluated using **Accuracy** to measure the proportion of correctly classified samples.

The model prediction performance was evaluated on the test dataset.

## Key Learning

Through this project, I practiced:

* Support Vector Machine Classification
* RBF Kernel
* Categorical Data Encoding
* Train-Test Split
* Feature Scaling using StandardScaler
* Model Prediction
* Classification Accuracy

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook / VS Code

## Conclusion

This project provided practical experience in implementing **SVM Classification with an RBF kernel**.

It strengthened my understanding of categorical data preprocessing, feature scaling, non-linear classification, and model evaluation.

---
⭐ Part of my Machine Learning Practical Series

⭐ Part of my **Machine Learning Practical Series**
