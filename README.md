# 📊 Customer Behavior Analysis Project

## 🔍 Overview
This project analyzes customer purchasing behavior using Python, SQL, and Power BI.  
The goal is to extract meaningful insights, identify trends, and build an interactive dashboard to support business decision-making.

---

## 📁 Dataset
- Source: Customer dataset (CSV format)
- Contains:
  - Customer ID
  - Gender
  - Age
  - Purchase Amount (USD)
  - Subscription Status
  - Product Category
  - Location

---

## 🛠️ Tools & Technologies
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **SQL** (PostgreSQL / MySQL)
- **Power BI** (Dashboard & Visualization)
- **Jupyter Notebook**
- **GitHub** (Version Control)

---

## ⚙️ Steps Performed

### 1. Data Loading
- Loaded dataset using Python (Pandas)
- Imported data into PostgreSQL for SQL analysis

### 2. Data Cleaning
- Handled missing values
- Fixed data types
- Removed duplicates
- Standardized column names

### 3. Exploratory Data Analysis (EDA)
- Analyzed customer demographics
- Identified spending patterns
- Compared purchase behavior across gender & subscription status

### 4. SQL Analysis
- Wrote queries to calculate:
  - Total revenue
  - Average spending
  - Customer segmentation
- Example:
sql
SELECT gender, SUM(purchase_amount_usd) AS revenue
FROM customer
GROUP BY gender;

5. Dashboard Creation (Power BI)
Built interactive dashboard with:
Revenue by gender
Subscription insights
Category-wise sales
Used filters, slicers, and KPIs

6. Reporting
Created a presentation (PPT) summarizing:
Key insights
Business recommendations

📊 Key Insights
Male/Female customers show different spending patterns
Subscribers contribute higher average revenue
Certain product categories dominate sales
Customer segmentation helps target marketing strategies

▶️ How to Run
Clone the repository:
git clone https://github.com/sanmitha2905/customer_behavior_analysis.git
Open Jupyter Notebook:
jupyter notebook
Run SQL queries in PostgreSQL
Open Power BI dashboard file (.pbix)

🤝 Conclusion
This project demonstrates end-to-end data analysis including data cleaning, SQL querying, visualization, and reporting.
It showcases practical skills required for a data analyst role.

⭐ Author
P.Sanmitha
