# Olist-Data-Analysis

## About Olist
Olist is a Brazilian e-commerce platform that connects small and medium-sized businesses to customers across Brazil. 
The platform operates as a marketplace, where merchants can list their products and services and customers can browse and purchase them online.

## About the Dataset;

The Olist sales dataset available on Kaggle is a collection of anonymized data about orders placed on the Olist platform between January 2017 and August 2018. It contains a wide range of information about each order, including the order date, product details, payment and shipping information, customer and seller IDs, and customer reviews. The dataset also includes information about the sellers who list their products on Olist, as well as data on customer behavior and demographics.

## problem statement

To help Olist gain better insights into their e-commerce platform and optimize available opportunities for growth, 
The dataset is designed to help analysts and researchers better understand the e-commerce landscape in Brazil and identify opportunities for growth and optimization.

## Data preprocessing; 
The data preprocessing was done in Excel to remove important discrepances such as duplicates, null values where necessary and convert the data into a consistent manner.
Imported the data into microsoft SQL server to enable me extract the impotant information.
But because project is basically to asnwer Olist business question, i will just delve into it already;

## Exploratory Analysis using SQL

1; What is the total revenue generated by Olist, and how has it changed over time?

Ans: The total revenue generated by Olist was $16M, the month of August generated the highest revenue totaling $1697K

2;  How many orders were placed on Olist, and how does this vary by month or season?

Ans: The second quarter of the year has the highest number of orders placed by customers totaling 29328

3;  What are the most popular product categories on Olist, and how do their sales volumes compare to each other?

Ans; cama_mesa_banho (bed_table_bath), beauty_health by sales volume were the most popular product category totaling $1.7M

4;   What is the average order value (AOV) on Olist, and how does this vary by product category or payment method?

Ans; The average order valu on OList was $154

5; How many sellers are active on Olist, and how does this number change by payment type?

Ans; 2951, 2010, 1046, 679 are total number of active sellers by credit_card, boleto, voucher, debit_card respectively.

6; What is the distribution of seller ratings on Olist, and how does this impact sales performance?

Ans; 5 review_score with 30% seller ratings account for the most sales made by OLIst

7;  How many customers have made repeat purchases on Olist, and what percentage of total sales do they account for?

Ans; 2,997 customers placed order on Olist more than once and they account for approximately 6% of the total sales

8;  What is the average customer rating for products sold on Olist, and how does this impact sales performance?

Ans; The average customer rating on products is 4.0

9; What is the average order cancellation rate on Olist, and how does this impact seller performance?.

Ans; The cancelled orders on average acounted for 625(0.62%) of the total sales on Olist

10;  What are the top-selling products on Olist, and how have their sales trends changed over time?

Ans; The top 2 selling products on Olist were bed_bath_table(Cama_mesa_banho), beauty_health(Beleza_saude) and each accounting for $1.7M and $1.6M of the total sales respectively

11; Which payment methods are most commonly used by Olist customers, and how does this vary by product category or geographic region?

Ans; The payment method commonly used by customers was the credit card with over 74% of it useage, then boleto with 16% of useage compare to other payment method.

bed_bath_table is the product with high purchases made  using the credit card while Sao paulo is the location with the credit card used the most.

12; How do customer reviews and ratings affect sales and product performance on Olist?

Ans; 5 and 4 review_score were given to most product by customers, It shows that customers are mostly satisfied with the company's product.

13; Which product categories have the highest profit margins on Olist, and how can the company increase profitability across different categories?

Ans; telefonia_fixa is the product with the highest profit margins of 68%

14; How does Olist's marketing spend and channel mix impact sales and customer acquisition costs, and how can the company optimize its marketing strategy to increase ROI?

Ans; Olist could impact sales and optimize its marketing strategy to increase ROI by focusing more on  customer retention and loyalty programs, monitor and adjust marketing campaigns.

15;  Geolocation having high customer density. Calculate customer retention rate according to geolocations

Ans; From all 27 States, Sao Paulo had the highest customer concentration with 41,746(41%) customers.

# INSIGHTS
1; Total revenue fo the provided data is $16M with 2016 having the least revenue and 2018, the highest revenue generated year.

2; The average order value from the analysis was $154.

3; A total of 99,441 orders were placed on Olist within the analyzed period. 
The months with the highest number of orders were August, May, and July, while September, October, and December had the least.

4; The top selling products were the bed_bath_table and the beauty_health.

5; Sao paulo is the state with high customer concentration of 41% of the total customer rate

6; Telefonia_fixa is the product with highest profit margin of 68%, drinks (60%), and signaling_and_security (59%). Olist could channel more resources including strtegic marketing for increase in profitability of these product.

7; Average rating score of most products was 4. follwed by 5 reviews. These shows that customers are satisfied with the products on Olist platform.

8; Over 74% of the customers used credit card for payment, debit cards were the least used for payment by customer. These could be base on customer convenience or rewards attached to using this credit cards

9; The order cancellation rate on Olist is approximately 0.6%, indicating a high level of customer satisfaction.

# Limitation

During the cause of this analysis i was'nt able to covert the product category names to english as the data were stored in portuguese language. So to get the name in a common language understood by many(english) i used chatGPT to translate the output for easy communication.

# Conclusion
The Analysis help me to know more about E-commerce platform using (Olist as a case study) with regards to revenue, orders, product categories, customer behavior, and marketing strategy.

## Thank you for reading through!





