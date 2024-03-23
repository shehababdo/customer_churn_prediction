# Customer Churn Prediction ML

 **Customer Churn Prediction - ReadMe**

**Project Overview**

This project develops a machine learning model to predict customer churn for a telecommunications company. It follows these key steps:

**1. Data Preparation**

* Loaded and explored the customer churn dataset.
* Handled missing values in the 'TotalCharges' column by filling with the mean.
* Cleaned feature names by converting them to lowercase.
* Transformed the 'churn' target variable into a numerical format (0/1).
* Identified and addressed class imbalance in the target variable.

**2. Exploratory Data Analysis**

* Analyzed the distribution of churned and non-churned customers.
* Calculated churn rates for different categories within categorical features.
* Visualized relationships between features and churn using bar plots.
* Identified the most important categorical features using mutual information.

**3. Feature Engineering**

* Created a tenure category feature for potential insights.

**4. Data Preprocessing**

* Separated categorical and numerical features.
* Applied one-hot encoding to categorical features.
* Scaled numerical features using StandardScaler.

**5. Model Development**

* Split the dataset into training, validation, and testing sets.
* Experimented with different classification models:
    * Logistic Regression (baseline)
    * Logistic Regression with only the most important categorical features
    * Logistic Regression with only numerical features
    * Decision Tree
* Evaluated model performance using accuracy, precision, recall, F1-score, and confusion matrix.
