# Project Name : Lending club case study
A consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicants profile. Two types of risks are associated with the banks decision:
-If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
-If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
EDA is used to understand banking and financial services data and how data is used to minimise the risk of losing money while lending to customers.


## Dependencies

To run this code, you'll need the following software to be downloaded:

- Anaconda Navigator 2.4.0
- Jupyter Notebook 6.5.2

## Installation and Setup
1. clone the repository:
git clone https://github.com/jainarpit1403/lending_case_study.git

2. Install the Anaconda Navigator 2.4.0 software


## Table of Contents

### Data Understanding, Cleaning and Preprocessing
- Data Source
- Data Types and Formats
- Data Quality Assessment 
- Missing Data Handling
- Outlier Detection and Treatment 
- Data Trasformation

### Data Analysis
- Derived Metrics
- Univariate Analysis
- Segmented Univariate Analysis
- Bivariate Analysis
- Multivariate Analysis


## General Information
This assignment focuses on using Exploratory Data Analysis (EDA) to solve real business problems related to risk analytics in the banking and financial services industry. The case study revolves around a consumer finance company that specializes in lending loans to urban customers. When the company receives a loan application, they need to assess the risk associated with approving the loan.

Two types of risks are involved in the decision-making process. Firstly, if a loan is not approved for a reliable applicant, it results in a loss of potential business for the company. Secondly, if a loan is approved for an applicant who is likely to default, it can lead to financial losses for the company.

The provided dataset contains information about past loan applicants and whether they have defaulted on their loans or not. The objective is to identify patterns and factors that indicate whether a person is likely to default. This knowledge can be used to take actions such as denying the loan, reducing the loan amount, or lending to risky applicants at higher interest rates.

When a person applies for a loan, there are three possible outcomes: the loan is fully paid, the applicant is currently paying the installments (not labeled as defaulted), or the applicant has defaulted by not paying the installments for an extended period. The dataset does not include information on rejected loans.

The business objectives of the company are to minimize credit losses, which occur when borrowers default and fail to repay their loans. By identifying risky loan applicants through EDA, the company can reduce the number of such loans, thereby minimizing credit losses. This information can also help the company in portfolio management and risk assessment.

The company in question is the largest online loan marketplace, providing various types of loans with lower interest rates and a fast online application process. Identifying risky applicants is crucial for reducing credit losses, as defaulters cause the most significant financial loss to the lenders.

The aim of this case study is to understand the key factors or variables that drive loan defaults. By identifying strong indicators of default through EDA, the company can make informed decisions and assess risk more effectively.

The dataset used in this case study covers loan data issued between 2007 and 2011. It provides comprehensive information for analysis and understanding of the loan portfolio during that period.

To enhance your understanding of the domain, it is recommended to research risk analytics and gain insights into different types of variables and their significance in assessing loan default risk.

## Conclusions

#### Conclusions of univariate analaysis
- Grades A and B receive the most loans, particularly grades A4, B3, A5, B5, and B4.
- 36-month loans are more common than 60-month loans.
- Borrowers with 10 or more years of experience are more likely to be granted loans.
- Loan numbers have steadily increased over the years, with the highest amount borrowed in 2011. 
- Loan numbers peak in October, November, and December.
- Approximately 15% of loans result in charge-offs.
- Loans are predominantly issued in the states of CA, NY, FL, and TX.
- Debt consolidation, credit card repayment, and other purposes account for the majority of loans.
- Education and renewable energy loans are infrequent.
- Individuals residing in rented or mortgaged homes receive the most loans.
- Loan amounts range from $5,000 to $15,000.
- Installment amounts typically fall between $200 and $400.
- The median amount-to-income ratio is approximately 0.18, indicating favorable loan terms.
- Loans with interest rates between 9% and 13% are the most common.
- Loans with rates between 21% and 25% are less prevalent.

#### Conclusions of Bivariate and Multivariate Analysis

- Loan default tendency increases as the grade of the loan goes from A to G.
- Borrowers in subgrades F5, G3, and G5 exhibit the highest likelihood of loan default.
- Self-employed borrowers, as well as those with 10 and 7 years of employment, have a higher tendency to default on loans.
- Borrowers from the states NV, TN, SD, AK, FL, and HI demonstrate the highest tendency to default on loans.
- Small business category borrowers have the highest chances of loan default.
- Borrowers classified as "Other" have the highest tendency to default on loans.
- Loan default tendency is higher among borrowers in lower income groups, decreasing as annual income increases.
- There is a positive correlation between the interest rate and loan default tendency.
- The correlation graph indicates that variables such as annual income, installment, issue month, loan amount-to-income ratio, loan amount, funded amount, and issue year have a negative impact on the loan status variable.


## Technologies Used
- Anaconda Navigator 2.4.0
- Jupyter Notebook 6.5.2
- Python 

## Acknowledgements
Give credit here.
- This project was inspired by Upgrad 
- References:  
    - https://www.kaggle.com/
    - https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.html
    - https://www.python.org/


## Contact
Created by [@jainarpit1403] - feel free to contact me!
