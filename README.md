Practicallab2

Machine Learning Project2

Iris Dataset Classification 🏵️

Overview

This project demonstrates exploratory data analysis (EDA), preprocessing, and classification of the Iris dataset using Python and scikit-learn. The goal is to understand the dataset, apply preprocessing techniques, train multiple machine learning models, and evaluate their performance.

Dataset: Iris Dataset (multiclass classification: setosa, versicolor, virginica)

Features

Sepal length (cm)

Sepal width (cm)

Petal length (cm)

Petal width (cm)

Target: Species (setosa, versicolor, virginica)

Project Steps
1. Exploratory Data Analysis (EDA)

Checked dataset shape, features, and class distribution

Detected missing values (none found)

Analyzed feature statistics (mean, median, std dev)

Visualized data: histograms, boxplots, bar charts, correlation heatmaps

Insights from EDA:

No missing values → no imputation required

Strong correlation between petal length & petal width → may influence model selection

Class distribution is balanced → no resampling required

2. Data Preprocessing

Encoded categorical variables (if any)

Standardized numerical features

Split dataset into training (80%) and testing (20%) sets

3. Modeling

Trained three classifiers:

Logistic Regression

Decision Tree

k-Nearest Neighbors (kNN)

Predictions were evaluated using:

Accuracy

Precision, Recall, F1-score

Confusion Matrix

ROC Curve & AUC


4. Insights & Next Steps

EDA guided preprocessing: Standardization improved kNN performance

Best model: Logistic Regression (highest accuracy and stable performance)

Class balance: No resampling needed

Improvement ideas: Hyperparameter tuning, feature engineering, or using ensemble methods (Random Forest, Gradient Boosting)
