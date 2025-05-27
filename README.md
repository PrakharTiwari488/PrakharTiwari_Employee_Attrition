# PrakharTiwari_Employee_Attrition
Employee Attrition Prediction
Overview
This project aims to predict whether an employee is likely to leave the company using the IBM HR Analytics dataset. By leveraging a Random Forest classifier, the model classifies employees as either staying or leaving based on various features such as job role, overtime status, monthly income, and job satisfaction. The project also visualizes feature importance to help understand which factors most influence attrition.

Features
Data preprocessing including handling missing values and encoding categorical variables

Splitting data into training and testing sets

Training a Random Forest classification model

Model evaluation with metrics: accuracy, precision, recall, F1-score

Confusion matrix visualization using heatmaps

Feature importance analysis for interpretability

Getting Started
Prerequisites
Python 3.x

Libraries: pandas, scikit-learn, matplotlib, seaborn

You can install the required libraries using:

bash
Copy
Edit
pip install pandas scikit-learn matplotlib seaborn
Usage
Upload the IBM HR Analytics CSV dataset to the project folder or your environment.

Run the Python script or Jupyter notebook to preprocess data, train the Random Forest model, and evaluate results.

View classification reports, confusion matrix heatmaps, and feature importance plots to interpret model performance.

Dataset
The IBM HR Analytics dataset contains employee records with features related to demographics, job role, work environment, and attrition status.

Results
The Random Forest model achieved good classification performance, accurately identifying employees likely to leave. Feature importance analysis revealed key attrition drivers, which can help HR teams focus retention efforts more effectively.

Future Work
Experiment with other classifiers like SVM, Gradient Boosting, or Neural Networks

Perform hyperparameter tuning to improve model accuracy

Address class imbalance to reduce false negatives and false positives

Develop an interactive dashboard for HR insights
