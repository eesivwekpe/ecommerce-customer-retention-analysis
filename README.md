E-Commerce Customer Retention & Cohort Analysis
Business Context

ShopSphere, an e-commerce platform, aims to improve customer retention and long-term revenue growth. Understanding how customers behave after their first purchase is critical to identifying high-value segments, reducing churn, and increasing lifetime value.

This project applies cohort analysis, RFM segmentation, and retention modelling to generate actionable business insights.

Objectives

Perform cohort analysis based on customers’ first purchase month

Build a retention matrix to measure repeat purchase behaviour over time

Calculate repeat purchase rate

Segment customers using RFM (Recency, Frequency, Monetary) analysis

Estimate Customer Lifetime Value (CLV proxy)

Provide data-driven business recommendations

Dataset

Transactional dataset containing:

Customer ID

Order Date

Revenue

Data was cleaned and transformed to support cohort grouping and segmentation analysis.

Tools & Techniques Used

Python (Pandas, NumPy)

Data Visualisation (Matplotlib / Seaborn)

Cohort Analysis methodology

RFM Segmentation

Retention Matrix & Heatmap

CLV Estimation

Analytical Approach
 Cohort Analysis

Customers were grouped by their first purchase month to track behaviour over time. A retention matrix was built showing:

Month 0 (initial purchase)

Month 1, Month 2, Month 3, etc.

Percentage of customers returning in each subsequent month

A heatmap visualisation was created to identify retention decay patterns.

 Repeat Purchase Rate

Calculated to measure how many customers made more than one purchase.

RFM Segmentation

Customers were segmented based on:

Recency (time since last purchase)

Frequency (number of purchases)

Monetary value (total spend)

Segments identified:

V-VIPs

Highest frequency and monetary scores (normalized to 1)

Extremely valuable and highly engaged customers

VIPs

Strong frequency and spending patterns

High-potential customers suitable for targeted nurturing

Loyal Regulars

Balanced across metrics with moderate spending

Stable revenue contributors

At-Risk / Lost Customers

Low recency and declining engagement

High churn probability

Customer Lifetime Value 

Estimated CLV using historical revenue and purchase frequency trends to identify long-term revenue drivers.

Key Insights

Retention declines significantly after Month 2, indicating early churn risk.

Revenue is highly concentrated among V-VIP and VIP segments.

Repeat customers generate significantly higher average revenue per user.

Loyal Regulars represent an opportunity for upselling and revenue expansion.

At-Risk customers show declining frequency patterns before churn.

Business Recommendations
 High-Value Segments (V-VIPs & VIPs)

Implement tier-based loyalty programs to maximise lifetime value.

Provide exclusive offers and early access incentives.

Use personalised recommendations to increase frequency and basket size.

Loyal Regulars

Apply data-driven upselling and cross-selling strategies.

Introduce rewards encouraging movement into higher-value tiers.

Increase engagement through personalised campaigns and targeted offers.

 At-Risk / Lost Customers

Deploy reactivation campaigns with limited-time incentives.

Collect feedback to identify churn drivers.

Simplify return-to-purchase journey with frictionless re-engagement flows.

Project Outcome

This analysis demonstrates how cohort modelling and segmentation can transform raw transaction data into actionable retention strategy, enabling data-driven decision-making for revenue optimisation.
