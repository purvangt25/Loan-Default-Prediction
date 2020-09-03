# Loan-Default-Prediction

## Introduction:

Lending Club is an online crowdfunding platform for peer to peer lending, facilitating personal loans, business loans, and financing. Borrowers access loans through an online or mobile interface and investors provide capital in exchange for earning interest (peer-to-peer (P2P) lending). Being an online-only operation results in cheaper operating costs and overheads, thus this offers lenders higher returns compared to traditional bank products. Borrowers can borrow money at lower interest rates, even after accounting for platform and credit checking fees. Interest rates are set by lenders who compete for the lowest rate based on a reverse auction model or a fixed rate based on borrower's credit profile

## Goals:

To classify if the borrower will default the loan using borrower’s finance history. We would be given a set of predictor variables; we need to predict the target variable as 1 -> Defaulter or 0 -> Non-Defaulter.
We would be using various classification algorithms to identify defaulter’s so that lending club will decide if a person is fit for sanctioning a loan in future or not.

## Model Accuracies:


| Model               | Model	Accuracy|
| -------------       |-------------  | 
| XGBoost             | 79.06%        | 
| Random Forest       | 78.01%        | 
| Logistic Regression | 76.87%        | 
| Naïve Bayes         | 76.08%        | 


## Technologies:

Programming Language: Python

Libraries: Pandas, Scikit-learn, Matplotlib, Seaborn

Visualization: plotly


## Data Source:

https://www.lendingclub.com/info/download-data.action
 
