# (Dataset Exploration Title)
## by (your name here)


## Dataset

> This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. This dataset has plenty of both quantitative and qualitative datapoints on the specifications of the loan, and the attributes of the borrower.

## Summary of Findings

> Most loans in this dataset are in completed or current status, which I will look at as a positive outcome. There are, however, a lot of loans in Defaulted or Chargedoff status which is a negative outcome. 

>The majority of loanees have monthly income between 2 and 6 thousand dollars, while most of these loans have a monthly payment of less than 500 dollars. For a given payment amount, borrowers with more income generally had better loan statuses, but this is not a very strong correlation as I orginally expected it to be. 

>The vast majority of credit scores are between 600 and 800, which is standard. Credit Scores increase as the interest rate decreases. Credit scores on average are higher for Current and Completed Loan Statuses. This makes a lot of sense, because people with better credit score tend to pay their loans back and on time. 

>Most borrowers have had zero delinquencies over the past 7 year, but a minority of borrowers have had delinquencies and some have had a lot of them. Negative loan statuses are associated with higher average delinquencies over the past 7 years. 

>Most loans fall have interest rates between 10 and 30%. It looks like the interest rates in general are rather high, with an average rate around 20%! Completed and Current loan statuses have lower interest rates compared to chargedoff and defaulted. I have a feeling that the higher interest amount makes the loan harder to pay back which can result in a default or chargeoff.

>People who own homes seem to have better loan outcomes than those people who do not own homes. Homeowners are stronger borrowers than non homeowners this can be seen several times throughout this analysis, but look no further than the chart that shows that for a given monthly payment amount, they make more money than non-Homeowners do. 


## Key Insights for Presentation

> I really wanted to see the impact of Borrower Interest Rate on Loan Status so I created a new dataframe that had the exact same loan term, credit score, and listing category. I also narrowed down the monthly income so that all these loanees have incomes around the median of the entire dataset. In other words these loans in this dataset all have a very similar risk profile. Then I created a violin plot with Borrower Interest Rate on the Y axis and Loan status on the x axis. It is very clear now that higher interest rates make are correllated with worse loan outcomes simply because they are more expensive to pay back. I have always thought about this paradoxical relationship. On one hand, finanial institutions need to be compensated for greater risk that they take, but on the other hand this extra compensation creates more risk because the loan is harder to repay (more interest)! This is a huge economic and societal issue!!

>My second main insight was that Homeowners are stronger borrowers and financiall better of than non-homeowner are. This is evidenced by higher incomes, higher credit scores, and better loan outcomes. For a given monthly payment amount, they make more money than non-Homeowners do which enables them to pay back loans and have a better loan status on average. Even when homeowners did have a negative loan outcome(status) they had signicanlty higher monthly payments than non-homeowners. This tells me generally homeowners are better borrowers than non-homeowners and in cases where homeowners did face difficulty it was partly because of the higher monthly payment when compared to there counterparts who also faced difficulty and were paying much less per month. Additionally, for good loan outcomes homeowners had higher montly payments on average than non-homeowners. Homeowners are simply financially better off.  
