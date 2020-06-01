# Prosper Company Loand Data Analysis
## by Furkan Küçük

## Investigation Overview
In this work, I tried to discover the correlations between Prosper Rating and other factors like income level, credibility, house ownership. I also tried to discover customer behaviors with loan status.

## Dataset
Dataset is provided by Prosper and can be found at: https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv.

Variable explainations can be found at: https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0.

Preliminary exploration shows that:

- Data contains 113937 samples with 81 columns. (76216 entries and 69 columns after cleaning)
- The data we want to invesitage is:
  - Loan status
  - Prosper Rating
  - Borrower APR
- Features mentioned above may be correlated, or being constructed by other features which may be:
  - Income Range
  - Verifiable Income
  - Ownership of house
  - Employment status
  
## Summary of Findings
- Company has a succesful rating system
- People tend to make the payments on time. If they miss it, a large proportion of customers pays within 15 days.
- Rating system considers number of things like being a house owner or income.
- Company tries to create a Gaussian distribution when scoring their customers, similar to an exam scoring of a lecture. This is a valid approach as it models lots of things well.
- Ownership of house is not the best indicator for on-time payments.

