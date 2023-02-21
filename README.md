# Cognizant-AI-Virtual-Experience-Program Internship Overview
Built a Unified Modelling Language (UML) Diagram for business strategic planning.

Incorporated data exploration, data cleaning & data Merging (Data Wrangling).

Performed feature engineering & used k-fold cross validation.

Implemented data modelling by utilizing Random Forest Regressor model for prediction. Computed accuracy using mean absolute error (MAE).

Performed Feature importance to check relevant features in the dataset.

Made alluring & comprehensible presentations for the client.

## Dataset:
Worked on 3 datasets. 'Sales' Dataset consists of following details (7829 rows x 9 columns):

Looking at the output of the .info() method, I can intepret each column as follows:

transaction_id = this is a unique ID that is assigned to each transaction,
timestamp = this is the datetime at which the transaction was made,
product_id = this is an ID that is assigned to the product that was sold. Each product has a unique ID,
category = this is the category that the product is contained within
customer_type = this is the type of customer that made the transaction
unit_price = the price that 1 unit of this item sells for
quantity = the number of units sold for this product within this transaction
total = the total amount payable by the customer
payment_type = the payment method used by the customer
'Sensor_stock_levels' Dataset consists of following details (7829 rows x 9 columns):

id
timestamp
product_id
estimated_stock_pct
'Sensor_storage_temperature' Dataset consists of following details (7829 rows x 9 columns):

id
timestamp
temperature
## Data Cleaning
After collecting the data, I needed to clean it up so that it was usable for our model. I made the following changes and created the following variables:

Dropping unnecessary unnamed 0 column from dataset
The column named 'timestamp' appears to be categorical but it's a date column. So, I converted timestamp to datetime format. Created a 'hour' column for further analysis
Merged 3 datasets appropriately into 1 dataframe

## Code and Resources Used
Python Version: 3.7
Packages: pandas, numpy, sklearn, matplotlib

Cognizant_Forage website https://www.theforage.com/virtual-internships
And made many more changes which can be viewed in the pre-processed data csv
