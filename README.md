# SQL_Data_Analysis_Projects
This is a end to end Data Analysis Project on Data set from Target Corporation.

Case study has been done on Big Query.

Data Set is attached in the repository.



## Why this case study?

### From company’s perspective:
 
 
 ● Target is a globally renowned brand and a prominent retailer in the United States.
Target makes itself a preferred shopping destination by offering outstanding value,
inspiration, innovation and an exceptional guest experience that no other retailer can
deliver.


 ● This particular business case focuses on the operations of Target in Brazil and provides
insightful information about 100,000 orders placed between 2016 and 2018. The
dataset offers a comprehensive view of various dimensions including the order status,
price, payment and freight performance, customer location, product attributes, and
customer reviews.


 ● By analyzing this extensive dataset, it becomes possible to gain valuable insights into
Target's operations in Brazil. The information can shed light on various aspects of the
business, such as order processing, pricing strategies, payment and shipping efficiency,
customer demographics, product characteristics, and customer satisfaction levels.


### The data is available in 8 different csv files:
1. customers.csv
2. geolocation.csv 
3. order_items.csv
4. payments.csv
5. reviews.csv
6. orders.csv
7. products.csv
8. sellers.csv


## What are we exploring about the data set?

I. Import the dataset and do usual exploratory analysis steps like checking the
structure & characteristics of the dataset.

* Data type of all columns in the “customers” table.
* Get the time range between which the orders were placed.
* Count the Cities & States of customers who ordered during the given period.

II. In-depth Exploration:
* Is there a growing trend in the no. of orders placed over the past years?
* Can we see some kind of monthly seasonality in terms of the no. of orders being
placed?
* During what time of the day, do the Brazilian customers mostly place their
orders? (Dawn, Morning, Afternoon or Night)

   ● 0-6 hrs : Dawn
  
   ● 7-12 hrs : Mornings
  
   ● 13-18 hrs : Afternoon
  
   ● 19-23 hrs : Night

III. Evolution of E-commerce orders in the Brazil region:
* Get the month on month no. of orders placed in each state.
* How are the customers distributed across all the states?

IV. Impact on Economy: Analyze the money movement by e-commerce by looking at
order prices, freight and others.
* Get the % increase in the cost of orders from year 2017 to 2018 (include
months between Jan to Aug only).
* Calculate the Total & Average value of order price for each state.
* Calculate the Total & Average value of order freight for each state.

V. Analysis based on sales, freight and delivery time.
* Find the no. of days taken to deliver each order from the order’s purchase date
as delivery time.
Also, calculate the difference (in days) between the estimated & actual delivery
date of an order.
* Find out the top 5 states with the highest & lowest average freight value.
* Find out the top 5 states with the highest & lowest average delivery time.
* Find out the top 5 states where the order delivery is really fast as compared to
the estimated date of delivery.

VI. Analysis based on the payments:
* Find the month on month no. of orders placed using different payment types.
* Find the no. of orders placed on the basis of the payment installments that have
been paid.

### Recommendation and Insights concluded from the data analysis has been mentined in the PDF at evry step.

