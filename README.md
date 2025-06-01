# Unsupervised-Algorithms-in-Machine-Learning

Customer Segmentation Analysis - Unsupervised learning algorithms.(KMeans, DBSCAN, AgglomerativeClustering)
Customer segmentation using unsupervised learning algorithmsclustering on retail transaction data.


Dataset: 

Online retail data (2009-2011) link : https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci
1,067,371 transactions
Features: Invoice, StockCode, Quantity, Price, CustomerID, Country

Process

Data cleaning - handled missing values and outliers
Exploratory Data Analysis (EDA)
Created features (Recency, Frequency, Monetary)
K-means clustering with hyperparameter tuning
Found optimal 5 clusters

Results
Identified 5 customer segments:

VIP customers (high spenders, frequent)
Loyal customers (regular buyers)
Average customers (occasional)
At-risk customers (inactive recently)
Lost customers (haven't bought in long time)
