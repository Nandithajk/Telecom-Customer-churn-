# Telecom-Customer-churn-
## Telecom customer churn prediction- classification by machine learning algorithm
**Churn Prediction** is one of the most popular Big Data use cases in business. It consists of detecting customers who are likely to cancel subscription to a Service.

**Churn** is a problem for telecom companies because it is more expensive to acquire a new customer than to keep your existing one from leaving.

## Objective
To predict customer churn

Highlighting the main variables/factors influencing customer churn.

Use various ML algorithm to build predictive models, evaluate the accuracy and performance of these models.

Finding out the best model fot our business case and providing executive summary.

## Overview

The dataset comprises 7043 rows and 35 columns, containing various customer attributes and churn-related information.The dataset is taken from kaggle.

CustomerID: Unique identifier for each customer.

Count: Counter for each row.

Country: Country where the customer resides.

State: State where the customer resides.

City: City where the customer resides.

Zip_Code: Postal code of the customer's location.

Lat_long: Latitude and longitude coordinates of the customer's location.

Latitude: Latitude coordinate of the customer's location.

Longitude: Longitude coordinate of the customer's location.

Gender: Gender of the customer.

Senior_citizen: Indicator if the customer is a senior citizen (1) or not (0).

Partner: Whether the customer has a partner (Yes/No).

Dependents: Whether the customer has dependents (Yes/No).

Tenure_Months: Number of months the customer has been with the telecom company.

Phone_Service: Whether the customer has phone service (Yes/No).

Multiple_Lines: Whether the customer has multiple lines (Yes/No).

Internet_Service: Type of internet service subscribed by the customer.

Online_Security: Whether the customer has online security service (Yes/No).

Online_Backup: Whether the customer has online backup service (Yes/No).

Device_Protection: Whether the customer has device protection service (Yes/No).

Tech_Support: Whether the customer has technical support service (Yes/No).

Streaming_TV: Whether the customer has streaming TV service (Yes/No).

Streaming_Movies: Whether the customer has streaming movies service (Yes/No).

Contract: Type of contract subscribed by the customer (e.g., month-to-month, one year, two years).

Paperless_Billing: Whether the customer has opted for paperless billing (Yes/No).

Payment_Method: Payment method used by the customer.

Monthly_Charges: Monthly charges incurred by the customer.

Total_Charges: Total charges incurred by the customer.

Admin_Tickets: Number of administrative tickets raised by the customer.

Tech_tickets: Number of technical tickets raised by the customer.

Churn_Label: Label indicating churn status (Yes/No).

Churn: Indicator of churn (1 for churn, 0 for non-churn).

Churn_Score: Churn score assigned to the customer.

CLTV: Customer lifetime value.

Churn_Reason: Reason for churn (if applicable).


## Steps.

### 1.Importing necessary library:

pandas

matplotlib

seaborn

sklearn

imblearn

datetime

### 2.Loading the dataset

### 3.EDA

Data Cleaning

Checking and treating duplicates and null values

Data manipulation

### 4.Data Visualization

### 5.Model building

Splitting the dataframe

train.test split

scaling

model building

models:

logistic regresion

decision tree

random forest

### 6.Evaluation matrix

accuracy

precision

confusion matrix

classification report

roc

auc


Conclusion



