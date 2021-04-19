# Data Science Telco Customer Churn Analytic

* Perform data exploratory on the features in the data
* Perform data cleaning on the dataset 
* Construct a dashboard for reporting purpose 
* Develop a model to predict if an existing client will become churner, based on services signed up, account information and demographic information.

## Code and Resources Used

**Python Version:** 3.7 <br>
**Packages:** numpy, pandas, seaborn, matplotlib, sklearn <br>
**IDE:** Google Colab <br>
**Dashboard Software:** Google Data Studio <br>
**Dataset:** https://www.kaggle.com/blastchar/telco-customer-churn

## Data Gathering
The dataset used in this project can be downloaded from Kaggle (link as shown above). It is about telco customer churn, focusing on customer retention program to retain client based on behavior. This dataset consist of 7043 rows and 21 features. The information of the dataset includes: <br>
* Customers who left within last month
* Services that client has signed up
* Account information
* Demograhpic info 

## Data Cleaning
Based on the dataset, the data type of the feature TotalCharges is a string. It has to be changed to numeric before data exploratory and modeling are carried out. However, during the string to numeric conversion, there are 11 null values generated due unable to convert to numeric. Hence, the 11 null values are replaced with the mean value of TotalCharges. <br> There is no other missing values for the rest of the features.

## EDA
To understand the patterns and values of the data by using different types of visualizations <br>
* Distribution of the client based on gender, category (senior or non senior citizen), with partners and with dependets in are also singed with the telco.
* Tenure of client and churner
* Phone services signed up by the client and churner
* Contract term and payment method
* Monthly and total charges of client and churner

Example of the charts produced as follows: <br>

![](/images/client_vs_churner.png)

![](/images/dependent_client_vs_churner.png)

![](/images/services_client_vs_churner.png)

![](/images/payment_client_vs_churner.png)
