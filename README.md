Online-Shopping-Analysis

Growth of online shopping brings possibilities for research and study. We can use online price data for forming consumer price index. In today's era customers are preferring to shop products from a single store where they get variety of items. As per demand of items from customers, seller could place the items together with offers which can be sold in huge amount and according to sale, seller could also offer discount on the basis of holidays and weekdays. 
This project proposes online price prediction system that use online price commodities from online retailers as data source. To collect many products information as consumption commodities of transnational countries, we use online data of different countries. Collecting consumption commodities from online stores is possible and well proven.
We are processing ETL operation on top of that data using Apache Spark and dumping required data into MongoDB for data visualization through Power BI and build Machine Learning to predict total sales of the products of different countries. Precise estimation of total sales of transnational countries from which inventory of the business can be managed in better way and the chances of sell increases. 

1.	INTRODUCTION 

Every shopping centre is trying to provide personalized and short-time oﬀers for attracting more customers depending upon the day, such that the volume of sales for each item can be predicted for inventory management of the organization, logistics and transport service, etc. Present machine learning algorithm are very sophisticated and provide techniques to predict or forecast the future demand of sales for an organization, which also helps in overcoming the cheap availability of computing and storage systems. 
In this project, we are focusing on online shopping sales prediction or forecasting of an item on customer’s future demand in diﬀerent shopping stores across various locations and products based on the previous record. Diﬀerent machine learning algorithms like linear regression analysis, random forest, etc. are used for prediction or forecasting of sales volume. As good sales are the life of every organization so the forecasting of sales plays an important role in any shopping complex. Always a better prediction is helpful, to develop as well as to enhance the strategies of business about the marketplace which is also helpful.

Problem Statement:

Predicting sales is one of the most important business problems for any retail entity. If a business can predict the how much of each item it will sell in each month, it can manage its inventory better. Sales predictions also help in directing the marketing efforts in right direction to increase the chances of sale.

Client:

The client in this case is a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.
This model can be replicated to any similar online or physical store selling any kind of product.
 

Datasets and Model: 

Two Datasets were used in the project are structured in nature from year Dec 2010 to Dec 2011. Online retail dataset is collected from https://archive.ics.uci.edu/ml/datasets/Online%20Retail. 
Public Holiday dataset is collected from https://www.worldpop.org/doi/10.5258/SOTON/WP00689. Linear regression with model selection, ridge, lasso, bagging with linear regression and clustering on RFM models were used to predict total sales. 



Features of Online Retail Dataset:

Invoice No: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
Stock Code: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
Description: Product (item) name. Nominal.
Quantity: The quantities of each product (item) per transaction. Numeric.
Invoice Date: Invoice Date and time. Numeric, the day and time when each transaction was generated.
Unit Price: Unit price. Numeric, Product price per unit in sterling.
Customer ID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
Country: Country name. Nominal, the name of the country where each customer resides.


Features of Public Holiday Dataset:


ADM Name: Country name. Nominal, the name of the country.
ISO: Abbreviation used for country names. 
Date: Holiday date.
Name: Name of the Holiday.
Type: Type of the Holiday.

CONCLUSION AND FUTURE SCOPE 
 
In this project, we have designed a predictive model by modifying bagging regressor with linear regression and performed it on the 2010-11 online retail dataset for predicting sales of the product from different transnational countries. Bagging regressor with linear regression model produce more accurate prediction compared to other available techniques like linear regression, lasso regression, ridge regression etc. Finally, a comparison of diﬀerent models is summarized in Table 1. It is also concluded that our model with highest R2_score performs better compared to existing models.



Future Scope

1. Predict customer churn and suggest ways to prevent the churn
2. Customer segmentation and buying behavior analysis
