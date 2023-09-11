# Lending Club Case Study
- You work for a consumer finance company which specialises in lending various types of loans to urban customers
- Goal is to understand how consumer attributes and loan attributes influence the tendency of default and understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile.
- The data given below contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.
- In this case study, it is required to understand how consumer attributes and loan attributes influence the tendency of default
- The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment.
- Dataset used - 'loan.csv' 
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- pandas - 1.5.3
- matplotlib - 3.7.1
- datetime
- re (regex) - 2022.7.9
- seaborn - 0.12.2

## Conclusions
- About 86% of the members are non-defaulters i.e. either have fully paid off the load or are in paying in time. Remaining 14% of the members have defaulted
- About 50% of the defaulters stay in a rented house - from this one can infer that they are either bachelors or have low income if they have family staying with them. 41 % of them have mortage and only 8% have their own houses
- Defaults seem to occur where either income is verified by LC or not - this would also mean since their income source is not verified, the source of income is not stable enough to repay the loan. Defaults occur lesser where the income source is verified
- Generally, the defaults tend to decrease gradually as the members spend more time in the company(s). However there is a shoot up in defaults when employement length is 10 years and more. This might be due to the fact that the job is low paying and applied loan is higher and the interest rate goes on increasing and/or they are not getting promoted and expenses are rising
- About 57% of the defaulters chose to go fo 3 years term for the loan assignment
- With both 3 and 5 years term plan, most of the defaults happen for annual income up to 1 Lakh per annum
- 50% of the defaulters have debt to be consolidated - this is clearly explainable by low income and higher loan requirements
- Most of the defaulters have DTI of about 14 which means monthly debt are 14 times more than total debt obligations! This again is supported by the fact that 50% of the defaulters are consolidating debts - see purpose section
- Almost 20% of the defaulters stay in California. Standard of living in CA is definitely higher as compared to other states! High standard of living --> higher debt consolidation --> lower income --> Defaults!!
- On an average, defaulters have to pay loan with an interest rate of 14% p.a which is high considering lower income of the defaulters!
- For a 3 year term, most of the defaulters have a loan of Rs. 6000 with interest rate of 14%. For a 5 year term, the loan doubles i.e. becomes Rs. 12000 with interest rate of 14%. The variation/expanse of applied loan is more for a 5 year term with 1st quartile raised by almost Rs. 4000
- It can be clearly seen that the defaulters have not paid any loan installment lately. Larger difference in the last payment date and issue date indicates that more number of loan installments have been paid off by the fully paid cases. Lesser difference for the defaulters clearly indicate less number of installments paid till date!. Assuming last payment date as the loan repayment completion for fully paid cases. For the 3 years term, defaulters have not paid off the installments since last 2 years!!. Similarly for 5 years term, defaulters have not paid off the installments since last 3-3.5 years!!
- For a 3 years term, most of the defaulters still have the revolving balance of around Rs. 5600 which is pretty close to the loan amount itself (Rs. 6000). For a 5 years term, most of the defaulters still have the revolving balance of around Rs. 7800 which is pretty close to the loan amount itself (Rs. 12000)
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- References
  - https://matplotlib.org/stable/index.html
  - https://pandas.pydata.org/docs/index.html
  
## Contact
Created by [@rk1989] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
