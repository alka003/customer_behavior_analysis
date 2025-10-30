# 🛍️ Customer Shopping Behaviour Analysis -Data Analyst Project

## 📖 Overview
This project analyzes customer shopping behavior to uncover insights about spending patterns, product preferences, and purchasing habits. It combines **Python (EDA & Cleaning)**, **MySQL (SQL Queries)**, and **Power BI (Visualization)** to create a full end-to-end analytics pipeline, ending with a **Gamma presentation** summarizing findings.

---

## 🧾 Dataset
- **Name:** `Customer_Shopping_Behaviour.csv`
- **Size:** ~1,000+ customer transactions
- **Key Features:**
  - Customer demographics (age, gender, subscription status)
  - Purchase details (item purchased, amount, discount applied)
  - Shipping type, previous purchases, and review ratings

---

## 🧰 Tools & Technologies
| Task | Tool/Technology |
|------|------------------|
| Data Loading & EDA | Python (Pandas, NumPy, Matplotlib, Seaborn) |
| Data Cleaning | Python |
| SQL Analysis | MySQL |
| Dashboard Building | Power BI |
| Report Creation | MS Word / PDF |
| Presentation | Gamma App |

---

## 🔍 Project Steps

### 1. Data Loading
- Imported dataset into Python using **Pandas**.
- Displayed initial rows, checked nulls, data types, and structure.

### 2. Exploratory Data Analysis (EDA)
- Analyzed distributions, correlations, and spending trends.
- Visualized insights using **Matplotlib** and **Seaborn**.

### 3. Data Cleaning
- Handled missing values, duplicates, and outliers.
- Standardized column formats for SQL integration.

### 4. SQL Querying in MySQL
- Created a database `shopping_db` and user access for analysis.
- Ran queries to answer key business questions like:
  - Revenue by gender
  - Impact of discounts
  - Top products by rating
  - Comparison between shipping types
  - Customer segmentation (New, Returning, Loyal)
- SQL file: [`customer_behavior_sql_queries.sql`](./customer_behavior_sql_queries.sql)

### 5. Power BI Dashboard
- Built an interactive dashboard using **customer_behaviour_analysis.pbix**.
- Highlights:
  - Gender-based spending comparison
  - Revenue by category and age group
  - Discount usage impact
  - Subscription insights

### 6. Reporting & Presentation
- Created a concise report summarizing findings and recommendations.
- Designed a **Gamma presentation** for stakeholders to visualize insights clearly and interactively.

---

## 📊 Dashboard Preview
**File:** `customer_behaviour_analysis.pbix`  
Includes:
- KPI Cards (Total Revenue, Avg Purchase, Top Products)
- Dynamic Filters (Gender, Age Group, Category)
- Visuals (Bar, Pie, Line charts)

---

## 📈 Results
- Identified top-spending customer segments.
- Found discount patterns linked to higher retention.
- Highlighted top-rated and most-purchased products.
- Delivered data-driven insights for improving marketing and sales strategies.

---

## ⚙️ How to Run

### 🔸 Prerequisites
- Python 3.x
- MySQL Server
- Power BI Desktop
- Gamma (for presentation)

### 🔸 Steps
1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/customer-shopping-behaviour-analysis.git
   cd customer-shopping-behaviour-analysis
   ```
2. **Run Jupyter Notebook** (`Customer_Shopping_Behaviour_Analysis.ipynb`)
   ```bash
   jupyter notebook
   ```
3. **Load SQL Queries**
   - Import `customer_behavior_sql_queries.sql` into MySQL.
4. **Open Power BI File**
   - Launch `customer_behaviour_analysis.pbix` for visual insights.
5. **View Report & Gamma Presentation**
   - Access summary and final presentation in `/reports` or Gamma link.

---

## 📬 Contact
**Author:** Alka K S  
**Role:** Data Analyst Intern  
**Email:** [alkaks3995@gmail.com](mailto:alkaks3995@gmail.com)  
**LinkedIn:** [www.linkedin.com/in/alka-k-s](https://www.linkedin.com/in/alka-k-s)
