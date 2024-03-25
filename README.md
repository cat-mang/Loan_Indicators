# Loan_Indicators

Link to Data Set:
https://www.kaggle.com/datasets/bsugiarto9/loan-status-prediction-with-added-nans

Describe the available fields.

How many categorical fields? What do they represent?
1. Loan_ID
2. Gender (of applicant)
3. Married (Yes or No to indicate marital status)
4. Education (graduate or not graduate)
5. self_employed (yes or no)
6. Credit_History
7. Property_Area (Urban, Rural, or semiurban)
8. Loan_Status (Y or N)
 

How many quantitative? What do they represent?
1. Dependents (number of dependents- max value is 3+)
2. ApplicantIncome (monthly income in USD)
3. CoapplicantIncome (monthly income of co-applicant in USD)
4. LoanAmount (loan amount requested/applied for)
5. Loan_Amount_Term (number of months for loan)


Is there missing data or data that seems to be wrong somehow (e.g. age = -99)?
Several loans are missing critical information such as number of dependents, Gender, Education, and income stats.

Has the data already been summarized, or are the observations raw and unprocessed?
Raw and unprocessed

# Initial EDA 
Initial data exploration often sparks additional questions or potential insights that could be supported by continued exploration.

What types of questions does this dataset seem to support?

Be especially on the lookout for avenues of inquiry that produce a tangible value (the ability to make better targeted or informed decisions, or some other potential benefit to stakeholders).

1. What demographics are most/least likely to get approved for a loan?
2. Are rural or urban developments more likely to get approved for a loan?
3. What income level is needed to likely be approved for a loan and at what amount? Over how many years?

# Stakeholders
Imagine that this dataset was provided by some stakeholder.

What are the potential benefits to your proposed line of inquiry? It's ok if this adjusts as you become more acquainted with the data.

1. Community planners such as county managers or city council would be interested in this data to understand how loan predictors will impact their constituents and their city/county growth.