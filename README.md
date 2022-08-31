# Alx-t-Project3

### Dataset
* This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

[Clik here to see column information](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0)
[Clik here to download dataset](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000)

from the 81 columns provided in the dataset, i choosed the data set i would focus on into a dataframe and this columns  includes;

* ListingKey: Unique key for each listing, same value as the 'key' used in the listing object in the API.
* Term: The length of the loan expressed in months.
* LoanStatus: The current status of the loan: Cancelled, Chargedoff, Completed, Current, Defaulted, FinalPaymentInProgress, PastDue. The PastDue status will be accompanied by a delinquency bucket.
* BorrowerAPR: The Borrower's Annual Percentage Rate (APR) for the loan.
* BorrowerRate: The Borrower's interest rate for this loan.
* ProsperRating(Alpha): The Prosper Rating assigned at the time the listing was created between AA - HR. Applicable for loans originated after July 2009.

* BorrowerState:The two letter abbreviation of the state of the address of the borrower at the time the Listing was created.
* Occupation: The Occupation selected by the Borrower at the time they created the listing.
* EmploymentStatus:The employment status of the borrower at the time they posted the listing.
* IsBorrowerHomeowner: A Borrower will be classified as a homowner if they have a mortgage on their credit profile or provide documentation confirming they are a homeowner.
* IncomeRange: The income range of the borrower at the time the listing was created.
* LoanOriginalAmount: The origination amount of the loan.
* LoanOriginationDate: The date the loan was originated.

### Exploratory data Analysis Findings.
* A larger percentage of them are employed, a good number of them are full time employees while the rest of them are either non-partime retired or not employed.
* Califonia CA seems to be leading the pack with more than 14000 borrowers.
* 36 Terms is clearly the most occuring followed by 60 and the least is 30 Term.
* Only 51.58% of the Borrowers are Home owners.
* LoanOriginalAmount is a multimodal  distribution and starts from 1000, with its highest peak at about 17,500.
* Current and Completed are the most dominant.  
* 10.2% of the entire loan has been charged off as bad debt.
* The distribution shows that BorrowerAPR from 2006 had 0.2% with a slight fall to 2007 and a gradual increase till 2011 which was the highest APR % rate about 0.25%. A steady fall occurred from 2012 to 2014.
* There is a negative correlation between the borrowerAPR and LoanOriginalAmount the  the range of borrowerAPR decrease with the increase of LoanOriginalAmount.
* Borrowers who are Retired & Not Employed, have taken loans of Lower Amounts when compared with other Employment categories.
* longer term(60 months) had higher borrowerAPR. which means the longer the term the individual collect the loan the more likely the BorrowerAPR increases.
