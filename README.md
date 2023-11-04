# Neural-Networks-2

Data Preprocessing and Churn Classification Modeling

This repository contains Python code for data preprocessing and training a churn (customer attrition) classification model using the scikit-learn library.

Prerequisites
Before running the code, you need to have the following libraries installed in your Python environment:

pandas
scikit-learn
You can install them via pip using the following commands:

Copy code
pip install pandas
pip install scikit-learn
Code Description
The code in this repository performs the following steps:

Loads a dataset from an Excel file named "churn.xlsx" using pandas.
Conducts exploratory data analysis, including handling missing values and statistical description of variables.
Imputes missing values in the "TotalCharges" column with the mean.
Encodes categorical variables using LabelEncoder and One-Hot Encoding.
Splits the dataset into training and testing sets.
Applies data normalization using StandardScaler.
Trains an MLP (Multi-Layer Perceptron) classification model with three hidden layers.
Evaluates the model's performance based on accuracy and the F1 score.
How to Run the Code
You can run the code in a Python environment that meets the mentioned prerequisites. Make sure to have the "churn.xlsx" file in the same directory where the code is located.

Execute the code and observe the performance metrics, including accuracy and the F1 score.

Author
[Guilherme B. Correia]

