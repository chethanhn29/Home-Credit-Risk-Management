# Home-Credit-Risk-Management
![images (2)](https://user-images.githubusercontent.com/110838853/211742625-8dec7141-1e7e-41c7-9dc8-0d3cb47ae279.jpg)                     ![download](https://user-images.githubusercontent.com/110838853/211743116-c221bd4a-034a-4faf-88c4-434425a279c7.png)

## Project Objective :
The objective of this project is to use historical loan application data to predict whether or not an applicant will be able to repay a loan. The goal is to build a model that can identify the loan applicants who are likely to repay the loan, allowing companies to avoid losses and incur profits.

## Problem Statement
Home Credit, a company that offers easy, simple and fast loans for a range of Home Appliances, Mobile Phones, Laptops, Two Wheeler's, and varied personal needs, has a challenge on Kaggle to find out the loan applicants who are capable of repaying a loan, given the applicant data, all credits data from Credit Bureau, previous applications data from Home Credit and some more data.

## Dataset Description
The dataset used for this project is from the Home Credit Default Risk Kaggle competition. It includes the following files:

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

