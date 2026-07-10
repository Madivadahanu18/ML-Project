# Breast Cancer Classification: A Comparison of KNN Random Forest and XGBoost
## Overview

This project is about comparing three machine learning algorithms.
These are K-Nearest Neighbors, Random Forest and XGBoost.
The models are. Evaluated on the Breast Cancer Wisconsin Diagnostic Dataset.
The goal is to classify tumors as Benign or Malignant.
We want to see which algorithm is the accurate for breast cancer diagnosis.
The Breast Cancer Wisconsin Diagnostic Dataset is used for this project.
This dataset has numerical features.
These features are extracted from images of breast mass cell nuclei.

# Dataset

- Dataset: Breast Cancer Wisconsin Diagnostic Dataset
- Target Variable: diagnosis

M means Malignant
B means Benign

The dataset has features.
These features help us classify tumors.

# Machine Learning Algorithms

## 1 K-Nearest Neighbors (KNN)

K-Nearest Neighbors is an algorithm.
It classifies a data point based on its nearest neighbors.
It works well when the data is standardized.

**Advantages**
- Easy to understand
- Works on small datasets
- No training required
KNN is a good algorithm.
It is simple and effective.

## 2 Random Forest

Random Forest is an algorithm.
It combines decision trees.
This approach improves accuracy. Reduces overfitting.

**Advantages**
- accuracy
- Handles complex datasets
- Less prone to overfitting
- Provides stable predictions
Random Forest is a powerful algorithm.
It works well on datasets.

## 3 XGBoost

XGBoost is a boosting algorithm.
It builds trees sequentially.
Each new tree corrects the mistakes of trees.
This results in accurate predictions.

**Advantages**
- Excellent performance
- Handles missing values
- Reduces overfitting
- Widely used in competitions
XGBoost is an algorithm.
It is widely used in machine learning competitions.

# Methodology

We followed these steps:
1. Loaded the Breast Cancer Wisconsin Dataset.
2. Removed unnecessary columns.
3. Checked for missing values.
4. Removed outliers.
5. Split the dataset into training and testing sets.
6. Standardized the feature values.
7. Trained the KNN, Random Forest and XGBoost classifiers.
8. Predicted the test data.
9. Evaluated the models using Accuracy Score.
We used an approach.
This helped us compare the algorithms fairly.

# Model Performance

| Algorithm                | Accuracy |
|--------------------------|-----------:|
|K-Nearest Neighbors (KNN) | **94.74%** |
|Random Forest             | **96.49%** |
| XGBoost                  | **95.61%** |

The results are clear.
Random Forest is the accurate algorithm.

# Best Performing Model

Random Forest achieved the accuracy.
It outperformed KNN and XGBoost.
This makes it the effective model for this dataset.

### Performance Ranking

🥇 Random Forest – **96.49%**
🥈 XGBoost – **95.61%**
🥉 K-Nearest Neighbors (KNN) – **94.74%**
The ranking is clear.
Random Forest is the algorithm.

**#Conclusion**

This study shows that all three algorithms perform well.
However Random Forest is the accurate.
It is the effective model for breast cancer diagnosis.
Random Forest is a choice.
It provides generalization and reduces overfitting.

# Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- XGBoost
- Google Colab
These helped us build and evaluate the models.

# Author

**Madivada Hanu Harshitha**
B.Tech – Artificial Intelligence and Machine Learning
Shri Vishnu Engineering College for Women
