# Loan Data from Prosper
## by Quadri Naheem


## Dataset

The data consists of BorrowerRate and attributes of 113,937 Prosper loan borrowers. The attributes include EstimatedLoss, EmploymentStatus, IsBorrowerHomwowner, IncomeRange and others. 31,262 data points were removed from the analysis due to inconsistencies and to ensure adequate standardization.


## Summary of Findings

In the exploration, I found that there was a strong positive relationship between the borrowers rate and estimated loss, with addtional influence from employment status, IsBorrowerHomeowner and borrowers' income range. I also found out the influence of other categorical features on the borrowers rate such that  a borrower that has high income range, is a home owner and also employed is likely to receive lower interest rates compared to a borrower that is not a home owner or that is not employed, or that has low income range.
Outside of the main variables of interest, I also found out that most of the borrowers with income of $50,000 and above are homeowners, and that borrowers that are employed have more income range than does that are not employed.

## Key Insights for Presentation

For the presentation, I focus on just the influence of borrowers EstimatedLoss, EmploymentStatus, IsBorrowerHomeowner and IncomeRange on the BorrowerRate. I start by introducing the BorrowerRate variable, followed by the pattern in EstimatedLoss distribution, then plot the scatterplot of the two variables.
Afterwards, I introduce each of the categorical variables one by one. To start, I use the box plot of BorrowerRate across EmploymentStatus. The other two categorical variables, IsBorrowerHomeoner and IncomeRange, are covered afterwards, using box plots.



