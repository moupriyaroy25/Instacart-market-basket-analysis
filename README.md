# Instacart-market-basket-analysis
## PCA, K-Means Clustering on Instacart data
- **Approach**:

I have tried to find a possible customer segmenetation enabling to classify customers according the their different purchases.Since there are thousands of products in the dataset so I will use Principal Component Analysis to find new dimensions on products of users ,along with clustering will be easier. I will then try to find possible explanations for the identified clusters.

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
