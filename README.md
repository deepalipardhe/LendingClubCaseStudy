# Lending Club Case Study

Lending loans to risky applicants is the largest source of credit loss.
The credit loss is the amount of money lost by the lender 
when the borrower refuses to pay or runs away with the money owed.  

The main objective is to identify these risky loan applicants, 
then such loans can be reduced thereby cutting down the amount of credit loss. 
Identification of such applicants using EDA is the aim of this case study.   

Perform an analysis to understand the driving factors behind loan default, i.e.the variables which are strong indicators of default.  
The company can utilise this knowledge for its portfolio and risk assessment.

### Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

  ## General Information
- A consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.

- The data given below contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

- Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 
- Business probem: Understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 
- Dataset used: loan.csv (Previous year loan data)

## Technologies Used
- Python - version 3.12.4
- Matplotlib - version 3.8.4
- Seaborn - version 0.13.2
- Numpy - version 1.26.4
- Pandas - version 2.2.2

## Conclusions
- Risk Assessment for Grades B, C, and D: Since loan applicants from Grades B, C, and D contribute to most of the "Charged Off" loans.

- Pay special attention to applicants with Subgrades B3, B4, and B5, as they are more likely to charge off. Implementing additional risk mitigation measures or offering them lower loan amounts could be considered.

- Term Length: Given that applicants opting for 60-month loans are more likely to default, the company should consider evaluating the risk associated with longer-term loans and potentially limiting the maximum term or adjusting interest rates accordingly.

- Employment Length: Loan applicants with 10+ years of experience are more likely to default. This suggests that experience alone may not be a reliable indicator of credit worthiness. The company should use a more comprehensive credit scoring system that factors in other risk-related attributes.

- There is steady increase in the number of loan applicants from 2007 to 2011 indicates growth in the market. The company can capitalize on this trend by maintaining a competitive edge in the industry while keeping risk management practices robust.

- December and Q4 are peak periods for loan applications, likely due to the holiday season. The company should anticipate increased demand during these periods and ensure efficient processing to meet customer needs.

- Debt Consolidation is the category with the maximum number of loans and high default rates, the company should carefully evaluate applicants seeking debt consolidation loans and potentially adjust interest rates or offer financial counselling services.

- Applicants living in rented or mortgaged houses are more likely to default. This information can be considered in the underwriting process to assess housing stability and its impact on repayment ability.

- Verified loan applicants are defaulting more than those who are not verified. The company should review its verification process to ensure it effectively assesses applicant creditworthiness and consider improvements or adjustments.

- Applicants receiving loan amounts of $15K or higher are more likely to default. The company can mitigate this risk by conducting more thorough assessments for larger loan requests and potentially capping loan amounts for higher-risk applicants.

- High Debt-to-Income (DTI) ratios and interest rates in the 13%-17% range are associated with defaults. The company should review its interest rate determination process and consider adjusting rates based on DTI ratios to better align with the borrower's ability to repay.

- Applicants with annual income of range 31201 - 58402 have a higher likelihood of defaulting. The company should consider offering financial education resources or setting maximum loan amounts based on income levels to ensure affordability for borrowers.

## Acknowledgements
Give credit here.
- This project was inspired by live session of upGrad on EDA by Akash Garg
- UpGrad tutorials on Exploratory Data Analysis (EDA) on the learning platform

## Contact
Created by Deepali Pardhe

