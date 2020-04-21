# Exploratory and explanatory analysis of the Prosper Loans dataset
### by Daniel Mirica


## Introduction and dataset details

The project consists of 2 files that address the exploratory and explanatory analysis parts for the Prosper Loans dataset and 1 file designed as a presentation of key insights. There are 113,937 entries in the dataset with 81 columns that describe various metrics ranging from risk and grade of a loan to information about the borrower (e.g. - state, income range, ocuppation). 
None of the data has been manipulated in any way.

Before starting to go through the analysis please have a look at the description of the variables we will be working with [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0):


## Summary of Findings

* Most of the loans have a Prosper Score (risk score) between 4 and 8. 
* The Prosper Score shows moderate to high negative corellation coefficients in relation to the EstimatedEffectiveYield, EstimatedLoss and BorrowerRate variables.
* The Prosper Score shows a weak negative corellation coefficient in relation to the EstimatedReturn variable.
* The distribution of the ProsperScore ratings is concentrated betweeen 5 and 8 for Completed loans and between 4 and 8 for Current and FinalPaymentInProgress ones and 3 to 7 for the more riskly loan statuses (like Past Due).
* The distribution of the `ProsperScore` ratings is concentrated betweeen 4 and 8 for the majority of the IncomeRange brackets.
* The majority of the loans are deemed either medium (4-7) or low risk (8-11) in terms of Prosper Score with no unusual patterns in distribution for any of the US states.




## Key Insights for Presentation (saved as `Prosper_Loan_Data_Explanatory.slides`)

* The corellation between Borrower Rate and Estimated Return variables is stronger for low risk loans (with a Prosper Score between 8 and 11). 
* As for the insights regarding Borrower Rate based on Income Range and Prosper Score, the distributions seem uneven between the income ranges labelled as Not employed and 0 and the ones labelled 1-24,999 and above.