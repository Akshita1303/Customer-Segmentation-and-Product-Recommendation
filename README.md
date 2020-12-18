# Customer-Segmentation-and-Product-Recommendation
PROBLEM STATEMEMT:

Primary goal of the project is to recommend products to customer after dividing them into different segments. This will be achieved by:

1. Distinguishing active customers from inactive customers.

2. Studying customer behaviour and predicting customer lifetime value

4. Recommendation using product rating and reviews    



DATASET, DATA DESCRIPTION AND DATA SOURCE:


This dataset was provided by Olist, the largest department store in Brazilian marketplaces. Olist connects small businesses from all over Brazil to channels without hassle and with a single contract. Those merchants are able to sell their products through the Olist Store and ship them directly to the customers using Olist logistics partners.

After a customer purchases the product from Olist Store a seller gets notified to fulfil that order. Once the customer receives the product, or the estimated delivery date is due, the customer gets a satisfaction survey by email where he can give a note for the purchase experience and write down some comments.








BRIEF DESCRIPTION AND PLAN OF ANALYSIS:

Customer Segmentation is the process of dividing the similar customer into homogenous groups for the sake of classification and study. Customers are segmented in similar groups based on their likes or dislikes of a particular product. This helps to target specific brands/product towards a specific group of customers and helps to form a tailored marketing strategy.

Using the Clustering technique and by combining olist_customers_dataset, olist_geolocation_dataset, olist_orders_dataset, olist_products_dataset and olist_products_dataset we will divide our customers into different segments on the basis of:

1. Geography

2. Demography

3. Behaviour

4. Revenue Generation

Next step is to find the Customer Lifetime Value. Customer Lifetime Value (CLV), represents the total amount of money a customer is expected to spend in your business, or on your products, during their lifetime. By the equation below, we can have Lifetime Value for each customer in that specific time window:  Total Gross Revenue – Total Cost

By calculating lifetime value for each customer we will know what products are we supposed to recommend them.

Taking all the above points into consideration we’ll build a recommendation system using olist_products_dataset, olist_order_reviews_dataset and olist_customers_dataset. 



SCOPE:

Scope of the project is to come up with a solution to increase customer base and overall revenue by appropriately targeting all the customer, to strongly hold the loyal and satisfied customers and retain dissatisfied and one time customers.
