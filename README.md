#  E-commerce Company
## Introduction
In this project, I am analyzing the **Brazilian E-Commerce dataset**, generously provided by **Olist**, the largest department store in Brazilian marketplaces. Olist connects small businesses across Brazil with sales channels, allowing them to sell their products through the **Olist Store** and ship directly to customers using **Olist logistics partners**. The dataset contains information on **100k orders** made between **2016 and 2018** at multiple marketplaces in Brazil.

The dataset offers insights into various aspects of e-commerce, including **order status**, **pricing**, **payment methods**, and **delivery performance**, as well as **customer location**, **product attributes**, and **customer reviews**. 

The goal of this analysis is to explore **overall performance**, **product trends**, **order patterns**, **customer satisfaction**, and **transaction data** to provide valuable insights into the dynamics of Brazil's e-commerce market.

For this project, I am using **Python** for data processing, analysis, and visualization, and **Power BI** for creating **interactive reports** and **dashboards** to present the findings and insights from the **Brazilian E-Commerce dataset**.



Here are the datasets I am using for the project:

### ✔ Orders dataset
Provide information about orders
- order_id: unique ID of the order
- customer_id: unique ID of the customer
- order_status: order status
- order_purchase_timestamp: time when the order was ordered
- order_approved_at: time the order is approved
- order_delivered_carrier_date: the time the item was delivered to the carrier
- order_delivered_customer_date: the time the item was delivered to the customer
- order_estimated_delivery_date: the estimated time the order will be delivered to the customer

### ✔ Order items dataset  
Provide information about each item in the order and shipping costs
- order_id: unique ID of the order
- order_item_id: ID of the item in the order (item number 1 has ID 1, item 2 has ID 2, etc. Based on this we also know how many items each order has)
- product_id: unique ID of the product in the order
- seller_id: unique ID of the seller
- price: the price of the item
- freight_value: shipping fee

### ✔ Order payments dataset
Provide information about order payments.
- order_id: unique ID of order
- payment_sequential: sequence order
- payment_type: payment type
- payment_installments: full payment (payment_installments = 1) or installment (payment_installments > 1,total payment is splited to many payments .
- payment_value: payment value (payment_value - equal total payments of all times payment installments)

### ✔ Product dataset 
Provide product information
- product_id: unique ID of product
- product_category_name: category product name 
- product_name_lenght: number of product name letters
- product_description_lenght: number of product description letters
- product_photos_qty: number of product photo
- product_weight_g: weight of product  (g)
- product_length_cm: length of product (cm)
- product_height_cm: height of product (cm)
- product_width_cm: width/deep of product (cm)

### ✔ Product category name translation
Translate the product name from Portuguese to English

- product_category_name
- product_category_name_english

### ✔ Order reviews dataset 
Provide review details of each order
- review_id: unique ID of review
- order_id: unique ID of order
- review_score: Review Score
- review_comment_title: Comment title
- review_comment_message: detail of review
- review_creation_date: Created date of review
- review_answer_timestamp: timestamp of review answers

### ✔ Customers dataset
Provide Customer Information 

- customer_id: customer unique ID ( used to link with customer_id of orders_dataset table.
- customer_unique_id: mã unique ID of customer in system of customer information management. 
- customer_zip_code_prefix: zip code of customer
- customer_city: City name of customer 
- customer_state: State name of customer

## Analysis
# 1. Overall 
