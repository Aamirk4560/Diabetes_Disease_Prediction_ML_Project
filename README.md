"""
# Diabetes Disease Prediction Machine Learning Project

## Introduction
This project involves building machine learning models to predict diabetes based on various health metrics. The dataset used contains information such as glucose level, blood pressure, and BMI among others.

## Dataset Exploration
The dataset consists of 1536 rows and 9 columns. There are no missing values in the dataset.

## Outliers Analysis
Outliers were removed from the dataset using the IQR method. Box plots were used to visualize the outliers before and after removal.

## Exploratory Data Analysis (EDA)
Descriptive statistics were calculated for numerical features, and histograms were used to visualize their distributions. A heatmap and pair plot were used to explore correlations between features.

## Data Preprocessing
The dataset was split into training and testing sets with an 80-20 ratio. The number of occurrences of each class in both sets was checked to ensure a balanced distribution.

## Model Building and Evaluation
Four machine learning models were trained and evaluated:
1. K-Nearest Neighbors (KNN)
2. Naive Bayes
3. Decision Tree
4. Random Forest

Confusion matrices were generated for each model to evaluate their performance in terms of accuracy, sensitivity, specificity, precision, classification error, and false positive rate.

## Model Evaluation
The performance of each model was summarized using a tabular format, including accuracy, sensitivity, specificity, precision, classification error, and false positive rate.

For more details, refer to the code and comments provided in the GitHub repository.
"""
