Description
This project implements a linear, hard-margin Support Vector Machine (SVM) using quadratic programming (QP) via the cvxopt library. The LinearSVM-QP class is designed to train and classify data, following the familiar scikit-learn API structure.

Features
Training (fit): Uses a QP solver to optimize the separating hyperplane for linearly separable datasets.
Prediction (predict): Classifies new data points based on the trained SVM model.
Scikit-Learn API Compatibility: Methods are structured to align with scikit-learn's machine learning workflow.
