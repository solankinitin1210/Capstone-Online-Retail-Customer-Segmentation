# Capstone-Online-Retail-Customer-Segmentation
## Problem Statement
In this project, your task is to identify major customer segments on a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.
## Data Description
Attribute Information:
- InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
- StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
- Description: Product (item) name. Nominal.
- Quantity: The quantities of each product (item) per transaction. Numeric.
- InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.
- UnitPrice: Unit price. Numeric, Product price per unit in sterling.
- CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
- Country: Country name. Nominal, the name of the country where each customer resides
## Conclusion
- Built a clustering model using K-means and hierarchical clustering to identify major customer segments on transaction data to optimize the impact of marketing
- Engineered features to obtain new features such as RFM, and RFM-Score for getting more details about the customers' purchasing behavior.
- Evaluated the optimal clusters using the silhouette score , elbow method and dendrograms Method also plotted the scatter plot for visualization of clusters.
