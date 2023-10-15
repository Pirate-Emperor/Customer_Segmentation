# Restaurant Customer Segmentation

## Dataset:
Use the _**orders.csv**_ file to get the customer data used in this project. The dataset is pretty much self-explanatory.

## Problem Statement:
Customer Segmentation is needed in order to use the clusters with most valuable customers to predict the seat/visitor forecasting to ensure adequate seat reservation and to gain financial boost to the restaurant.
The second objective is to provide recommendation to the restaurant to capture those cluster of customers whose recency is less and payout is high.

## Methodology:
Python is used to perform the analysis in this project. The complete Python code can be found in the Jupyter Notebook named **’Customer Segmentation - RFM’**. The outline of the steps followed in the analysis is as follows:
- Data exploration and Validation (Performing data integrity checks, identifying missing values etc.)
- Data Preprocessing (Handling missing values, standardization, checking for correlation, testing hypothesis)
- Pareto Analysis (To determine what percentage of the customer contribute to what percent of the revenue)
- Determining the Key Performance Indicators.
- Determining the number of clusters through Elbow Analysis.
- K-Means clustering for Customer Segmentation.
- PCA for better visualization.
- Aggregate information for each cluster.
