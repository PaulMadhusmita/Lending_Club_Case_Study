# Lending Club Case Study
 
Lending Club is an online loan marketplace for personal & home loans, business loans, and financing of medical procedures.
Borrowers can easily access lower interest rate loan with investors looking to lend money and make a return.

When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile as borrowers who default cause the largest amount of loss to the lenders. 

There are two types of risks are associated with the bank’s decision:

1 > If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

2> If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company. These customers labelled as 'charged-off' are the 'defaulters'.  

Identifiying these risky loan applicants prior to loan approval can reduce the amount of credit loss.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information
Risk Analysis has been carried on based on the available dataset with respect to the descriptions available in the data dictionary, as per below steps:
https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fcdn.upgrad.com%2FUpGrad%2Ftemp%2Faf860da6-f838-47d6-ad97-551022550ee4%2FData_Dictionary.xlsx&wdOrigin=BROWSELINK
-  Step 1: Data Understanding
   Step 2: Data Cleaning and Manipulation as needed
   Step 3: Univariate Analysis
   Step 4: Segemented Univariate Analysis
   Step 5: Bivaraiate Analysis
   Step 6: Multivariate Analysis
   Step 7: Conclusion

- What is the background of your project?
  Exploratory Data Analysis (EDA) with respect to the complete loan data for all loans issued through the time period 2007 t0 2011. 

- What is the business probem that your project is trying to solve?
  Objective is to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default so that the company can utilise this knowledge for its portfolio and risk assessment. 

- What is the dataset that is being used?
 Complete loan data for all loans issued through the time period 2007 t0 2011.
 The data set being used has only the details of Approved Loans. Rejected loans are not accounted for this analysis.

## Conclusions
Based on deatiled analysis below are some of the attributes (but not limited to) that can help identify defaulters:
1. Maximum defaulters are higher for applicants with home ownership as MORTGAGE or OTHER
2. Loan amount requested for Small Business is highest and also have high defaulters followed by Credit Card & Debt Consolidation
3. Defaulters are higher for higher interest rate accross all categories
4. Defaulters are pretty high for funded amount between 10k to 15k and employee length 10+years
5. Chances of defaulting is higher when the funded amount is in range of 20K to 35K and annual income is between 75k to 140k

## Technologies Used
- Python Version: 3.9.7
- Pandas Version: 1.3.4
- Numpy Version: 1.20.3
- MatplotLib Version: 3.4.3
- Seaborn Version: 0.11.2

  Jupyter Notebook with Python code detailing the approach used for analysis
  Python Numpy library for data evaluation
  Pandas library to get an insight into the data frame
  Matplotlib and Seaborn to create various visualization charts for beter represntation and interpretation of data

## Acknowledgements
- This project was based on UpGrad AIML Course Case Study

## Contact
-Created by [@PaulMadhusmita] - feel free to contact me!
