# Prosper Loan Dataset Exploration
## by Baki Musa Oladayo


## Dataset

Prosper Loan dataset contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. The dataset can be found in the repository for R's ggplot2 library [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv.), with feature documentation available [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).


## Summary of Findings

In the exploration, I found that there was a strong relationship between the Borrowers APR and prospers score (risk score) of the listing, with modifying effects it was clearly shown that as ARP is decreasing as the prosper score increased. Higher Prosper Score leads to Lower ARP, the lower the APR the lower the risk. Exploring borrowers APR with other numeric variables shows that there was negative relationship between borrowers APR and loan original amount and available bank card credit, this shows that the higher the Borrowers APR the lower the loan original amount and the lower the availabel bank card credit. 

With exploration of borrowers APR against selected categorial variables i saw that borrowers APR decreases as the credit score increased, so people with a good credit score gets lower interest rate. People with other employment status have higher Borrowers APR when compared with both employed and retired, People who are employed gets lower intrest rate than retired. Borrowers APR decrease as the loan terms increases, borrowers with 60 month loan Term as chances of having low interest rate. I go further by exploring the effect of borrowers APR on loan status outcome, although relationship with loan status categories isn't that consistent but current status tend to have lower BorrowersAPR when compared to others.

Outside of the main variables of interest, I verified the relationship between prosper score (risk score) and credit score and Employment Status . For the dataset, it was revealed that as the Prosper score increases, credit score increased. People with a good credit score gets lower interest rate and has low risk of payback. Employed people have highest prosper score which show that they have low risk of payback. Also  i explore effect of Loan Term and Employment status on Original loan amount and i found out that People employed take loans of Higher Amounts when compared to people who are Retired or have other employment status.



## Key Insights for Presentation

For the presentation, I focus on just the factors that have effect on determining borrowers APR  and leave out most of the intermediate derivations. I started by introducing the borrowers APR variable, followed by the pattern in prosper score (risk score) distribution, then plot the transformed scatter plot.

Afterwards, I introduce each of the categorical variables one by one and some numerical variable. To start, I use the box plots of borrowers APR and prosper score across credit score. I'm only looking at the effect of credit score here since it's the closest factor that determine loan borowers APR. The other two categorical variables, loan term and employment status, are covered afterwards, using box plots. I later explore the effect of numerical variable on the determination of borrowers APR with heat map. Lastly, i looked at relationship between BorrowerRate against EmploymentStatu and credit score with use of pointplot. I've made sure to use different color palettes for each quality variable to make sure it is clear that they're different between plots.
