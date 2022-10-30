# (Prosper Loan Data Exploration)
## by (Akpan Enwongo Boniface)


## Dataset

The dataset which contains contains 113,937 loans with 81 variables may be obtained from https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv. The variables are information on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

The variable definitions may be obtained from https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0.

## Summary of Findings

From the visualizations, it was obeserved that most loans are in the current state and there are more completed loans compared to the ones in the delinquency bucket (past due date). California was the state with the highest number of borrowers. The salary range bewteen $25,000 to $49,999 and most loans were acquired for debt consolidation. Most borrowers acquire loans within the range of \\$1,000 to \\$16,000.

My main features of interest were the Loanstatus, LoanOriginalAmount, Incomerange and LoanCurrentDaysDelinquent. The features to support my investigation into those key features were Term, LenderYeild, Prosperrating and Loan Month since Origination.

There was a postive correlation between the LoanCurrentDaysDelinquent and LoanMonthsSinceOrigination. The 36-month term is the most common term. There was no correlation between LoanCurrentDaysDelinquent and LoanOriginalAmount.

The Borrower APR is positively correlated with the LenderYield. The loan original amount is negatively correlated with ProsperRating and positively correlated with the Income Range.



## Key Insights for Presentation


For the presentation, I will focus on the influence of Term, EmploymentStatus and Prosper Rating on the Loan Status. I want to assess the variables that may affect the loan status and may be used to identify trends in delinquency. Loan Status will be re-grouped into Charged off, Delinquent Payments and Non Delinquent Payments and the categories in the Employment Status will be reduced to Employed,Full-time       
Not employed, Self-employed, Part-time and Retired.

The data points were reduced to 110809 due to inconsistencies.

I will start by showing the Loan Status variable, then proceeding to show the relationship between Loan Status and Term, then Loan Status and EmploymentStatus,  EmploymentStatus and Term and then show the relationship between all three variables.

The mentioned variables are qualitative, hence, the clustered bar chart and faceting will be used for visualization.

