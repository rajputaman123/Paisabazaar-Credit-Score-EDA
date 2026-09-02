# Paisabazaar-Credit-Score-EDA

## Colab Notebook Link
[Open in Google Colab](https://colab.research.google.com/drive/1XBSwDgB3TwaMr-9CpQ6YKpTXONjoNbjC?usp=sharing)

## About the Project
Paisabazaar helps customers find and apply for banking and credit products. This project explores
customer financial data (100,000 records, 12,500 unique customers tracked over 8 months) to understand
what factors influence a customer's Credit Score — Good, Standard, or Poor.

## Business Objective
To identify the strongest, most explainable predictors of creditworthiness — such as income, payment
behaviour, credit mix, and outstanding debt — so Paisabazaar can improve credit risk assessment and give
customers concrete advice on improving their score.

## Dataset
The dataset contains 28 columns covering demographic info (Age, Occupation), banking relationships
(Num_Bank_Accounts, Num_Credit_Card), loan behaviour (Delay_from_due_date, Num_of_Delayed_Payment), and
payment behaviour (Payment_Behaviour, Monthly_Balance), with Credit_Score as the target variable.

## What This Notebook Covers
- Data understanding and cleaning
- Hypothesis and statistical testing (Chi-square test)
- 15 visualizations with insights and business impact for each
- Key findings and business recommendations
- Final conclusion

## Key Findings
- Higher income and longer credit history are associated with better credit scores.
- Higher outstanding debt, more payment delays, and more credit cards/bank accounts are associated with
  worse credit scores.
- Credit_Mix and Payment_of_Min_Amount are the strongest behavioural predictors.
- Occupation has almost no effect on credit score.

## Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, SciPy

## How to Run
1. Open the notebook in Google Colab.
2. Upload `dataset.csv` to the Colab environment.
3. Run all cells (Runtime → Run all).

## Author
Aman Kumar
