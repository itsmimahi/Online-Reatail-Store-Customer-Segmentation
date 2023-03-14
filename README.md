## Online Store Customer Segmentation (Unsupervised ML)
### Problem Statement:
In this project, your task is to identify major customer segments on a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

![customer segmentation pic](https://user-images.githubusercontent.com/105766113/224970296-44ec6e78-baf1-4770-adc4-2dcfdda0be90.jpg)


### Data Description:
A transnational data set with transactions occurring between 1st December 2010 and 9th December 2011 for a UK-based online retailer. The company mainly sells unique all-occasion gifts. and Many customers of the company are wholesalers.


### Attribute Information :

1. InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.

2. StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.

3. Description: Product (item) name. Nominal.

4. Quantity: The quantities of each product (item) per transaction. Numeric.

5. InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.

6. UnitPrice: Unit price. Numeric, Product price per unit in sterling.

7. CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.

8. Country: Country name. Nominal, the name of the country where each customer resides.

### Challenges:


   1. Data cleaning
   2. RFM analysis
   3. Deciding optimal number of clusters
	 
### Model Summary :

Built a clustering model using K-means and Agglomerative clustering to identify major customer segments on transactions data for the UK based non-store online retail. Engineered new features to obtain new features such as RFM, busist days, time, month, RFMGroup, and RFMScore for getting more details about the customer. Obtained optimal number of clusters using Silhouette Analysis, Elbow Method and visual inspection of dendogram resulting from Hierarchical Clustering . Leveraged the visualization library t-SNE for multi-dimentional scaling to visualize and validate the inter-cluster separation and intra-cluster similarity.


### Conclusion :

 ![Screenshot 2022-10-28 221247](https://user-images.githubusercontent.com/105766113/224969928-5ee1c786-835f-4ddc-96f0-5672d260a132.png)

* We got optimal number of clusters=2 with the help of Elbow method, Silhouette score.

### Certificate-

![Customer segmentation Project](https://user-images.githubusercontent.com/105766113/224971446-10d5a1b4-84f9-43fb-8155-aa831a848c47.png)

