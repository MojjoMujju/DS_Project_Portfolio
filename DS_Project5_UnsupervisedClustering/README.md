# Customer Segmentation
Welcome to this repository! This repository is dedicated to a customer segmentation project, where we analyze and model data related to segment customers in e e-commerce dataset. The project's objective is to construct a predictive model that facilitates early identification of patterns in customer behavior.

## Repository Contents:
### Dataset: 
- This dataset consists of 541909 rows and 8 columns.
- Variables contain customer data.

### Features:
1. 	InvoiceNo: Customer invoice Number.
2. 	StockCode: Unique identifier.
3. 	Description: Product description.
4. 	Quantity: Product quantity.
5. 	InvoiceDate: Invoice Date.
6. 	UnitPrice: Product Prices.
7. 	CustomerID: Customer Unique identifier.
8. 	Country: Country

### Notebooks:

#### EDA (Exploratory Data Analysis) & FE (Feature Engineering) : 
- Handling Missing Values.
- Check Anomaly Data.
- Country Column Analysis.
- Purchasements Analysis
- RFM Analysis.
- Merge Data.
- One Hot Encoding.
- Standardization (StandartScaller)

#### Modelling
- Make models (KMeans)
- Models evaluation (Silhouette Score Method)

### Model Result:
- Make labels with 6 clusters.
![image](https://github.com/MojjoMujju/DS_Project_Portfolio/assets/84460310/9357bf70-0d15-4250-ba91-426596d51b06)

### Report:
#### Characteristics of Each Cluster
#### Cluster 0 : 
Cluster 0 consists of customers who shop quite frequently at specific intervals (recency), with a moderate shopping frequency (frequency), and the amount spent is not excessively high (monetary).

#### Cluster 1 : 
Cluster 1 comprises customers who rarely shop, as indicated by average shopping recency of around 247 days, low shopping frequency, and the lowest monetary expenditure compared to other clusters.

#### Cluster 2 : 
Cluster 2 represents customers who infrequently shop (recency), yet have a relatively high transaction frequency, even higher than Cluster 0, which is more active in shopping (frequency). The amount spent in this cluster is not substantial (monetary) when compared to clusters 3, 4, and 5.

#### Cluster 3 : 
Cluster 3 includes customers who shop quite frequently (recency), with a high shopping frequency and a significant amount spent (monetary), although not as much as in Cluster 4.

#### Cluster 4 : 
Cluster 4 consists of loyal customers who spend the most (monetary), shop most frequently (recency), and have a very high shopping frequency (frequency).

#### Cluster 5 :
Cluster 5 comprises customers who potentially shop every month (recency), with a relatively high shopping frequency (frequency), and a considerable monetary expenditure (monetary).
