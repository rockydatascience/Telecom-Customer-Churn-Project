# Customer Churn Analytics

## Abstract
In the competitive landscape of telecommunications, customer churn poses a significant challenge, impacting revenue and market share. This project aims to analyze customer churn patterns within a telecom company to understand the underlying factors contributing to customer attrition. The study leverages historical customer data, including demographic information, service usage metrics, and customer interaction logs. Through exploratory data analysis and predictive modeling techniques, key drivers of churn will be identified, such as service dissatisfaction, pricing strategies, contract terms, and customer support effectiveness.

## Problem Statement
The objective of this project is to analyze customer churn in a telecom company. Customer churn refers to the phenomenon where customers switch from one service provider to another or cancel their subscription altogether. By analyzing customer churn patterns, we aim to identify the factors that contribute to churn and develop strategies to mitigate it.

## Project Description
In this project, we will work with a dataset from a telecom company that includes information about their customers, such as demographics, customer accounting information, and service information. The dataset will also include a churn indicator that specifies whether a customer has churned or not.

## Desired Problem Outcome (Objective or Goal)
The main objective is to find out the reasons for call drops and voice connectivity. We aim to build a classification predictive model to predict call drops.

## Desired Outcome
Our main goal is to build a computer program that can predict when a customer might leave the company.

## Algorithms
- **Logistic Regression**
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **AdaBoost Classifier**
- **Gradient Boost Classifier**

## About the Data
The data is divided into three types:

### Demographic Information
- **Gender:** Whether the customer is male or female.
- **SeniorCitizen:** Whether the customer is a senior citizen or not (1, 0).
- **Partner:** Whether the customer has a partner or not (Yes, No).
- **Dependents:** Whether the customer has dependents or not (Yes, No).

### Customer Accounting Information
- **Contract:** The contract term of the customer (Month-to-month, One year, Two years).
- **PaperlessBilling:** Whether the customer has paperless billing or not (Yes, No).
- **MonthlyCharges:** The amount charged to the customer monthly.
- **TotalCharges:** The total amount charged to the customer.
- **Tenure:** Number of months the customer has stayed with the company.
- **PaymentMethod:** The customer's payment method (Electronic check, Mailed check, Bank transfer, Credit card (automatic)).
- **CustomerID:** Customer ID.

### Service Information
- **PhoneService:** Whether the customer has phone service or not (Yes, No).
- **MultipleLines:** Whether the customer has multiple lines or not (Yes, No, No phone service).
- **InternetService:** Customer's internet service provider (DSL, Fiber optic, No).
- **OnlineSecurity:** Whether the customer has online security or not (Yes, No, No internet service).
- **OnlineBackup:** Whether the customer has online backup or not (Yes, No, No internet service).
- **DeviceProtection:** Whether the customer has device protection or not (Yes, No, No internet service).
- **TechSupport:** Whether the customer has tech support or not (Yes, No, No internet service).
- **StreamingTV:** Whether the customer has streaming TV or not (Yes, No, No internet service).
- **StreamingMovies:** Whether the customer has streaming movies or not (Yes, No, No internet service).

### Target Variable
- **Churn:** Whether the customer has churned or not (Yes, No).
