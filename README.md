# Spam Email Detection Methods Comparison


This project focuses on comparing various machine learning methods for detecting spam emails. The primary goal is to evaluate the performance of different classifiers on the SPAMBASE dataset.


## Introduction
Spam emails are unsolicited messages that often contain advertisements, phishing links, or malware. Detecting spam emails is crucial for maintaining the security and efficiency of email communication. This project compares six different spam email detection methods to determine the most effective approach.

## Dataset
The SPAMBASE dataset, sourced from the UCI Machine Learning Repository, is used in this project. It contains 4,601 email instances, each with 57 attributes. These attributes include word frequencies, character frequencies, and other features that help distinguish between spam and non-spam emails.

## Methods
The following machine learning methods were compared in this project:

1. **Naive Bayes**: A probabilistic classifier based on Bayes' theorem with strong independence assumptions.
2. **Support Vector Machine (SVM)**: A classifier that finds the hyperplane that best separates the data into different classes.
3. **Random Forest**: An ensemble method that uses multiple decision trees to improve classification accuracy.
4. **K-Nearest Neighbors (KNN)**: A non-parametric method that classifies instances based on the majority class of their nearest neighbors.
5. **Logistic Regression**: A statistical model that uses a logistic function to model a binary dependent variable.
6. **Decision Tree**: A model that uses a tree-like graph of decisions and their possible consequences.

## Results
The performance of each method was evaluated using metrics such as accuracy, precision, recall, and F1-score. The results showed that:

- **Random Forest** achieved the highest accuracy, followed by SVM and Logistic Regression.
- **Naive Bayes** performed well in terms of precision but had lower recall compared to other methods.
- **KNN** and **Decision Tree** had moderate performance but were less effective than ensemble methods like Random Forest.

## Conclusion
The comparison indicates that ensemble methods, particularly Random Forest, are highly effective for spam email detection. However, the choice of method may vary depending on the specific requirements and constraints of the application.

