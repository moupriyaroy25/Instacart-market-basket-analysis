# Instacart-market-basket-analysis
## PCA, K-Means Clustering on Instacart data
[Instacart market basket analysis dataset]( https://drive.google.com/drive/folders/1NYpXda5Zdig1GlJ5KgHg_ys0YLJBXBZR?usp=sharing)
- **Approach**:

I have tried to find a possible customer segmenetation enabling to classify customers according the their different purchases.Since there are thousands of products in the dataset so I have used Principal Component Analysis to find new dimensions on products of users ,along with clustering . I have then tried to find possible explanations for the identified clusters.

- **My understanding on features from dataframes**

    -   user_id: to identify user
    -   order_id: to identify order by each user
    -   order_number: Each order of a user is characterized
    -   aisle & aisle_id: represent categories of products and number each catogory
    -   product_id &product_name: product names and number to specify each product
    -   add_to_cart_order: a set of product representing the sequence in which they have been added to the cart in that order
    -   reordered: number of reorders
    -   order_dow: to specify the day of week when ordered
    -   order_hour_of_day: to specify the hour of day when ordered
      
- **Steps I've tried to implement as followed**

    :one: Loading data and merging into one data frame
    
    :two: Perform feature extraction and combine product name for word2vec analysis
    
    :three: Extract vectorized feature and combine with rest features
    
    :four:  Implement PCA followed with K-Means Cluster to find a possible customer segmenetation
    
    :five: Visualizing cluster for better understanding for customer segmenetation
    
    
- **Requirments**
  - Google colabatory Notebook ( RAM : 25 GB)
  - Python API Pyspark
  - Python Packages:
    - numpy, panda , matplotlib , seaborn , sklearn
    
## Simple EDA using instacart data
- **Approach**

In this notebook I've mostly worked focusing on visulization of the datasets. As the datas has several csv files so together it has huge amount of various features. So,I tried simplified the relation between each features throgh explortion(as much as possible for me) and by visualizing through various graphs and charts and tried to reach some simple statement conclusion from each graph/chart.

- **Visualization of Relation Between Features (I tried to find)**
    - Reorder frquency in a week
    - Interval between Reorders of Users
    - Frequency Distribution of Reorders w.r.t time of the day
    - Frequency distribution of Day of week Vs Hour of day
    - Most popular 20 products bought by customers (based on product types)
    - Top 20 popular product (based on product names)
    - Department wise reorder ratio
    
- **Requirments**
  - Google colabatory Notebook ( RAM : 25 GB)
  - Python Packages:
    - numpy, panda , matplotlib , seaborn
