# Lending Club Case Study
**## Loan Default and Non Defaulter Predictions

# Data Description
No of rows and Columns in the data (39717, 111)

Dropped all of the columns which has no values

Cleaned the data which had sum extra symbols in the data

# Univarite Analysis
Most of the loans are give for the term of 36 or 60 months

Loan Status

The loan_status is fully paid then its considered as Non Defaulter

Charged off tells that the loan is defaulted

While Current is the loan which is going on and hasn't defaulted any EMI

The data for top 10 employee Title the top most is US Army while 2nd is Bank of America

The data discrepancy in the data where the USAF and US air force should be in same category

We can see that the data shows that people with 10+ years of experience takes more loans than the people with Experience

9 years the data shows really weird results since there is no more difference between 9 and 10 year experience people

We can also see that the people within 1 year take lot of loans after people experience more than 10 years

# Bivariate Analysis
We can see that the data loan status has 3 categories and the current category doesn't seem to helpful in Prediction so we should remove it

The loans that are charged of are usually in the range of 5k to 16k and with some outliers

People tend to pay it more often  than charging it off the most of the data lies in 5k to 15k range where people tend to pay the loans fully**

The data shows that the loans Charged off are the loan which are higher than 11% and most of the charged off are because of higher interest Rates

We can see that the loans are charged of more often in 36 months period while previously we saw that because of

the interest rate the loan were charged off soo we can consider this assumption that the loan with less term and high interest rates are waived off usually

We can see in the data that there is more charged off if the employee is having experience more than 10 years also the employee

who seem to be having experience less than 1 year seem to take lot of loans and charge them off

# Multivariate analysis
Loan_amnt is highly correlated to installment
Collection_recovery fee is highly correlated to recovery

Last recorded interest is highly correlated to funded amount

We can see that the most of the distribution of the installment lies between 0 to 600 who have charged off there loans

While we can see that most of people fully paid there loans lies between 0 to 800

We can see that the most of the distribution of the installment lies between 0 to 600 who have charged off there loans

While we can see that most of people fully paid there loans lies between 0 to 800

People who are taking the loans for 60 terms have lower defaulter rate than who takes it for lower terms

The verification status shows that the most of people who are source verified tent default loans very less than

while when the source isn't verified the person tend to default the loan

If the person having the own house its seems very rare that he would default the loan and the rented houses tend to default the loans more often

when a person takes the loan for debt consolidation there is more risk the person will default the loans

Next Steps
Next Steps that can be done remove the redundant columns which are having high correlation value

Feature Engineer the data with new columns which will help get new information

Use different Classification Algorithms to predict the Non Defaulter and Defaulters and try to get new test data to test it on it

[ ]
↳ 1 cell hidden
**
