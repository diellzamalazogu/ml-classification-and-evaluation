# Machine Learning Classification and Evaluation Project

This repository contains a machine learning project focusing on data classification using several classifiers and evaluating their performance. The classifiers applied include Decision Trees, Naive Bayes, and Support Vector Machines (SVMs). It also explores feature normalization techniques and performance evaluation using metrics like accuracy, sensitivity, specificity, and ROC curves.

## Project Overview
- **Data Preprocessing**: Feature scaling using min-max normalization and z-score normalization.
- **Classification Models**: 
  - Decision Trees
  - Naive Bayes
  - Support Vector Machines (SVMs)
  - k-Nearest Neighbors (k-NN)
- **Evaluation Metrics**:
  - True Positive Rate (TPR)
  - False Positive Rate (FPR)
  - Accuracy, Sensitivity, Specificity
  - ROC Curves for model performance.

## Files Included
- **`datasets/spam.csv`**: The dataset used for classification tasks.
- **`notebooks/classification_and_evaluation.ipynb`**: The main Jupyter notebook containing the implementation of the classifiers and the evaluation metrics.

## Instructions for Running the Code
1. Install the necessary Python packages:
   ```bash
   pip install numpy pandas scikit-learn matplotlib seaborn
