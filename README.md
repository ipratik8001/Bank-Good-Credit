# Bank-Good-Credit
Problem Statement : Bank GoodCredit wants to predict cred score for current credit card customers. The cred score will denote a customer’s credit worthiness and help the bank in reducing credit default risk. 

Project Goal :

1. Data exploration insights – what did you find and what decision did you take?

2. Feature matrix - List of features selected with gain

3. Model evaluation - Gini and rank ordering


Bank Customer Credit Score Analysis
Objective & Background : Classify credit card customers as good / bad, based on information from internal and external sources.

Data provided Demographic: Base file of with credit card history details. Only one record for every customer.

Account: Contians data for various loans availed by the customer. Not related to credit card. Multiple records for every customer.

Enquiries: Enquired made by customers for different loan purposes. Multiple records for every customer.

Design Data to be downloaded using SQL queries. Required information to be extracted from Account and Enquiry files and converted to one-to-one files. The columns from the two files should be merged with Demographic file using Left Join with “customer no” as key column, to create a final file. The final file should contain all the records in demographic and additional columns/features from Account and Enquiry files will get added to Demographic file. There will be many customers in account and enquiry file who will get left out. this is fine as we anyway don’t know their good/bad label for training purpose.
