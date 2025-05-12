# Credit-Card-Fraud-Detection
Credit Card Fraud Detection: Capstone Project (BA)
    
# Project Overview
This project focuses on detecting credit card fraud, a significant challenge for financial institutions due to the drastic increase in fraudulent transactions with the rise of digital payments and online shopping. The primary objective is to identify and flag potentially fraudulent transactions before they occur, thereby minimizing financial losses for the bank and maintaining customer trust and the bank's reputation. While catching fraudsters is beyond the scope of an AI/ML model, the timely identification of suspicious activities can help retain customers, especially high-profile ones. This project analyzes transaction data to build a cost-effective machine learning model that can distinguish between legitimate and fraudulent transactions, ultimately contributing to revenue by controlling fraud-related costs.   

# Problem Statement
The core problem is the increasing number of fraudulent credit card transactions and the delay by customers in reporting these incidents to the bank. This delay and the occurrence of fraud impact the bank's credibility and reputation. 

- The project aims to:   
1. Identify fraudulent transactions proactively.    
2. Develop a machine learning model that is cost-effective in mitigating fraud-related losses.    
3. Provide business insights and strategies to the bank for optimal fraud risk mitigation.    
4. A root cause analysis (detailed in Rising_Frauds_RCA.pdf) indicated that rising frauds are due to factors including customers not adhering to security 
   best practices, merchants' insufficient data sanctity checks, and banks' limitations in timely fraud identification and customer alerting.   

# Dataset
Source: The primary dataset used for model building was obtained from Kaggle: Fraud Detection Dataset.   
This includes fraudTrain.csv (1,296,675 transactions) and fraudTest.csv (555,719 transactions). These were concatenated for analysis.   
Description: The dataset comprises details of 1,852,394 credit card transactions from 1,000 customers across multiple merchants, spanning from January 1, 2019, to December 31, 2020.   

It contains 23 columns, including transaction details, customer information (gender, job, location), merchant details, and a target variable is_fraud.   
A key characteristic of the dataset is its imbalance: only 9,651 transactions (0.52%) are fraudulent.   

# Project Pipeline
The project followed a structured data science pipeline:   

- Business Understanding: Defining the problem, objectives, and scope.   
- Data Understanding & Cleaning  
- Exploratory Data Analysis (EDA): Univariate and bivariate analyses were performed to understand data distributions and relationships.
- Visualizations were created to identify patterns in fraudulent vs. non-fraudulent transactions. 
- Feature Engineering
- Model Building
- Model Evaluation
- Cost-Benefit Analysis
 
# Results & Conclusion
The project aimed to build a machine learning model capable of detecting fraudulent credit card transactions effectively. The model, once developed and fine-tuned, would be subjected to a cost-benefit analysis to demonstrate its value in terms of financial savings by preventing fraud and reducing associated operational costs. The final model's performance and the outcome of the cost-benefit analysis would determine the recommendations to the bank regarding the adoption of this fraud detection system.
