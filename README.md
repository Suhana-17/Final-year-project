# A Comparative Analysis of ANOVA and PCA for Modelling Credit Card Fraud Detection using Machine Learning

#Table of Contents : 
1.Introduction
2.Project Overview
3.Dataset
4.Methods
5.Results
6.Conclusion
7.Installation


#1.Introduction:
  This project explores the effectiveness of two statistical techniques, ANOVA (Analysis of Variance) and PCA (Principal Component Analysis), in the context of credit card fraud detection. By comparing these methods, we aim to determine which technique provides better modeling performance in identifying fraudulent transactions.

2.Project Overview:
  The primary goal of this project is to analyze and compare the performance of ANOVA and PCA in detecting credit card fraud. The project involves the following steps:
Data Preprocessing
Applying ANOVA and PCA
Building Machine Learning Models
Evaluating and Comparing Results

3.Dataset:
  The dataset used for this analysis is obtained from [source] (add a link if available). It contains transaction records labeled as fraudulent or non-fraudulent. The dataset includes various features such as transaction amount, time, and other relevant attributes.

4.Methods:
  ANOVA (Analysis of Variance)
ANOVA is used to identify significant features that differentiate between fraudulent and non-fraudulent transactions. It helps in selecting the most relevant features for model training.

  PCA (Principal Component Analysis)
PCA is a dimensionality reduction technique that transforms the original features into a set of linearly uncorrelated components. It helps in reducing the feature space while retaining most of the variance in the data.

Machine Learning Models
Various machine learning algorithms such as Logistic Regression, Decision Trees, and Random Forest are used to build models based on the features selected by ANOVA and PCA. The performance of these models is evaluated and compared.

5.Results:
  The results section presents a detailed comparison of the models' performance in terms of accuracy, precision, recall, F1 score, and other relevant metrics. Graphs and tables are used to illustrate the findings.

6.Conclusion:
  This section summarizes the key findings and insights gained from the comparative analysis. It discusses the advantages and limitations of using ANOVA and PCA for credit card fraud detection and provides recommendations for future work.

7.Installation:
  To run this project, you need to have the following dependencies installed:

Python 3.x
Jupyter Notebook
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
