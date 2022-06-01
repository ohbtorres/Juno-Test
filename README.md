# Data Science Test

## Context
Juvo deals with a lot of Telco transactional data and uses this data to evaluate a user on multiple aspects like risk, churn, ability to pay etc...One of Juvo’s core products is airtime lending.

This assignment deals with a problem we usually face in every Telco we work with, which is assessing risk of repaying a loan.

## Datasets
You will find 3 csv files. The files were created from our database as of 2020 Feb 05.

## Brazil_DS_loans_2019-11-10_2019-12-05
It has the loans made for a period of 25 days with following important fields

* Loan_id - unique identifier for a loan
* Uuid - user identifier
* Created_at - time when loan was created
* Paid_at - time when it was paid. If it is missing then loan was not paid as of file creation date
* Amount - amount of loan

A loan is considered repaid if it's paid within 60 days.The objective is to create a predictive model for loan repayment based on the labels in this file.

## Brazil_DS_prev_loans
This has the previous loans taken for users in the above file and should have the same schema.

## Brazil_DS_recharges_2019-08-10_2019-12-05
A user pays for loans by making recharges after taking a loan. This file contains recharges for all users for about 4 months.

# Objective
Using the above files and tools of your choice, we need you to

Create a model to predict delinquency probability and measure its performance.
Submit a document that explains your methodology - preferably ipython notebooks
