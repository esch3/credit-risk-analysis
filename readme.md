# Credit Risk Analysis
## by Tom Esch


## Dataset

> This dataset is from Prosper, a private lending company based in CA. There are 81 variables in the dataset, including 61 numeric, 17 categorical variables, and 3 boolean variables as well as 113937 unique observations. The data is readily usable. We look at variables that can affect credit risk, such as occupation, income, borrower APR, loan status, Prosper score, and others. 


## Summary of Findings

> 
    "Other" and "Professional" occupations have the greatest number of default loans.
    Borrowers with a ProsperScore of 4.0 are the most common borrowers to default. 
    Monthly income of default borrowers most fall mostly within the 1k-10k range, with the most common income around 5k per month.
    Homeowner status is almost equivalent in paid vs unpaid loan groups.
    The strongest correlation that exists is between BorrowerAPR and ProsperScore. 
    Occupation vs Loan Status is quite similar from those who pay their loans vs those who don't. 
    Most defaulted loans fall within the $25,000-$49,999 income range for borrowers.
    The APR with the most defaults is around 0.35. 
    For each category of employment type, the borrower's APR is higher in the group that defaults. 
    Self-employed has the lowest ProsperScore but least number of defaults. 
    Generally, as number of delinquent accounts increases, a borrower's APR also increases. 



## Key Insights for Presentation

> Some of the key insights include the fact that homeowner status does not affect whether or not a loan is repaid, which is suprising as a common bias exists that homeowners are more financially stable and thus would be assumed to be more likely to repay debt. Income ranges with most defaults are between $25,000 and $49,999, and the least amount of defaults fall within the less than $24,999 income range. However, the category earning between $50,000 and $74,999 has the greatest ratio of those who repay their loan with the category or those earning less than $24,999 have the smallest ratio of those repaying their loans. This tells us the former category may be the least risky to lend to, and the latter category the most risky. Occupations listed as "other" have almost 2.5x more defaults than the 2nd highest default occupation listed as "professional". This is a significant finding because if an occupation is listed as either of these two categories, it could raise a red flag that a borrower is risky. Also helpful to know that although self-employed's have the lowest PropserScore, they are also much less likely to default. 
