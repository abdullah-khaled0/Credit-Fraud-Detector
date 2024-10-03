# Credit Fraud Detector

![](https://www.techopedia.com/wp-content/uploads/2024/06/60-Global-Credit-Card-Fraud-Statistics-in-2024.webp)

## Introduction
The **Credit Fraud Detector** is a machine learning project designed to accurately detect fraudulent transactions. Using various predictive models, we aim to determine whether a transaction is a normal payment or fraudulent. The dataset features are anonymized and scaled to protect privacy, but key insights can still be uncovered through analysis.

This project will guide you through essential steps in working with imbalanced datasets, including handling distribution issues, applying various sampling techniques, and evaluating classifier performance.

## Goals
- Understand the distribution of the provided data.
- Create a balanced dataset using the NearMiss algorithm (50/50 ratio of Fraud vs. Non-Fraud transactions).
- Test multiple classifiers and identify the most accurate one.
- Build a Neural Network and compare its performance against the best classifier.
- Understand common mistakes when working with imbalanced datasets.

## Project Outline

### I. Understanding the Data
- **Data Exploration**: Analyzing the structure and key characteristics of the dataset.

### II. Preprocessing
- **Scaling and Distributing**: Ensuring the data is ready for analysis.
- **Data Splitting**: Separating training and testing data.

### III. Random UnderSampling & OverSampling
- **Distributing and Correlating**: Visualizing data relationships.
- **Anomaly Detection**: Identifying patterns indicative of fraud.
- **Dimensionality Reduction and Clustering (t-SNE)**: Reducing complexity for better insights.
- **Classifiers**: Implementing and testing various machine learning algorithms.
- **Logistic Regression Analysis**: Deep dive into logistic regression performance.
- **Oversampling with SMOTE**: Addressing class imbalance with Synthetic Minority Over-sampling Technique (SMOTE).

### IV. Testing Models
- **Logistic Regression**: Evaluating performance on fraud detection.
- **Neural Network Testing**: Comparing Neural Network performance using undersampling and oversampling techniques.

## Key Learnings About Imbalanced Datasets
1. **Avoid Testing on Oversampled/Undersampled Data**: Always test on the original dataset.
2. **Cross-validation Considerations**: When using cross-validation, oversample or undersample within the training data in each fold.
3. **Choose the Right Evaluation Metric**: Accuracy can be misleading in imbalanced datasets. Use metrics such as F1-score, precision/recall, or the confusion matrix for a clearer picture.

## References
- *Hands-on Machine Learning with Scikit-Learn & TensorFlow* by Aurélien Géron (O'Reilly, 2017).
- *Machine Learning - Over-& Undersampling* by Coding-Maniac.
- *AUPRC, 5-fold C-V, and Resampling Methods* by Jeremy Lane (Kaggle Notebook).

## Conclusion
The **Credit Fraud Detector** project demonstrates the importance of handling imbalanced datasets and choosing the right models and evaluation metrics to detect fraud effectively. We hope this project helps you understand key fraud detection techniques and encourages you to explore further into machine learning solutions for real-world problems.

Happy coding!
