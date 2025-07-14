# Brazilian E-Commerce Data Analysis Project

This project provides an end-to-end analysis of the Olist Brazilian E-Commerce dataset, focusing on customer behavior, product performance, revenue trends, churn analysis, and business insights. The goal is to extract actionable insights that can guide marketing, logistics, and customer retention strategies.

---

## 📦 Dataset Information

- **Source:** [Brazilian E-Commerce Dataset by Olist (Kaggle)](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- **Time Period:** Jan 2016 to Aug 2018
- **Primary Tables Used:**
  - `orders_dataset`
  - `order_items_dataset`
  - `customers_dataset`
  - `products_dataset`
  - `order_reviews_dataset`
  - `geolocation_dataset`
  - `order_payments_dataset`

- **Key Columns:**
  - `order_id`, `customer_id`, `order_purchase_timestamp`, `order_delivered_customer_date`, `product_id`, `product_category_name`, `price`, `freight_value`, `review_score`, `payment_value`, `customer_state`

---

Business Questions Answered

1. What are the monthly revenue trends?
2. Which product categories generate the most revenue?
3. Which states have the highest number of customers and purchases?
4. What is the customer retention and churn rate?
5. What are the top-performing products by quantity and revenue?
6. Which categories have the highest shipping costs?
7. What is the average review score by product?
8. What segments do our customers fall into based on RFM?
9. What is the delivery performance and its impact on reviews?
10. What are the top actionable business recommendations?

---

 Approach
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- RFM Segmentation (Recency, Frequency, Monetary)
- Customer Churn Analysis
- Product Performance Metrics
- Visual Analytics
- Final Business Insight Generation

---

Key Business Insights

1. Top 10% of customers contribute ~40% of revenue.
2. SP (São Paulo) state has the highest order volume and revenue.
3. Most users are one-time buyers — low repeat behavior.
4. High-value segments like Champions are small but very profitable.
5. Review scores drop when delivery time increases.
6. Electronics and Accessories lead in both sales and revenue.
7. Furniture and Décor have the highest freight costs.
8. Over 35% of customers churn after 90 days of inactivity.
9. Many products have low performance — potential for cleanup.
10. Retention and loyalty campaigns can greatly increase LTV.

---

🛠 Tools & Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- SQLite3 (for SQL-based analysis)
- Jupyter Notebook

---

How to Run This Project

1. Clone the repository
   bash
   git clone https://github.com/your-username/ecommerce-data-analysis.git
   cd ecommerce-data-analysis
