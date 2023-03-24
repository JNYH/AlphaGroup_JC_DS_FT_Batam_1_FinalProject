# AlphaGroup_JC_DS_FT_Batam_1_FinalProject

# __Customer Segmentation using RFM Clustering Method on Brazilian E-Commerce Public Dataset by Olist__

**Data Source : https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce**

**Data Creator: Olist**

**Team Members:**
1. Antonius Lemmy Wahyudi
2. Nicholas Jefferson Tansri
3. Sinabutar Yohanes Adolf Gusmories



Welcome! In this project, we will do customer segmentation on a Brazilian e-commerce public dataset of orders made at Olist Store. The dataset has information of around 100.000 orders from 2016 to 2018 made at multiple marketplaces in Brazil. Its features allows viewing an order from multiple dimensions: from order status, price, payment and freight performance to customer location, product attributes and finally reviews written by customers. We also released a geolocation dataset that relates Brazilian zip codes to lat/long coordinates.

# Business Problem Understanding

>**Context**

Olist, as an end-to-end e-commerce company (handles product listing, logistics, and multiple store payment process) that was founded in 2015, is trying to increase transaction traffic on its platform (from both the sellers' and customers' side) to compete as one of the largest end-to-end e-commerce companies in Brazil such as Mercado Livre, B2W, and Via Varejo. To achieve that goal, Olist has to improve the efficiency of business expenses by doing targeted marketing approach for each customer segments.


Source : https://paganresearch.io/company/olist#:~:text=Olist%20was%20founded%20in%202015,Livre%2C%20B2W%20and%20Via%20Varejo

>**Problem Statement**

To increase transaction traffic, Olist needs to know more about the characteristics of its customers so Olist can do better business strategies for each of the customer segments. By doing so, the transaction traffic of Olist will increase and the expense will decrease due to efficiency of targeted approach. If Olist does promotion campaigns without analysing the customers' characteristics, the resources (money, time, effort, etc) spent will be wasted on the wrong customer segment.

>**Goals**

To increase transaction traffic of Olist by giving the correct and targeted promotion campaigns to the right customer according to their characteristics/segments.

>**Analytic Approach**

We are going to use a customer behavior-based marketing analysis that is called RFM (Recency, Frequency, and Monetary). This method is effective to group customers into certain segments based on their purchasing behavior.

The 'Recency' matrix focuses on the activeness of customer (can be seen from the last date of purchase made by customers). The 'Frequency' matrix focuses on the amount or frequency of purchases made by customers on Olist platform. The last matrix, 'Monetary', is used to measure the total historical purchase value. A high score in RFM matrix indicates that the customer has high value (tends to be loyal and generates a lot of revenue) for Olist.
