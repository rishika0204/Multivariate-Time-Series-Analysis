# Multivariate-Time-Series-Analysis

## Overview
This project implements various machine learning algorithms for regression, classification, and clustering tasks on a weather dataset. The project was completed as part of the Machine Learning course (BITS F464) at BITS Pilani.

## Dataset
The project uses a weather dataset from Kaggle, which includes historical weather data with the following features:
- Formatted Date
- Summary
- Precip Type
- Temperature (C)
- Apparent Temperature (C)
- Humidity
- Wind Speed (km/h)
- Wind Bearing (degrees)
- Visibility (km)
- Pressure (millibars)
- Daily Summary

Dataset source: [Weather Dataset on Kaggle](https://www.kaggle.com/datasets/muthuj7/weather-dataset/data)

## Algorithms Implemented

### Regression
1. Linear Regression
2. Random Forests
3. Extra Random Forests
4. AdaBoost

### Classification
1. Naive Bayes
2. K-Nearest Neighbors (KNN)
3. Support Vector Machines (SVM)
4. Decision Trees

### Clustering
1. K-Means
2. Expectation-Maximization (EM) Clustering
3. K-Medoids

## Results

### Classification Performance Comparison

| Algorithm      | Accuracy | Precision | Recall | F1 Score |
|----------------|----------|-----------|--------|----------|
| Naive Bayes    | 0.9401   | 0.9037    | 0.9871 | 0.9435   |
| KNN            | 0.99613  | 0.99244   | 1      | 0.99620  |
| SVM            | 0.9925   | 0.9854    | 1      | 0.9926   |
| Decision Trees | 0.99927  | 0.99857   | 1      | 0.99928  |

### Clustering
- The optimal number of clusters (K) was determined using the Elbow Method for each clustering algorithm.
- For K-Means and EM-Clustering, the optimal K was found to be 3.

## Conclusion
Decision Trees performed the best overall for the classification task, with the highest scores in accuracy, precision, recall, and F1 score. KNN and SVM also performed well, while Naive Bayes had the lowest scores but still achieved respectable performance, especially in recall.
