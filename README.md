# Lending Case Study
> This case study tries to analyse the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.

# Project Name
> Solving this assignment will give you an idea about how real business problems are solved using EDA. In this case study, apart from applying the techniques you have learnt in EDA, you will also develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
- If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
- Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 
- The data set is from a lending company which has collected data over 3 years.


### Quantative Variables : loan_amnt, funded_amnt, installment,int_rate,emp_length,dti ,total_pymnt, annual_inc 
### Un Ordered Categorical Variable - term, loan_status, Purpose, grade, home ownership

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
### Outcomes of Univariate Analysis 
   - Most of the loans has been offered at interest from 12% to 15% 
   - 14.17% of total Loans are Charged Off
   - When the Loan Amount Increases then the Total Payment is decreased
   - There are quite considerable number of Loans which are Not Verified which requires Further analysis
   - dti ratio is acceptable , where the Debt to Income is not making big impact 
   - Employess with more exprience is taking more loans
   - home_ownership  with RENT and MORTGAGE were taking more loans
   - More loans were being taken for Debit Consolidation 
   - All the loans taken with either tenure of 36 or 60 months 
   - Tops Grades were taking more loans ( A, B C )
### Outcomes of Segmened Univariate Analysis
   - There is a increase in Number of loans each year  from Q1 to Q4.
### Outcomes of Bi Variate Analysis
   - When Loan Amount/interest rate/debt to income ration/employment Lenth increases then there is risk of getting defaulters 
   - Members with low Debt to Income Ratio and high annual income have less tendency to get charged off
   - Members with house ownership status as "Others" tend to default the rate by 18%.
   - Whereas, Members in category of Mortgage and own house has less tendendency  to be defaulters  compared to other categories.

 
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas
- Seaborn
- Matplotlib

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.

This is acheived in collaboration with Onkar Daeker <onkardarekar19@gmail.com>

## Contact
Created by [@pvoodhar] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
