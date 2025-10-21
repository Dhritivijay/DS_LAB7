Lab 7: Logistic Regression from Scratch
 Overview

This experiment implements Logistic Regression from scratch using Python and NumPy.
The goal is to predict whether a person buys insurance based on their age using a simple binary classification model.

 Dataset

File: insurance_data.csv
Columns:

age → Age of the person

bought_insurance → Target variable (1 = Yes, 0 = No)

 Steps Involved

Data Loading & Normalization
The dataset is loaded using pandas and normalized for consistent scaling.

Model Implementation

Sigmoid activation function

Binary Cross-Entropy loss

Gradient Descent optimization

Training & Prediction
The model learns the relationship between age and the probability of buying insurance.

Evaluation

Confusion Matrix

Classification Report

Accuracy Score

Visualization

Loss curve

Logistic regression fit curve over data points

 Technologies Used

Python 

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn (for metrics only)

 Results

The loss curve shows smooth convergence.

Logistic curve fits the data accurately, demonstrating that as age increases, the probability of buying insurance increases.

Achieved high accuracy (around 90–95%).

 Outputs

 Loss Curve

 Confusion Matrix

Logistic Regression Fit

 Classification Report

Conclusion

Logistic Regression was successfully implemented from scratch.
The model effectively predicts binary outcomes and demonstrates the core concepts of logistic regression, gradient descent, and sigmoid activation
