# Credit Card Default Prediction
                  AlmaBetter Verified Project
![image](https://user-images.githubusercontent.com/104791753/218299557-dad55d80-7bf5-4c54-a920-bac84f9f8111.png)


I have built a Credit Card Default Prediction Model using classification algorithms in Python which can be deployed to minimize the risk of default and optimize credit management strategies for credit card companies by providing insights into customers' credit behavior.

## Description
This project is about Taiwan and aimed at predicting the case of customers default payments. The challenge is to develop a predictive model that can accurately predict the likelihood of a customer defaulting on their credit card payment. The model should take into account a range of factors such as the customer's age, income, spending habits, and payment history, among others, to make an informed prediction. 

The main motive behind the credit card prediction of Taiwan dataset is to help credit card companies better understand the risk profile of their customers. By analyzing the credit card behavior of their customers, the companies can make more informed decisions about granting credit, setting interest rates, and managing their portfolios. The goal is to minimize the risk of default and optimize their credit management strategies.

## Data Fields

**ID:** ID of each client

**LIMIT_BAL:** Amount of given credit in NT dollars (includes individual and family/supplementary credit

**SEX:** Gender (1=male, 2=female)

**EDUCATION:** (1=graduate school, 2=university, 3=high school, 4=others, 5=unknown, 6=unknown)

**MARRIAGE:** Marital status (1=married, 2=single, 3=others)

**AGE:** Age in years

**PAY_0:** Repayment status in September, 2005 (-1=pay duly, 1=payment delay 
for one month, 2=payment delay for two months,8=payment delay for eight months, 9=payment delay for nine months and above)

**PAY_2:** Repayment status in August, 2005 (scale same as above)

**PAY_3:** Repayment status in July, 2005 (scale same as above)

**PAY_4**: Repayment status in June, 2005 (scale same as above)

**PAY_5:** Repayment status in May, 2005 (scale same as above)

**PAY_6:** Repayment status in April, 2005 (scale same as above)

**BILL_AMT1:** Amount of bill statement in September, 2005 (NT dollar)

**BILL_AMT2:** Amount of bill statement in August, 2005 (NT dollar)

**BILL_AMT3:** Amount of bill statement in July, 2005 (NT dollar)

**BILL_AMT4:** Amount of bill statement in June, 2005 (NT dollar)

**BILL_AMT5:** Amount of bill statement in May, 2005 (NT dollar)

**BILL_AMT6:** Amount of bill statement in April, 2005 (NT dollar)

**PAY_AMT1:** Amount of previous payment in September, 2005 (NT dollar)

**PAY_AMT2:** Amount of previous payment in August, 2005 (NT dollar)

**PAY_AMT3:** Amount of previous payment in July, 2005 (NT dollar)

**PAY_AMT4:** Amount of previous payment in June, 2005 (NT dollar)

**PAY_AMT5:** Amount of previous payment in May, 2005 (NT dollar)

**PAY_AMT6:** Amount of previous payment in April, 2005 (NT dollar)

**default.payment.next.month:** Default payment (1=yes, 0=no)

## Approach

* Importing Libraries And Loading The Datasets
* Overview Of The Dataset 
    *   Reading & Inspection Of Dataset
    *   Further analysing the dataset
* Data pre-Processing
    *   Null Value Treatment
    *   Renaming Columns
    *   Data Cleaning
    *   Handling Outliers
* Exploratory Data Analysis
* Key Findings From EDA
* Feature Engineering 
    *   Treating Multicollinearity
    *   One Hot Encoding
    *   Handling Data Imbalance
    *   Scaling Numberical Features
* ML Model
    *   Train-Test Split
    *   Model Training And Prediction
  		* Logistic Regression
  		* Support Vector Classifier
  		* Decision Tree Classifier
  		* Random Forest Classifier
  		* XGboost 
    *  Hyperparameter Tunning
  		* Logistic Regression
  		* Support Vector Classifier
  		* Decision Tree Classifier
  		* Random Forest Classifier
  		* XGboost 
	*  Plotting Classification Metrics Of The Models
	*  Feature Importance
  *  Performance Of Our Best Model
*  Conclusions From ML



## Dataset
Dataset can be downloaded from : https://docs.google.com/spreadsheets/d/1V3zmCj3y4ERxbR2wy8zh8rfKFx7AS8QW/edit?usp=share_link&ouid=100224134617693119071&rtpof=true&sd=true
