# Stroke Prediction

## Introduction
Stroke is a leading cause of death and disability worldwide, affecting millions of people annually. This project aims to develop predictive models to identify individuals at high risk of stroke based on various health metrics and demographic factors. By leveraging advanced machine learning techniques, the goal is to enhance early detection and preventive healthcare strategies, ultimately reducing the incidence and impact of strokes.

## Models Used

### Logistic Regression
A fundamental model used for its simplicity and interpretability, providing baseline performance metrics.

### K-Nearest Neighbors (K-NN)
This model was utilized to capture local patterns and clusters within the data, enhancing prediction accuracy.

### Random Forest
Chosen for its ability to handle complex interactions and avoid overfitting, Random Forest provided the best performance in our evaluation.
evaluation.

### Here we are using GridSearchCV as it finds best hyperparameters for models with in set of parameter grid

## Dataset
The dataset used for this project is sourced from Kaggle and can be accessed [Kaggle | Health dataset](https://www.kaggle.com/datasets/prosperchuks/health-dataset/data). This dataset is mostly preprocessed, making it suitable for immediate use in modeling and analysis. It includes various health metrics and demographic factors essential for predicting stroke , and also dataset for Diabetes and Hypertension are avaiable in the same link


