# Targeted-Marketing-Strategy
![](https://d2qhfytuodj4jf.cloudfront.net/dev/wp-content/uploads/2014/07/09211527/targeted-marketing1.png)

This repository contains the files prepared for Marketing Analytics class project completed under the guidance of [Prof. Garret Sonnier](https://www.mccombs.utexas.edu/Directory/Profiles/Sonnier-Garrett).

### Data 
This project uses publicly available [online retail dataset](https://archive.ics.uci.edu/ml/datasets/online+retail) from UCI Machine Learning repository. 

This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

Attributes:
* InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
* StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
* Description: Product (item) name. Nominal.
* Quantity: The quantities of each product (item) per transaction. Numeric.
* InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.
* UnitPrice: Unit price. Numeric, Product price per unit in sterling.
* CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
* Country: Country name. Nominal, the name of the country where each customer resides.

### Approach
1. Customer RFM segmentation using first 6 months (Dec’10 – May’11) data using k-means clustering to get R,F and M clusters for each customer
2. Analyze the customer movement across different RFM clusters in the first and last 6 months and identify the target segment
3. Recommend products performing market basket analysis maximize sales

Detailed approach is discussed in the presentation deck and the python files has the code used for this project.
