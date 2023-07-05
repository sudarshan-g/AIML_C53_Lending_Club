# Lending Club Case Study
 
## Table of Contents
* [General Info](#problem-statement)
* [Libraries Used](#libraries-used)
* [Conclusions](#conclusions)
* [Contact](#contact)

## Problem Statement
Lending Club is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures.

Two types of risks are associated with the bank’s decision:
If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
If the applicant is not likely to repay the loan, i.e., he/she is likely to default, then approving the loan may lead to a financial loss for the company

The company wants to understand the driving factors (or driver variables) behind loan default, i.e., the variables which are strong indicators of default. 

## Conclusions
Top drivers of default: 

- `grade` - Higher grade leads to higher interest rates & higher loan amounts which increases the probability of a default. 
- `term` -  Borrowers with `60 month` term defaulted more compared to `36 months`
- `int_rate` - Defaulters were paying a slightly higher interest rate on their loan
- `loan_amnt` - Defaulters had a higher median loan amount compared to others.
- `annual_inc` - Borrowers with annual income between `37k` and `75k` are likely to default more on loan amounts 
- `purpose` - Borrowers who mention their purpose as `small_business`, `debt_consolidation` and `credit_card` are likely to default more compared to others.
- `Borrower's state` - Borrowers from `CA`, `FL` and `NY` are more likely to default compared to other status.
- `verification_status` - Borrowers from `CA`, `FL`, `NY` are less likely to be verified as well. 

## Libraries Used
- Numpy - `1.24.3`
- Pandas - `1.5.3`
- Matplotlib - `3.7.1`
- Seaborn - `0.12.2`

## Contact
- [Sudarshan Govindaraghan](mailto:sudarshan_g@outlook.com)
- [Alpesh Kumar](mailto:alpeshkumar0695@gmail.com)

5th July 2023
