<h1>📊 Customer Sentiment & Sales Correlation Dashboard</h1>

<h2>🔍 Project Overview</h2>

The Customer Sentiment & Sales Correlation Dashboard is a data analytics project that analyzes how customer sentiment extracted from reviews impacts sales revenue across different products, time periods, and geographical regions.

This project integrates Python-based data processing with Power BI dashboards to transform raw customer data into meaningful business insights.

<h2>🎯 Project Objectives</h2>
•  Analyze customer sentiment (Positive, Neutral, Negative)<br>
•  Understand the relationship between sentiment and revenue<br>
•  Identify top-performing products based on sentiment<br>
•  Analyze sales trends over time and across regions<br>
•  Support data-driven business decisions<br>

<h3>🗂 Dataset Used</h3>

•  customer_purchase_data.csv<br>
•  customer_reviews_data.csv<br>
•  merged_customer_sentiment_sales.csv<br>

<h4>Dataset Contains:</h4>
•  Product Name & Category<br>
•  Country & Month<br>
•  Revenue<br>
•  Customer Reviews<br>
•  Sentiment Label (Positive / Neutral / Negative)<br>
•  Sentiment Polarity Score<br>


<h3>🛠 Tools & Technologies</h3>

•  Python (Pandas, NumPy) – Data cleaning, merging & preprocessing<br>
•  Power BI – Dashboard creation & analysis<br>
•  DAX – Measures & KPIs<br>
•  CSV / Excel – Data storage<br>

<h3>📐 DAX Measures Used</h3>

•  Total Revenue = SUM('merged_customer_sentiment_sales'[Revenue])

•  Total Reviews = COUNTROWS('merged_customer_sentiment_sales')

•  Avg Sentiment Polarity = AVERAGE('merged_customer_sentiment_sales'[Polarity])

•  Positive Reviews = CALCULATE(COUNTROWS('merged_customer_sentiment_sales'),'merged_customer_sentiment_sales'[Sentiment] = "Positive")

•  Negative Reviews = CALCULATE(COUNTROWS('merged_customer_sentiment_sales'),'merged_customer_sentiment_sales'[Sentiment] = "Negative")

•  Positive % = DIVIDE([Positive Reviews], [Total Reviews], 0)

•  Revenue Per Review = DIVIDE([Total Revenue], [Total Reviews], 0)


<h2>📊 Dashboard 1: Customer Sentiment & Sales Overview</h2>

![Customer Sentiment & Sales Overview](images/DASHBOARD_1.png)

<h3>🔑 Key Insights</h3>

•  Total Revenue: 15M<br>
•  Total Reviews: 10K<br>
•  Positive Reviews: 73%<br>
•  Revenue increased from 2023 to 2024, aligned with improved sentiment<br>
•  Positive sentiment contributes over 70% of total revenue<br>

<h3>📌 Visuals Included</h3>

•  KPI Cards (Revenue, Reviews, Avg Sentiment)<br>
•  Revenue vs Avg Sentiment by Year<br>
•  Revenue Distribution by Sentiment<br>
•  Revenue by Product Name<br>
•  Filters for Category, Country, Month, and Sentiment<br>


<h2>📊 Dashboard 2: Product Sentiment & Performance Analysis</h2>

![Product Sentiment and Performance Analysis](images/DASHBOARD_2.png)

<h3>🔍 Dashboard Explanation</h3>

This dashboard focuses on product-level analysis, highlighting how sentiment affects individual product performance.

<h3>🔑 Key Insights</h3>

•  Home Appliances generate higher revenue than Electronics<br>
•  Products like Toaster, Smartwatch, Heater perform consistently well<br>
•  Laptop has the highest average sentiment polarity<br>
•  Products with higher positive sentiment generally receive more reviews and revenue<br>

<h3>📌 Visuals Included</h3>

•  Product-wise Revenue & Sentiment Table<br>
•  Revenue by Product Name (Bar Chart)<br>
•  Avg Sentiment Polarity by Product<br>
•  Sentiment distribution by Product Category<br>


<h2>📊 Dashboard 3: Geographical & Temporal Analysis</h2>

![Geographical and Temporal Analysis](images/DASHBOARD_3.png)

<h3>🔍 Dashboard Explanation</h3>

This dashboard analyzes sales and sentiment trends across time and geography.

<h3>🔑 Key Insights</h3>

•  Q3 and Q4 show the highest revenue contribution<br>
•  September and December are peak months for sales<br>
•  Monthly sentiment polarity trends closely follow revenue patterns<br>
•  North America and Asia contribute the highest revenue globally<br>

<h3>📌 Visuals Included</h3>

•  Monthly Revenue vs Avg Sentiment Trend<br>
•  World Map showing Revenue by Country<br>
•  Quarterly Revenue split by Sentiment<br>

<h3>📈 Overall Insights Summary</h3>

•  Positive sentiment has a strong correlation with higher revenue<br>
•  Products with higher engagement (reviews) perform better<br>
•  Seasonal trends significantly affect sales and sentiment<br>
•  Neutral sentiment still contributes a substantial portion of revenue<br>
•  Regional demand patterns influence overall performance<br>

<h3>🚀 Future Enhancements</h3>

•  Real-time sentiment analysis using APIs<br>
•  Advanced NLP models (BERT / Transformers)<br>
•  Customer segmentation & churn analysis<br>
•  Predictive sales forecasting<br>
•  Live database integration<br>

✅ This project demonstrates strong skills in data analytics, sentiment analysis, Power BI, DAX, and business storytelling.

















