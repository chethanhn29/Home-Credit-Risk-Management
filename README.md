# Home-Credit-Risk-Management
![images (2)](https://user-images.githubusercontent.com/110838853/211742625-8dec7141-1e7e-41c7-9dc8-0d3cb47ae279.jpg)                     ![download](https://user-images.githubusercontent.com/110838853/211743116-c221bd4a-034a-4faf-88c4-434425a279c7.png)

## Project Objective :
The objective of this project is to use historical loan application data to predict whether or not an applicant will be able to repay a loan. The goal is to build a model that can identify the loan applicants who are likely to repay the loan, allowing companies to avoid losses and incur profits.

## Introduction
An existential problem for any loan providers today is to find out the loan applicants who are very likely to repay the loan. This way companies can avoid losses and incur huge profits. Home Credit offers easy, simple and fast loans for a range of home appliances, mobile phones, laptops, two-wheelers, and varied personal needs. Home Credit comes up with a Kaggle challenge to find out the loan applicants who are capable of repaying a loan, given the applicant data, all credits data from Credit Bureau, previous applications data from Home Credit, and some more data.

## Problem Statement
Home Credit, a company that offers easy, simple and fast loans for a range of Home Appliances, Mobile Phones, Laptops, Two Wheeler's, and varied personal needs, has a challenge on Kaggle to find out the loan applicants who are capable of repaying a loan, given the applicant data, all credits data from Credit Bureau, previous applications data from Home Credit and some more data.

## Dataset Description
The datasets used in this project can be found on [Home Credit Default Risk](https://www.kaggle.com/competitions/home-credit-default-risk/data)

### application_{train|test}.csv: 
This is the main table, broken into two files for Train (with TARGET) and Test (without TARGET). Static data for all applications. One row represents one loan in the data sample.

### bureau.csv: 
All client's previous credits provided by other financial institutions that were reported to Credit Bureau (for clients who have a loan in the sample). For every loan in the sample, there are as many rows as number of credits the client had in Credit Bureau before the application date.

### bureau_balance.csv: 
Monthly balances of previous credits in Credit Bureau. This table has one row for each month of history of every previous credit reported to Credit Bureau.

### POS_CASH_balance.csv: 
Monthly balance snapshots of previous POS (point of sales) and cash loans that the applicant had with Home Credit. This table has one row for each month of history of every previous credit in Home Credit (consumer credit and cash loans) related to loans in the sample.

### credit_card_balance.csv: 
Monthly balance snapshots of previous credit cards that the applicant has with Home Credit. This table has one row for each month of history of every previous credit in Home Credit (consumer credit and cash loans) related to loans in the sample.

### previous_application.csv: 
All previous applications for Home Credit loans of clients who have loans in the sample. There is one row for each previous application related to loans in the data sample.

### installments_payments.csv: 
Repayment history for the previously disbursed credits in Home Credit related to the loans in the sample.

### HomeCredit_columns_description.csv:
This file contains descriptions for the columns in the various data files.

## Methodology
The project is broken down into the following steps:

#### 1.Exploratory Data Analysis (EDA)
#### 2.Feature Engineering
#### 3.Data Preparation
#### 4.Machine Learning Modelling
#### 5.Performance Metrics

### Conclusion
The models used in this project are Light Gradient Boosting Algorithm (LGBM) and Logistic Regression

## Results
The results of the project showed that
Project Title: Home Credit Risk Management
Project Description:
The objective of this project is to use historical loan application data to predict whether or not an applicant will be able to repay a loan. Home Credit, a company that offers easy, simple and fast loans for a range of Home Appliances, Mobile Phones, Laptops, Two Wheelers, and varied personal needs, has come up with a Kaggle challenge to find out the loan applicants who are capable of repaying a loan, given the applicant data, all credits data from Credit Bureau, previous applications data from Home Credit and some more data. The goal is to build a model to predict how capable each applicant is of repaying a loan, so that sanctioning loan only for the applicants who are likely to repay the loan.

Data:
The dataset consists of several different types of data, including information about the applicant, their credit history, previous loan applications, and their repayment history.
The data can be found here

Requirements:
The project is built on python3 and requires the following packages:

numpy
pandas
seaborn
matplotlib
sklearn
lightgbm
scikitplot
Installation:
Clone the repository
Create a virtual environment
Install the required packages using pip
Copy code
pip install -r requirements.txt
Usage:
Run the jupyter notebook
Run all the cells
Results:
The model uses Light Gradient Boosting Machine (LGBM) algorithm and compares it with Logistic Regression algorithm. The performance of the model is evaluated using various metrics such as Confusion matrix, Precision, Recall, F1 Score and ROC. The model with LGBM has a higher recall score of 64.59% and AUC of 0.73, compared to Logistic Regression model.

Further Improvements:
Further tuning of the LGBM model's hyperparameters
Ensemble techniques like XGboost and Random Forest
Use of oversampling techniques like SMOTE to handle class imbalance.
References:
https://www.kaggle.com/c/home-credit-default-risk/overview/evaluation
https://lightgbm.readthedocs.io/en/latest/
Contact:
For further questions or support, please contact the authors.
