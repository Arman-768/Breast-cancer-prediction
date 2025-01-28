# Breast Cancer Prediction
Breast Cancer Prediction is a machine learning classification project aimed at predicting the diagnosis of a breast mass as either malignant (M) or benign (B). This project leverages a dataset containing features computed from digitized images of fine needle aspirate (FNA) of breast masses. The features describe various characteristics of cell nuclei present in the images.

# Introduction
Early detection of breast cancer can significantly improve treatment outcomes. This project builds predictive models using machine learning to assist in diagnosing breast cancer based on cell nucleus features.

# Dataset Details
The dataset contains features computed from digitized FNA images.
Key details:
Target Variable: Diagnosis (M for Malignant, B for Benign).
Features:
Radius, Texture, Perimeter, Area, Smoothness, Compactness, Concavity, Concave Points, Symmetry, Fractal Dimension, and more.

# Technologies Used
Python
Libraries: NumPy, Pandas, Matplotlib, Seaborn, scikit-learn.

# Exploratory Data Analysis
The following techniques were used:
Feature correlation heatmap
Bar plots for diagnosis distribution
Data cleaning and preprocessing to handle missing or irrelevant columns.

# Model Development
Decision Tree Classifier:
Accuracy: 93.5%
Logistic Regression:
Accuracy: 96%

# Results
Logistic Regression outperformed the Decision Tree Classifier with higher accuracy and recall.
Logistic Regression is recommended for this task due to better consistency.
