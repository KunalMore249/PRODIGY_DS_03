# PRODIGY_DS_03

## Task 1 : Plot Barchart or Histogram to visualize continuous variable.

## Problem Statement:<br/>
Build a decision tree classifier to predict whether a coustomer will purchace a product or service based on their demographic and behavioral data.
## About the Dataset :

The Dataset we are going to use in this task is Bank Marketing Dataset which is taken from UCI Machine Learning Repository.The dataset here is the 10% sample of the Original Bank Marketing Dataset. The dataset contains 20 features and 1 label. The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.

## Features of the Dataset:

### Input variables:
   ## Bank client data:
   1.  age (numeric)
   2.  job : type of job (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self-employed','services','student','technician','unemployed','unknown')
   3.  marital : marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed)
   4.  education (categorical: 'basic.4y','basic.6y','basic.9y','high.school','illiterate','professional.course','university.degree','unknown')
   5.  default: has credit in default? (categorical: 'no','yes','unknown')
   6.  housing: has housing loan? (categorical: 'no','yes','unknown')
   7.  loan: has personal loan? (categorical: 'no','yes','unknown')
   ## Related with the last contact of the current campaign:
   1.  contact: contact communication type (categorical: 'cellular','telephone')
   2.  month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')
   3.  day_of_week: last contact day of the week (categorical: 'mon','tue','wed','thu','fri')
   4.  duration: last contact duration, in seconds (numeric). Important note:  this attribute highly affects the output target (e.g., if duration=0 then y='no'). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.
   ## Other attributes:
   1.  campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
   2.  pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)
   3.  previous: number of contacts performed before this campaign and for this client (numeric)
   4.  poutcome: outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success')
   ## Social and economic context attributes
   1.  emp.var.rate: employment variation rate - quarterly indicator (numeric)
   2.  cons.price.idx: consumer price index - monthly indicator (numeric)     
   3.  cons.conf.idx: consumer confidence index - monthly indicator (numeric)     
   4.  euribor3m: euribor 3 month rate - daily indicator (numeric)
   5.  nr.employed: number of employees - quarterly indicator (numeric)

   ## Output variable (desired target):
   1.  y - has the client subscribed a term deposit? (binary: 'yes','no')

The classification goal is to predict if the client will subscribe (yes/no) a term deposit (variable y).

## Conclusion:<br />

This data science project provides a comprehensive analysis of the Bank Marketing dataset, encompassing exploratory data analysis, feature engineering, and Decision Tree classification. Dive into visualizations, uncover trends, and evaluate model accuracy for valuable insights into customer purchases.
