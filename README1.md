## Financial Distress Prediction 

### Problem statement
Credit scoring algorithms, which make a guess at the probability of default, are the method banks use to determine whether or not a loan should be granted. 
This project requires Learners to improve on the state of the art in credit scoring, by predicting the probability that somebody will experience financial distress in the next two years.


Contributors - [Sarika Nangare](https://github.com/saru712)

### Data Columns:
- **SeriousDlqin2yrs** :Person experienced 90 days past due delinquency or worse
- **RevolvingUtilizationOfUnsecuredLines** :Total balance on credit cards and personal lines of credit
- **age** :Age of borrower in years
- **NumberOfTime30-59DaysPastDueNotWorse** :Number of times borrower has been 30-59 days past due but no worse in the last 2 years
- **DebtRatio** :Monthly debt payments, alimony,living costs divided by monthy gross income
- **MonthlyIncome** :Monthly Income
- **NumberOfOpenCreditLinesAndLoans** :Number of Open loans (installment like car loan or mortgage) and Lines of credit
- **NumberOfTimes90DaysLate** :Number of times borrower has been 90 days or more past due
- **NumberRealEstateLoansOrLines** :Number of mortgage and real estate loans including home equity lines of credit
- **NumberOfTime60-89DaysPastDueNotWorse** :Number of times borrower has been 60-89 days past due but no worse in the last 2 years
- **NumberOfDependents** :Number of dependents in family excluding themselves

- Need to predict if somebody will experience financial distress in the next two years

## ML Algorithm: 
- Used RandomForestClassifier with Hyperparameter Tuning to obtain roc_auc_score 0.61




