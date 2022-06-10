# Prosper Loan Dataset Exploration
## by Oreva Egwebe


## Dataset

> The data consists of 81 columns and 113,937 observations regarding loans given by Prosper. Some of the variables iclude: loan amount, borrower rate, monthly income, employment status and credit grade. I created a dataframe of about 20 columns from the dataset to help me focus on the variables of interest for this exploration that is loan amount and borrower rate. The dataset can be found [here]('https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv') and the data dictionary can be found [here]('https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/')



## Summary of Findings

> In the exploration, I found out that loan amount and monthly income have a positive linear relationship though monthly income has no relationship with borrower rate. Borrower rates across the years showed a consistent rise up till 2011 then started to decline.
Prosper score, credit grade and prosper rating have a huge effect on borrower rates even though there were some outliers.
Employment status and being a home owner are also major factors that affect loan outcome and interest rates. A borrower that is fully employed and owns a home tends to have a lower interest rate and higher loan amount compared to a borrower who is unemployed and not a home owner. The distribution of loan amouunt and employment status by loan amount showed $4000, $10000 and $15000 as the popular loan amounts taken. The correlation coefficient of borrower rate and loan original amount is a negative correlation. There is a weak correlation between stated monthly income and borrower rate, also with loan original amount.



> Outside of the main variable of interest, I verified that credit grade, prosper score and proper rating are influenced by monthly income but these ratings do not affect the loan amount. The listing category for the highest number of loans taken was shown to be debt consolidation. Home owners were shown to have a higher loan amount for all listing categories except for buying a boat.



## Key Insights for Presentation

> For the presentation, I introduced the distribution of loan amount. This is followed by a plot showing the relationship between borrower rate, credit grade and prosper rating. I show a correlation plot of the numeric variables; monthly income, loan amount and borrower rate. Then I introduce other variables to clearly show the factors that influence loan amount and categorical variables most using point plots. I've made sure to use different color palettes for each categorical variable to make them easily distinguishable.

