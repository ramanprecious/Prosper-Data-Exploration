# [Prosper Loan](https://github.com/ramanprecious/Data-Analyst-Portfolio/blob/main/ProsperLoan/Part_I_exploration_template.ipynb)

A financial technology company is a place where you can borrow and lend money. Fintech companies are easing payment processes, reducing fraud, saving users money, promoting financial planning, and ultimately moving a massive industry forward. Prosper is one of the Fintech companies that have been making waves over the years.

In this project, I investigated the Prosper loan dataset provided by Prosper for insights and visualizations that would shed light on the progress of the company and their operations. 

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrowers' rate (or interest rate), current loan status, borrowers' income, and many others.

Data dictionary for better understanding of the variables is in this [link](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).

To ensure proper organization and apt focus, I only used few of the variables. The main features I focused on are:

- *BorrowerAPR*: The Borrower's Annual Percentage Rate (APR) for the loan.
- *Lender's Yield*: The Lender yield on the loan. Lender yield is equal to the interest rate on the loan less the servicing fee.
- *ListingCreationDate*: The date the listing was created.
- *LoanOriginationDate*: The date the loan was originated.
- *ClosedDate*: Closed date is applicable for Cancelled, Completed, Chargedoff and Defaulted loan statuses. 
- *CurrentStatus*: The current status of the loan: Cancelled,  Chargedoff, Completed, Current, Defaulted, FinalPaymentInProgress, PastDue. The PastDue status will be accompanied by a delinquency bucket.
- *LoanOriginalAmount*: The origination amount of the loan.

Other features explored include: Prosper rating, Borrowers' Rate, Term, Credit grade, Lender's Yield,  Debt-to-income ratio, Current delinquencies, Listing Category, Ocupation, Employment Status, Loan origination quarter, and Credit score

##### Some of the insights from the data include:

1. A larger percentage of the loans are either completed or currently running with the other features including charged off, defaulted, cancelled etc. having a smaller percentage.

2. Clients seem to flux in towards the end of the month. This could be due to the companies attempt to meet their performance goals. January being a best selling month might be a result of people renewing their resolutions and making their financial goals.

3. The clients seem not to trust the company by withholding their personal information like listing purpose, and giving wrong income range information. The company should look into improving their services to gain their clients' trust.

4. California has the highest number of borrowers. This is largely because the headquarter of prosper is located in San Francisco, California. It is however good to see that the company is extending their tentacles into other states. There is a possibility that they would dominate in years to come.

5. Borrowers with lower credit score are small in number, and same goes for those with high scores. This could be because people with high credit scores are financially stable and don't need loans, while people with low credit scores most times do nnot get approvals for loans. This can also be observed in Credit grade and Prosper ratings.

6. The growth of the prosper company is evident as most of the loans seem to still be ongoing. Another observation is that most of the borrowers take loan for debt consolidation.

##### The Key Insights are:

> There was a dip in 2009 that indicates a 'pause period' where the company rebranded itself and raised the bar of crediting goals and visions.

> The number of defaulted loans pre-revolution of the company is higher than that of  post-revolution. This shows that the decision to revolutionize the company was a success. 

> High risk loans have a higher lender yield. This is profitable for lenders, as borrowers with poor credit rating will have higher APR which returns higher yields. Also, there are many defaulted loans in the high risk category, thereby proving that the prosper rating system for loan approval is somewhat accurate.

The html file containing the slidedeck for this project is found [here](https://github.com/ramanprecious/Data-Analyst-Portfolio/blob/main/ProsperLoan/Part_II_slide_deck_template.slides.html)




