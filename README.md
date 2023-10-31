# retail_prediction

In this time series forecasting problem, you are required to predict the future number of sales of each product expected on a specific day. The attached data is the transactional dataset which contains all the transactions between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. 

Data Dictionary
Feature/Attribute	Data Type	Description
InvoiceNo 	Nominal	 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
CustomerID	Nominal	5-digit integral number uniquely assigned to each customer.
Country	Nominal	The name of the country where each customer resides.
StockCode/Product (item) code	Nominal	5-digit integral number uniquely assigned to each distinct product.
Product (item) name. 	Nominal	Name of the product
Quantity	Numeric	The quantities of each product (item) per transaction. 
InvoiceDate	Date time	The day and time when each transaction was generated.

UnitPrice	Numeric	Product price per unit in sterling.


Please make sure to follow the following process while solving this problem: 
1.	Exploratory Data Analysis: Module would be responsible for plotting the raw data to check for data distribution, missing values etc.
2.	Data Preprocessing: Module would be primarily addressing pre-processing the raw data. It may include imputing missing values along with other necessary tasks.
3.	Feature Engineering: Module would be primarily responsible to extract new features, or you might need to drop some of the existing features.
4.	Model Building: This module would involve creating a machine learning model that solves sales forecasting problems. Feel free to use any Machine Learning (ML) or Statistics model, which fits the data distributions.
5.	Evaluation: Once you are done with the model building part. Make sure to evaluate the model using the appropriate evaluation metrics. Primarily, you would be splitting the dataset into two parts i.e., training and testing dataset. Training set would be used by the model to learn the required data relationships and test data would be used to evaluate the performance of the model.

If you don’t have the computing power to train the model on all the products, you can sample the dataset.
Submission Deliverables
●	Source Code
●	Trained ML Model (pickle file).
●	Test Dataset (sample output in the following section “Sample Output”) file.
●	1-2 Page report on the process you have followed. This may include the model type (neural network, ARIMA etc.) you have used, preprocessing steps to clean the data, and the feature engineering approach you have taken along with the other approach.
