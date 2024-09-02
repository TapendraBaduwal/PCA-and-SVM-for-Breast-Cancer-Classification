# PCA-and-SVM-for-Breast-Cancer-Classification

This project focuses on the application of Principal Component Analysis (PCA) for dimensionality reduction and Support Vector Machine (SVM) for classifying breast cancer tumors.

## Overview

The goal of this project is to enhance the accuracy and efficiency of predictive models by reducing the dimensionality of the dataset using PCA and then applying SVM for classification. PCA helps in retaining the most informative features, while SVM is used to classify the tumors as benign or malignant.

## Dataset

The breast cancer dataset used in this project contains features derived from digitized images of fine needle aspirates (FNA) of breast masses. These features include various characteristics of cell nuclei such as radius, texture, perimeter, area, and more, leading to a total of 30 features.

## Methodology

1. **Dimensionality Reduction with PCA:**
   - Computed the covariance matrix to understand relationships between features.
   - Calculated eigenvalues and eigenvectors to determine principal components.
   - Reduced the dataset from 30 features to 14 principal components, capturing 98-99% of the variance.

2. **Classification with SVM:**
   - Implemented a linear SVM to classify the tumors.
   - Achieved an accuracy of 97.4% with strong precision and recall metrics.

## Conclusion

The PCA effectively reduced the dimensionality of the breast cancer dataset while preserving critical information, resulting in a more efficient and accurate SVM classification model. The high accuracy achieved demonstrates the model's effectiveness in distinguishing between benign and malignant tumors.

## References

- UCI Machine Learning Repository: Breast Cancer Wisconsin (Diagnostic) Data Set
- Principal Component Analysis - Visual Studio Magazine
