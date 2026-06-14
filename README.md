
# 🛒 Olist E-Commerce Sales Dashboard

Built an interactive E-Commerce Analytics Dashboard using Olist dataset with MySQL and Power BI. Performed data cleaning, modeling, and analysis to track revenue, orders, customer behavior, delivery performance, and satisfaction. Delivered actionable insights through dynamic visuals and DAX measures.

---
<img width="1438" height="807" alt="Screenshot 2026-04-03 232232" src="https://github.com/user-attachments/assets/10c1f0e9-64da-4ab2-97aa-39d5e757d29e" />

### 📄 **Page 1: About**

Introduces the Olist dataset, project objectives, and overall business context.
Explains how data is transformed into actionable insights using MySQL and Power BI.

---
<img width="1437" height="817" alt="Screenshot 2026-04-03 232312" src="https://github.com/user-attachments/assets/5a904847-b453-4ab4-945b-662486576698" />

### 📄 **Page 2: Executive Overview**

Displays key KPIs like total revenue, orders, customers, and delivery performance.
Provides a quick snapshot of overall business health and performance trends.

---

<img width="1432" height="810" alt="Sales Dashboard" src="https://github.com/user-attachments/assets/1d346e08-579a-4e18-bbc1-d944850e969a" />

### 📄 Page 3: Sales Performance Analysis

Analyzes revenue trends, top product categories, and payment method distribution.
Identifies key drivers of sales growth and highlights high-performing segments.

---

<img width="1442" height="822" alt="Customer Dashboard" src="https://github.com/user-attachments/assets/c47a7dc4-8714-426e-a58d-0f515bea9e90" />

### 📄 Page 4: Customer Insights & Segmentation

Explores customer distribution, behavior, and geographic presence.
Helps understand the customer base and identify targeting opportunities.

---

<img width="1447" height="817" alt="Logistics Dashboard" src="https://github.com/user-attachments/assets/b43782fa-03cd-4cf6-a6a0-288daf94fc69" />

### 📄 Page 5: Logistics & Delivery Performance

Evaluates shipping efficiency, delivery timelines, and fulfillment performance.
Highlights the impact of logistics on service quality and operational efficiency.

---

<img width="1450" height="817" alt="Feedback Dashboard" src="https://github.com/user-attachments/assets/6982352e-acfa-4111-908f-324754d3bd95" />

### 📄 Page 6: Customer Feedback & Satisfaction

Analyzes review scores, sentiment trends, and feedback patterns.
Shows how delivery performance and service quality affect customer satisfaction.

---

<img width="1452" height="817" alt="Advanced Insights Dashboard" src="https://github.com/user-attachments/assets/e13bdcbc-b973-4609-87fd-7ebc1dc3d7e0" />

### 📄 Page 7: Others (Advanced Insights)

Provides additional deep-dive analysis such as revenue correlation, product size impact, and seller performance.
Uncovers hidden patterns and supports strategic decision-making.

---

<img width="1440" height="813" alt="Tooltip View" src="https://github.com/user-attachments/assets/ca067f7f-a60d-4e3a-997d-ef702e11f6c6" />

### 🖱️ Tooltip (Interactive Insights)

Displays contextual information such as revenue, orders, and delivery metrics on hover.
Enhances user experience by providing insights without cluttering the dashboard.

---

<img width="1437" height="817" alt="Drillthrough View" src="https://github.com/user-attachments/assets/5cdea860-0d65-43a0-a020-63c8b7abb286" />

### 🔍 Drillthrough (Detailed Analysis)

Allows navigation from summary visuals to detailed, record-level insights.
Enables deeper analysis of categories, customers, or orders for better decision-making.

---

## 📌 Project Overview

This project analyzes the Olist E-Commerce dataset to evaluate overall business performance, customer behavior, sales trends, delivery efficiency, and customer satisfaction.

The dashboard transforms raw transactional data into meaningful business insights, helping stakeholders make data-driven decisions. The project demonstrates data cleaning, data modeling, KPI creation, and interactive dashboard development using MySQL and Power BI.

---

## 🎯 Objective

The primary objective of this project is to analyze e-commerce business performance using the Olist dataset and uncover valuable insights related to sales, customers, products, payments, and deliveries.

The dashboard aims to:

* Monitor overall business performance
* Identify top-performing product categories
* Analyze customer purchasing behavior
* Evaluate delivery performance
* Measure customer satisfaction through reviews
* Support strategic decision-making with data-driven insights

---

## 📂 Dataset

The Olist dataset contains real-world Brazilian e-commerce transaction data and includes information from multiple business areas.

### Key Data Tables

| Table       | Description                            |
| ----------- | -------------------------------------- |
| Customers   | Customer details and locations         |
| Orders      | Order information and status           |
| Order Items | Product-level order details            |
| Products    | Product categories and information     |
| Payments    | Payment methods and transaction values |
| Reviews     | Customer ratings and feedback          |
| Sellers     | Seller information                     |
| Geolocation | Customer and seller locations          |

---

## 🔧 Data Cleaning & Transformation

The following data preparation steps were performed:

* Cleaned and validated raw data using MySQL
* Removed inconsistencies and duplicate records
* Handled missing values where necessary
* Created relationships between multiple tables
* Organized data into a structured model
* Imported cleaned data into Power BI
* Created calculated measures using DAX

---

## 📊 Key Performance Indicators (KPIs)

The dashboard includes the following KPIs:

* Total Revenue
* Total Orders
* Total Customers
* Average Order Value (AOV)
* Customer Satisfaction Score
* Average Delivery Time
* Total Products Sold

---

## 🎛 Dashboard Features

Interactive dashboard pages allow users to analyze:

### Sales Analysis

* Revenue trends over time
* Top-performing product categories
* Order distribution analysis

### Customer Analysis

* Customer locations
* Customer purchase behavior
* Customer growth trends

### Delivery Analysis

* Delivery duration tracking
* Delayed vs. on-time deliveries
* Logistics performance evaluation

### Review Analysis

* Customer ratings distribution
* Satisfaction trends
* Impact of delivery performance on reviews

---

## 📈 Visualizations

The dashboard includes:

| Visualization      | Purpose                          |
| ------------------ | -------------------------------- |
| KPI Cards          | Business performance overview    |
| Line Charts        | Revenue and order trends         |
| Bar Charts         | Category and customer analysis   |
| Map Visualizations | Geographic customer distribution |
| Pie/Donut Charts   | Payment method analysis          |
| Tables & Matrix    | Detailed business insights       |
| Slicers            | Interactive filtering            |

---

## 💡 Key Insights

* Credit card is the most preferred payment method.
* Certain product categories generate significantly higher sales.
* Faster deliveries are associated with better customer ratings.
* Major cities contribute the highest share of customers and revenue.
* Customer satisfaction is strongly influenced by delivery performance.

---

## ⚠️ Limitations

* Cost and profit data are not available in the dataset.
* Profitability analysis cannot be performed accurately.
* Some business assumptions were made based on available information.

---

## 🚀 Future Improvements

Potential enhancements include:

* Profit and margin analysis
* Sales forecasting and trend prediction
* Advanced customer segmentation
* Real-time dashboard integration
* Predictive analytics using machine learning

---

## 🛠 Tools Used

* MySQL – Data Cleaning and Querying
* Power BI – Data Visualization and Dashboard Development
* DAX – KPI and Measure Creation

---

## 📁 Repository Structure

```text
📂 Olist-Ecommerce-Dashboard/
│
├── Dataset/
│   └── Olist Dataset Files
│
├── SQL/
│   └── Data Cleaning Queries.sql
│
├── Power BI/
│   └── Olist Dashboard.pbix
│
├── Docs/
│   └── Dashboard Screenshots
│
└── README.md
```

---

## 📌 Conclusion

This project demonstrates how data analytics can be used to understand and improve e-commerce business performance.

By combining MySQL for data preparation and Power BI for visualization, the dashboard provides actionable insights into sales, customers, deliveries, and customer satisfaction. The project strengthened practical skills in SQL, Power BI, DAX, and business intelligence reporting.

---

## 👤 Author

**Your Name**

* LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/in/mauzzamshaikh1104/)
* GitHub: [Your GitHub Profile](https://github.com/MAUZZAM123)

---

## 🌟 Feedback & Support

If you found this project useful, consider giving it a ⭐ on GitHub.

Feedback, suggestions, and contributions are always welcome!
