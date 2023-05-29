# Customer Lifetime Value Prediction
![SoFi Logo](/images/sofi_customers.jpeg)
## About
* Customer Lifetime Value (CLV) is a crucial metric for companies in the finance industry. It helps businesses understand the long-term value that each customer brings, enabling them to make informed decisions about customer acquisition, retention, and overall business strategy.
* A key aspect of CLV prediction involves analyzing customer behavior and preferences. RFM analysis (Recency, Frequency, Monetary) is a method used to segment customers based on their purchase behavior. It evaluates three key aspects: recency, frequency, and monetary value.
* By analyzing these dimensions, businesses can gain insights into customer behavior and preferences. Customers who have recently interacted, make frequent transactions, and have a high monetary value contribute significantly to CLV. These customers can be considered as high-value or loyal customers who require special attention to maintain their satisfaction and loyalty.
* Once customers are segmented based on RFM analysis, CLV prediction comes into play. CLV prediction involves estimating the future value that a customer will bring over their entire relationship. Factors such as average transaction value, purchase frequency, retention rate, and customer churn rate are considered. By predicting CLV, businesses can identify customers with high growth potential, prioritize resources for customer acquisition efforts, and tailor management strategies accordingly.
* Segmenting customers and predicting CLV allows businesses to apply appropriate management strategies for different customer segments. Strategies may include offering personalized services, targeted marketing campaigns, and retention efforts to enhance customer loyalty and satisfaction.

## Procedure
* Deciding the timeframe for CLV and RFM analysis involves considering factors such as business objectives, product lifecycle, customer engagement frequency, data availability, and customer lifecycle.
* For the purposes of this project, we will go ahead use 6 months.
1. Identifying the features for prediction
    1. Use RFM scores for each customer ID for feature set. In order to implement this correctly, we should divide our dataset. We will select a period of 3 months' worth of data, calculate the RFM scores, and then utilize them to predict the following 6 months. Therefore, our first step is to create two dataframes and add the RFM scores to them.'
2. Importing necessary libraries and packages
    1. Feature Engineering
3. Recency
    1. Assigning a recency score
    2. Ordering clusters
4. Frequency
    1. Frequency clusters
5. Revenue
    1. Revenue clusters
6. Overall score based on RFM clustering
7. Customer Lifetime Value
    1. Feature engineering
8. Machine Learning Model for CLV Prediction
9. Final Clusters for CLV
