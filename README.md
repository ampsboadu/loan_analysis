# Exploration Report On Prospers Loans


## Dataset Description
The dataset consist of 113937 loans disbursed over 10years (2005 - 2014). It contains almost all details of the loan, characteristics of the borrowers and other related fields spread on 81 columns. The dataset is attached together with a description of the fields as well.

## Preliminary Wrangling
In respect to this analysis, not all the 81 columns, so the dataset was limited to 17 columns which are concentrated on characteristics of the loans and some borrower features. The column names were renamed for ease of access in the exploration.

Further wrangling was performed on the include, managing null values in some numeric columns (prosper ratings and debt to income ratio), filling loan purpose with proper description of reason for the loan, and dropping duplicate rows if they exist.

## Summary of Findings
The exploration was targeted towards discovering the relationship between some loan features against character of it's borrowers. Interestingly, features of the loan such as amount and the status were very correlated with APR and borrowers rate. Increase in borrowers APR and borrowers rate will have decrease in loan amount and most loan in chargedoff and defaulted status exhibit very high median APR and borrowers rate with most them falling above the median value. Also, both loans in defaulted and chargedoff status matched very high against completed loans where both APR and borrowers rate were high.

It was also discovered that loan amounts were always on the rise within the 2013 recording the highest loans in number and compilation of heaviest loans in amount.


## Key Insights for Presentation.
The presentation is cantered on the impact of borrowers annual percentage rate on loan status especially completed loans and chargedoff loans.

The initial chart is generally looked at the distribution of the loan status for understanding of the current state of the loans. The violin chart after that shows the impact of borrowers annual percentage rate on all the loan status. This chart clearly depicts the concentration of borrowers annual percentage rate along the individual loan status.

Finally, the limit the distribution to borrowers annual percentage rate performance within just completed and chargedoff loans.