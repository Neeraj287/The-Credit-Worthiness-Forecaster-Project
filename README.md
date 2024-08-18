# The-Credit-Worthiness-Forecaster-Project
Introduction

In the financial industry, managing credit risk is critical to the sustainability and profitability of lending institutions. One of the most significant challenges faced by these institutions is the risk of loan defaults, where borrowers fail to meet their repayment obligations. Loan defaults can lead to substantial financial losses, not only for lenders but also for the broader economy, affecting credit availability and interest rates.
To address this challenge, predicting loan defaults before they occur has become a priority for financial institutions. By leveraging data-driven approaches and machine learning techniques, it is possible to assess the likelihood of default at the time of loan application, enabling lenders to make more informed decisions. This project aims to develop a predictive model that accurately identifies potential loan defaulters based on historical data and a range of borrower characteristics.

Aim : 
The goal of this project is to build a robust loan default prediction model that can help financial institutions minimize risks and optimize their loan portfolios. By analyzing factors such as credit history, income levels, loan amounts, and other relevant variables, the model seeks to provide early warnings and allow lenders to take appropriate actions to mitigate potential losses.

Problem Statement : 
Currently, lenders face challenges in effectively predicting which individuals are at higher risk of defaulting on their loans. Inaccurate predictions can lead to significant financial losses, either by extending credit to high-risk individuals or by denying credit to individuals who are actually creditworthy. The goal is to create a robust machine-learning model that can accurately predict the likelihood of an individual defaulting on a loan based on their historical loan repayment behavior and transactional activities.

Objective :
Use EDA to comprehend how loan and consumer characteristics affect the tendency of default.
Constraints : 
• When an individual requests for a loan, the organisation may make one of two decisions:
• Loan accepted: Three situations are outlined below in the event that the company authorises the loan:
• Fully paid: The loan (principal and interest rate) has been paid in full by the applicant.
• Current: The loan has not yet reached the end of its tenure; the applicant is currently paying the installments. There is no designation of "defaulted" for these candidates.
• Charged-off: The applicant has defaulted on the loan because they have not made the required monthly payments over an extended period of time. 
• Loan denied: The loan had been rejected by the company (because to the candidate does not meet their requirements, among other reasons). Because the loan was denied, the applicants' transaction history with the company is non existent, making this data unavailable to the company (and hence in this dataset) 
Columns:
1.	loan_amnt: The amount of money requested by the borrower.
2.	term: The loan's term length, typically in months (e.g., "36 months").
3.	int_rate: The interest rate on the loan.
4.	installment: The fixed monthly payment that the borrower has to make.
5.	grade: The loan's grade as assigned by LendingClub (e.g., A, B, C).
6.	sub_grade: The finer classification within each grade (e.g., B1, B2).
7.	emp_title: The job title of the borrower
8.	emp_length: The length of employment in years.
9.	home_ownership: The status of the borrower's home ownership (e.g., RENT, MORTGAGE).
10.	annual_inc: The annual income of the borrower.
11.	verification_status: Indicates whether the borrower's income was verified.
12.	issue_d: The date when the loan was issued.
13.	loan_status: The status of the loan (e.g., Fully Paid, Charged Off).
14.	purpose: The purpose of the loan (e.g., debt consolidation, home improvement).
15.	title: The title or description provided by the borrower for the loan.
16.	dti: Debt-to-income ratio of the borrower.
17.	earliest_cr_line: The date when the borrower's earliest reported credit line was opened.
18.	open_acc: The number of open credit lines in the borrower's credit file.
19.	pub_rec: Number of derogatory public records.
20.	revol_bal: The total credit revolving balance.
21.	revol_util: The revolving line utilization rate as a percentage.
22.	total_acc: The total number of credit lines currently in the borrower's credit file.
23.	initial_list_status: The initial listing status of the loan (e.g., "f", "w").
24.	application_type: Indicates whether the loan is an individual or joint application.
25.	mort_acc: The number of mortgage accounts.
26.	pub_rec_bankruptcies: The number of public record bankruptcies.
27.	address: The borrower's address.

Methodology and Techniques

Project Overview: 
EDA : Analysing and understanding the data is the task of the exploratory data analysis step. It involves comprehending the relationship between the features, spotting outliers, and visualising the data. 
Data cleaning : it is the process of dealing with missing numbers, removing outliers, and eliminating features that are not essential to our research. 
Categorical to Numerical: Using various encoding strategies, we transform categorical data into numerical ones. 
Feature engineering: we can enhance the performance of our model by generating new features from preexisting ones. 
Model Training: Training models with different techniques, including Random Forest Classifier (RFC), XGBoost, Logistic Regression, and Artificial Neural Networks (ANN). 
Front-end Development: We use Streamlit, a Python package for developing interactive web applications, to create a user-friendly front-end.
