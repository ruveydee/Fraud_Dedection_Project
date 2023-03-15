# Welcome to our Fraud Dedection Project!
<img src= "https://www.businessprocessincubator.com/wp-content/uploads/2018/10/www.fico_.comFraud-Management-Team-FIC-83f57a6ec467fcf8c7f911e7cbe2a56f802515b2.jpg" width = 400, height =300>

We implemented **Logistic Regression, Random Forest, XGBoost**,and **Neural Network** algorithms and Unbalanced Data Techniques . We Also visualized performances of the models using Seaborn, Matplotlib and Yellowbrick in a variety of ways.

<br>

Data drift and model drirft are key consepts about ML and MLOPS, we monitored and checked our data and models with plenty of ways and tools. **Deepchecks** is one of them and the leading tool for testing and for validating your machine learning models and data, and it enables doing so with minimal effort. In this project, we applied Data Integrity, Train-Test Validation, and Model Evaluation checks. Deepchecks Intruduction : https://youtu.be/7ELdizoi6BU

<br>

One of the challenges in this project is the absence of domain knowledge. So without knowing what the column names are, we only interested in their values. The other one is the class frequencies of the target variable are quite imbalanced.

# Determines
The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where it has **492** frauds out of **284,807** transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

Feature Information:

**Time**: This feature is contains the seconds elapsed between each transaction and the first transaction in the dataset.

**Amount**: This feature is the transaction Amount, can be used for example-dependant cost-senstive learning.

**Class**: This feature is the target variable and it takes value **1** in case of fraud and **0** otherwise.

## Tasks
3.0.0.1  1. Exploratory Data Analysis & Data Cleaning

<ul>
  <li>Import Modules, Load Data & Data Review</li>
  <li>Apply data integrity checks</li>
  <li>Exploratory Data Analysis</li>
  <li>Data Cleaning</li>
</ul>  

3.0.0.2  2. Data Preprocessing

<ul>
  <li>Train - Test Split</li>
  <li>Train - Test Split Validation Checks</li>
  <li>Scaling</li>
</ul> 

3.0.0.3  3. Model Building

<ul>
  <li>Logistic Regression</li>
  <li>Random Forest Classifier</li>
  <li>XGBoost Classifier</li>
  <li>Neural Network</li>
</ul> 

3.0.0.4  4. Model Deployement

<ul>
  <li>Save and Export the Best Model</li>
  <li>Save and Export Variables</li>
</ul> 

