# Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning

Background:
A company can develop rapidly when it knows the behavior of its customer personality, so that it can provide better services and benefits to customers who have the potential to become loyal customers. Company need to know it's customer behavior to boost marketing campaign.

Goal:
Improve marketing campaign performance and target the right customers to be able to do transaction(s) on the company's platform.

Objective:
Create a cluster prediction model so that it makes easier for companies to make decisions.

Data:
Dataset contains customer behavior features who made transactions and interactions on our platform.

Tools:
On this project I've used python as programming language; jupyterlab as notebook; pandas, numpy, sklearn and dython to preprocessing and machine learning section; combination of matplotlib and seaborn library to generated data visualization.

Contents:
Exploratory Data Analysis
Data Cleaning and Preprocessing
On this section, there are few processes such as handling missing and duplicated value, feature selection using RFMLC (Recency, Frequency, Monetary, Loyalty and C) methods, handling outliers using IQR (Q1=1%; Q3=99%), feature transformation to selected features using minmaxscaler, and splitting data on 70:30 proportion.

Data Modeling:
Using K-Means Clustering with cross-validation elbow method to inertia and silhoutte score

Customer Persoality Analysis for Marketing Retargeting:

Based on my model, there are 4 customer clusters:

- High-Valued Customer: Customers on this group have high average recency (73 days) and high average of total purchases (21 items) it means they are not frequent shoppers but they spend a lot on our platform (around IDR 1M/year).
- Low-Valued Customer: Customers on this group have highest average recency (74 days) and low average of total purchases (8 items) it means they are not frequent shoppers and they spend a little on our platform (around IDR 92K/year).
- High-Valued Frequent Customer: Customers on this group have low average recency (23 days) and high average of total purchases (21 items) it means they are frequent shoppers and they spend a lot on our platform (around IDR 989K/year).
- Low-Valued Frequent Customer: Customers on this group have high average recency (24 days) and lowest average of total purchases (7 items) it means they are frequent shoppers but they spend a little on our platform (around IDR 75K/year).

Recommedation:
Actionable Insights:
- Develop a membership tier program to enhance customer retention and incentivize increased shopping activity on our platform. We can establish four membership tiers - Platinum, Gold, Silver, and Bronze - each offering distinct privileges to customers. The level of membership will correspond to customer clusters, with Platinum reserved for high-value customers, Gold for highly frequent customers, Silver for moderately frequent customers, and Bronze for customers with lower value.

- To minimize churn risk, our primary focus should be on the High-Valued Customers group. We need to closely monitor their purchasing trends and implement strategies to retain their loyalty. This can be achieved by improving our services, providing excellent after-sales support, maintaining product quality, and optimizing our mobile apps. Additionally, we can offer them the top-tier Platinum membership, entitling them to exclusive benefits such as higher discounts, promotions, and free shipping. These perks will encourage them to shop more frequently on our platform.

- To further boost engagement from the High-Valued Frequent Customer group, we should provide them with additional promotions and coupons for free shipping through our membership tier program. By doing so, we aim to incentivize them to shop more often on our platform, leveraging their loyalty and strengthening their connection with our brand.

- Since the Low-Valued Frequent Customer and Low-Valued Customer segments have the lowest overall spending, we should concentrate on creating personalized advertisements, promotions, and campaigns that target affordable products. This approach aims to attract these customer groups to our platform. By tailoring our marketing efforts to their specific preferences and needs, we have the potential to increase their frequency of purchases and overall spending on lower-cost items, ultimately enhancing their engagement levels.

Potential Impact (Quantitative):
If we keep prioritize on Customer Groups/Clusters and they do not turn to churn, we still have potential GMV around IDR 1.3B/year (High-Valued Customer=IDR 670M/year; Low-Valued Customer=IDR 46M/year; Low-Valued Frequent Customer=IDR 604M/year; Low-Valued Customer=IDR 47M/year).
