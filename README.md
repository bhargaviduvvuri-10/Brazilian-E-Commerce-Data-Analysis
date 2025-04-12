# 📊 Brazilian E-Commerce Data Analysis — Power BI Project
This project analyzes a Brazilian e-commerce dataset using Power BI. It provides insights into customer behavior, order patterns, delivery performance, payment types, and sales trends.

## 📁 Dataset
The dataset used is the Brazilian E-Commerce Public Dataset by Olist, which includes:

Orders

Customers

Sellers

Products

Reviews

Payments

Geolocation

## 🔍 Key Features
Overview dashboard showing total orders, customers, revenue, and average delivery time.

Time-series analysis of orders by day/month.

Customer segmentation by location (state and city).

Delivery performance: estimated vs. actual delivery time.

Most used payment methods and installment patterns.

Reviews analysis (ratings and review comments).

Product category analysis by sales volume and revenue.

## 📌 Insights
Majority of orders come from the Southeast region of Brazil.

Delays in delivery tend to correlate with negative reviews.

Credit card is the most preferred payment method.

Specific product categories dominate sales and revenue.

Installment payments are common and influence revenue per order.

## 🔍 Key Findings:

There is a clear correlation between delivery delays and lower customer review scores.

Orders delivered late (compared to estimated delivery date) are significantly more likely to receive 1- or 2-star reviews.

On-time or early deliveries often receive 4 or 5 stars.

Certain product categories and seller regions have higher delay rates.

Items from some regions (e.g., North or remote states) show longer delivery times due to logistics issues.

Larger items or certain categories (e.g., furniture) tend to be delayed more.

Customers in rural areas or regions far from seller hubs face longer average delays.

This is due to extended transit times and fewer carrier options.

Sellers with lower average scores also tend to have more delayed deliveries.

## 🛠️ Recommendations to Reduce Delay and Improve Satisfaction
1. Improve Estimated Delivery Accuracy
Recalculate estimated delivery times based on:

Historical delivery time by region

Seller performance

Product category

This will manage customer expectations better and reduce frustration even if the actual delivery duration doesn't improve.

2. Partner with Regional Logistic Providers
In areas with consistent delays, work with local delivery services or 3PLs (third-party logistics) that specialize in those regions.

This can optimize last-mile delivery.

3. Enable Priority Fulfillment for Frequently Delayed Categories
Add logistics prioritization for high-delay product categories.

Provide incentives for sellers to dispatch these items faster.

4. Introduce Seller Performance-Based Delivery SLAs
Monitor seller delivery behavior.

Use penalties for chronic delay and rewards for consistent on-time dispatch.

5. Offer Real-Time Delivery Tracking with Alerts
Provide customers with live tracking and proactive alerts if delays are expected.

Improves transparency and helps manage expectations, reducing dissatisfaction.

6. Automated Delivery Risk Flagging
Use machine learning or rules-based logic to flag orders likely to be delayed (based on seller, product, region).

Offer those customers options like upgraded shipping or clearer expectations.

7. Empower Customer Support for Delayed Deliveries
Offer vouchers or personalized support for delayed orders with low ratings.

This may turn a poor experience into a neutral or positive one.



## 🛠️ Tools Used
Power BI Desktop

DAX (Data Analysis Expressions)

Power Query (M)

Data modeling and relationships
