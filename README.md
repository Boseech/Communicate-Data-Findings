# Communicate-Data-Findings
In this project, I perform exploratory data analysis using Python then, create a presentation with explanatory plots that conveys my findings.

I based my work on the Loan Data from Prosper which contains variables on loans including loan amount, credit grade, employment status and the loan status.
## Dataset
The data consists of 113937 observations, 81 features. The attributes include  IncomeRange, IncomeVerifiable, LoanStatus, ProsperScore and others such as Investors.

## Summary of Findings
In the exploration, I found that employment and a income source determines determines whether or not a customer will get a loan. Most investors are more likely to finance a loan if a customer has a source of income and especially if the source of income is verifiable. 
I also found out that people with a higher prosper score are more likely to get financed by investors. People with a prosper score of 7.0 and are increasingly more likely to get financed by investors.
Customers with a prosper score of 4.0 owe the most loans and customers with a prosper score of between 4.0 and 8.0 are most likely to default. This group also has more loan amounts as compared to the other groups.

## Key Insights for Presentation
For the presentation, I focus on factors which affect the likelihood of a customer getting a loan. I start by plotting Income range against loan status in order to find out who has the most loans. I then plot the Prosper score against Loan status in order to find out which group has the most loans. 
I then plot two subplots of the Prosper Score against the number of investors in order to find out which prosper score attracts the most investors.
Finally, I plot a boxplot of Income Range, Investors and Verifiable Income in order to find out whether having a verifiable source of income also attracts more investors.
