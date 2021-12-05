# Cryptocurrencies
## Overview
- Looked at cryptocurrency data to gather information for Accountability Accounting who wants to get into the cryptocurrency market.
- Specifically looked at what cryptocurrencies are on the trading market and how they can be grouped.
- Used unsupervised learning and clustering algorithm to process data and show the results with data visualizations.

## Process
- First we preprocessed the cryptocurrency data using Pandas
- Then used Principal Component Analysis algorithm to create a more simplified DataFrame
- Then we found the K-mean by creating an elbow curve using hvplot and predicted clusters
- hvplot was then used to visualize the groups and a table and scatter plot were produced

## Results
- From the final scatter plot we can see that class 2 is an outlier in this dataset. 
- Hovering over each dot on the scatter plot will provide more information on the currencies.
