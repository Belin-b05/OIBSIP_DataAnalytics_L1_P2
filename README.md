CUSTOMER SEGMENTATION ANALYSIS

Overview

This project analyzes a customer segmentation dataset to gain insights into customer demographics, purchasing behavior, and clustering patterns. The dataset contains information such as customer attributes, product purchases, promotional campaign responses, and online/offline purchase behaviors.

Data Exploration

People Attributes

Age: Customer's age

Customer_Days: Number of days the customer has been associated

Income: Customer's yearly household income

Recency: Number of days since the customer's last purchase

Complain: 1 if the customer complained in the last 2 years, 0 otherwise

Total Children

Kidhome: Number of children in the customer's household

Teenhome: Number of teenagers in the customer's household

Marital Status

marital_Divorced: Indicates whether the individual is divorced (1) or not (0).

marital_Married: Indicates whether the individual is married (1) or not (0).

marital_Single: Indicates whether the individual is single (1) or not (0).

marital_Together: Indicates whether the individual is in a relationship (1) or not (0).

marital_Widow: Indicates whether the individual is a widow/widower (1) or not (0).

Education

education_2n Cycle: Indicates whether the individual has an education level of '2n Cycle' (1) or not (0).

education_Basic: Indicates whether the individual has an education level of 'Basic' (1) or not (0).

education_Graduation: Indicates whether the individual has an education level of 'Graduation' (1) or not (0).

education_Master: Indicates whether the individual has an education level of 'Master' (1) or not (0).

education_PhD: Indicates whether the individual has an education level of 'PhD' (1) or not (0).

Products

MntWines: Amount spent on wine in the last 2 years

MntFruits: Amount spent on fruits in the last 2 years

MntMeatProducts: Amount spent on meat in the last 2 years

MntFishProducts: Amount spent on fish in the last 2 years

MntSweetProducts: Amount spent on sweets in the last 2 years

MntGoldProds: Amount spent on gold in the last 2 years

MntRegularProds: Amount spent on regular products

MntTotal: Total amount spent by the customer

Promotion

AcceptedCmp1: 1 if the customer accepted the offer in the 1st campaign, 0 otherwise

AcceptedCmp2: 1 if the customer accepted the offer in the 2nd campaign, 0 otherwise

AcceptedCmp3: 1 if the customer accepted the offer in the 3rd campaign, 0 otherwise

AcceptedCmp4: 1 if the customer accepted the offer in the 4th campaign, 0 otherwise

AcceptedCmp5: 1 if the customer accepted the offer in the 5th campaign, 0 otherwise

Response: 1 if the customer accepted the offer in the last campaign, 0 otherwise

AcceptedCmpOverall: Overall acceptance of marketing campaigns

Place

NumDealsPurchases: Number of purchases made with a discount

NumWebPurchases: Number of purchases made through the company’s website

NumCatalogPurchases: Number of purchases made using a catalog

NumStorePurchases: Number of purchases made directly in stores

NumWebVisitsMonth: Number of visits to the company’s website in the last month

Exploratory Data Analysis (EDA)

Analyzed customer's income distribution and found that the majority fall within the 0-100k$ range.

Discovered a decline in the average amount spent as the total number of children increases.

Identified that customers with graduate education level and above tend to spend more.

Explored the distribution of marital status and found that close to the highest proportion (39%) of customers are married.

Building the KMeans Model

Used the Elbow Method to determine the optimal number of clusters (3 clusters).

Applied KMeans clustering to segment customers based on their income, total amount spent, and age.

Visualized the clusters in a 3D scatter plot, showing distinct clusters based on spending behavior and age demographics.

Interpretation of Results

Cluster 1: Young customers with high income and high spending habits.

Cluster 2: Older customers with high income and high spending habits.

Cluster 3: Young customers with low income and low spending habits.

