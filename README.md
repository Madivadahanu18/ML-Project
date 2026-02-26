# Breast Cancer Classification using KNN

## Overview
In this project, I built a machine learning model to predict whether a tumor is malignant or benign using the Breast Cancer dataset from Kaggle. I used the K-Nearest Neighbors (KNN) algorithm and implemented it in Python with the help of Scikit-learn. The project was developed and tested in Google Colab.
The main aim was to understand how KNN works and apply it to a real medical dataset.

## Dataset
The dataset contains different medical measurements taken from breast mass images. These features help in identifying whether the tumor is:
* M → Malignant
* B → Benign
I divided the dataset into training and testing data to check how well the model performs on unseen data.

## Tools and Libraries Used
* Python
* NumPy
* Pandas
* Scikit-learn
* Matplotlib

## Algorithm
KNN is a simple classification algorithm. It checks the nearest data points and predicts the class based on the majority among them. The value of K determines how many neighbors are considered before making a prediction.

## Model Evaluation
To measure the model performance, I used:
* Accuracy score
* Classification report
* Confusion matrix
These metrics help in understanding how correctly the model predicts the tumor type.

## Conclusion
This project helped me understand how machine learning can be used in healthcare for prediction tasks. Even a simple algorithm like KNN can give good results when applied properly.
