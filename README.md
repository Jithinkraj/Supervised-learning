# Breast Cancer Classification

## Objective
The objective of this project is to evaluate the understanding and ability to apply supervised learning techniques to a real-world dataset, specifically the Breast Cancer Wisconsin (Diagnostic) dataset available in the sklearn library.

## Dataset
The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) dataset from sklearn. It contains 569 samples with 30 features each, and the target variable indicates whether the tumor is malignant or benign.

## Description
This project involves the following key components:

### 1. Loading and Preprocessing 
- **Loading the Dataset**: The dataset is loaded using the `load_breast_cancer` function from sklearn.
- **Preprocessing**: 
  - Handling missing values (if any).
  - Feature scaling using `StandardScaler` to standardize the features.

### 2. Classification Algorithm Implementation 
Implemented the following five classification algorithms:
1. **Logistic Regression:** A linear model for binary classification that estimates the probability that a given input belongs to a certain class.
2. **Decision Tree Classifier**: Splits the data into subsets based on the value of input features, creating a tree-like model of decisions.
3. **Random Forest Classifier**: An ensemble method that combines multiple decision trees to improve accuracy and control overfitting.
4. **Support Vector Machine (SVM)**: Finds the hyperplane that best separates the classes in the feature space.
5. **k-Nearest Neighbors (k-NN)**: Classifies a sample based on the majority class among its k nearest neighbors.

### 3. Model Comparison 
- Compared the performance of the five classification algorithms.
- Identified the best and worst performing algorithms based on accuracy.

## Results
- **Logistic Regression Accuracy**: 97%
- **Decision Tree Accuracy**: 95%
- **Random Forest Accuracy**: 96%
- **SVM Accuracy**:97%
- **k-NN Accuracy**:95%

## Conclusion
Based on the accuracy and classification report metrics,Logistic Regression and the Support Vector Machine (SVM)performed the best, while the k-Nearest Neighbors (k-NN) and Decision Tree Classifier performed the worst. Random Forest's ensembleapproach provided better generalization and robustness, making it the most suitable model for this dataset.This analysis gives an idea of which algorithm is most suitable for this dataset, considering both the performance and the characteristics of the data.
