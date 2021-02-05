# LEND SMART : A Loan Status Predictor
#### OBJECTIVE:
To build a web application which would predict the status of the loan taken by the borrower, i.e., whether the loan is
1. fully repaid,
2. up to date on all outstanding payments,
3. delinquent (late or overdue), or
4. in default status.	

#### DATA DESCRIPTION:
The source of the loan data used for analysis, is the American lending company, LendingClub. It is a collection of about 10,48,563 records of the loans borrowed from the LendingClub company during the years 2007 to 2018.
The dataset contains 147 variables or features, of which 113 are numerical and 34 are categorical. These features were used to predict the target variable, viz., ‘loan_status’, which has the following categories:
1. Fully paid
2. Current
3. Late
4. Default

A Random Forest Classifier was built to achieve this. The Python web framework, Flask, was used to develop the user interface.
