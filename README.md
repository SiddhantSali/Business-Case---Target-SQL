# Business-Case---Target-SQL

This business case focuses on the operations of Target in Brazil and provides Insights and recommendations by analyzing data of 100,000 orders placed between 2016 and 2018.

Introduction to Business Case:
Target is a globally renowned brand and a prominent retailer in the United States. This particular business case focuses on the operations of Target in Brazil and provides insightful information about 100,000 orders placed between 2016 and 2018. The dataset offers a comprehensive view of various dimensions including the order status, price, payment and freight performance, customer location, product attributes, and customer reviews.

The data is available in 8 CSV files:

customers.csv
sellers.csv
order_items.csv
geolocation.csv
payments.csv
reviews.csv
orders.csv
products.csv
By analyzing this extensive dataset, it becomes possible to gain valuable insights into Target's operations in Brazil. The information can shed light on various aspects of the business, such as order processing, pricing strategies, payment and shipping efficiency, customer demographics, product characteristics, and customer satisfaction levels.

Tools and Databases used:
Google BigQuery
Insights and Business Recommendations
1.	The orders trajectory shows a sharp rise in the volume of orders within a short period of time. Business in Brazil is growing quickly, according to the general trend, thus companies need to be prepared with more staff. Company may think about employing contract workers to reduce excessive risk.
2.	Total 609 orders were unavailable and 625 orders were cancelled during the given time period, which makes it  to be  around 1.2 % of total orders.  We can reduce this number by studying the reasons behind order cancellation and items unavailability.
3.	The query below calculates the ratio of review score for each is state. While, the extracted data is ordered to get the states with higher proportion of unsatisfied customers.
4.	A closer look reveals that the majority of these complaints mention problems with deliveries that were delayed or that the consumer did not get. However, a lot of the negative reviews are also brought on by things that were shipped incorrectly or damaged. Therefore, the business should concentrate on improving its logistics in order to win over customers and increase profitability. The most popular review titles are displayed with the following query.
5.	Rio de Janeirio, Sao Paulo and Belo Horizonte among others cities in Brazil that contribute the major chunk of orders. The company can upscale their businesses by improving their product offerings and logistics in order to attain higher customer satisfaction to gain more trust in these markets. The results of this analysis can be referred from “In-depth Analysis”, consisting the data for number of customers and number of orders placed per city.
6.	Additionally, Brazilian customers show a tendency for shopping online during afternoon and night. The company can focus on scheduling and optimizing their digital marketing campaigns during these hours of the day to increasing customer engagement.


