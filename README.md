<!-- ![GitHub stats](https://github-readme-stats.vercel.app/api?username=pratimaprasad17&show_icons=true) -->

<p align="center">
  <img width="250" height="60" alt="image" src="https://github.com/user-attachments/assets/0c354f0e-f383-4960-95fa-c31563139028" />    
</p>
<div align="center">
 
  # 🛒 Sales Analytics Dashboard 🛒
  
</div>

## ✨ What this project is about
This project is a complete end-to-end data analytics and business intelligence solution built to understand how a retail business actually performs not just at a high level, but across products, customers, employees and regions.

Using Walmart sales data, I designed a system that answers a simple but powerful question:

> **What is driving revenue, and where should the business focus next?**

From raw transactional data to interactive dashboards, every step of this project was built to simulate a real-world business intelligence workflow.

## 🧠 The Problem
Retail data is messy, layered, and interconnected.  
Sales don’t exist in isolation, they rather depend on:
- What products are being sold  
- Who is buying them  
- Which employees are selling  
- Where transactions are happening  
- How customers are paying  

The goal of this project was to perform **descriptive analysis** across all these dimensions and uncover patterns that can drive better decisions.
<!--
## 📊 What I built

A **6-page Power BI reporting system** that breaks down the business into clear, actionable layers:
-->
<div align="center">
  
## 📦 About the Data
</div>

This project is built on a transactional retail dataset sourced from the **Kaggle Walmart Sales Analysis Competition**.

At its core, the dataset captures the complete lifecycle of a sale, from product selection to final payment, across **different Walmart branches** 

Each row represents a **single sales transaction**, making the dataset ideal for both **granular analysis** and **aggregated business insights**.


### 🔹 For Data Analysts
The dataset is structured in a **flat transactional format** with **17 columns and ~1000 records**, making it suitable for:
- Exploratory Data Analysis (EDA)  
- KPI computation (Revenue, YoY growth, basket size)  
- Feature engineering (customer segments, product categories)  
- Time-series analysis (daily/monthly trends)  
- Dimensional modeling (can be extended into a star schema)

Key analytical opportunities:
- Revenue vs quantity trade-offs  
- Customer segmentation (type, gender, behavior)  
- Payment method distribution  
- Location-based performance analysis  


### 🔹 For Business Users
This dataset answers practical business questions such as:
- What products and categories are driving revenue?  
- Which customer segments spend more?  
- How does performance vary across locations?  
- What are the dominant payment behaviors?  
- When are peak sales periods?  

In simple terms, this data helps translate daily transactions into **business decisions**.

<div align="center">
  
## 📊 Data Dictionary
</div>

### 🧾 Core Transaction Fields
| Column | Description | Data Type |
|--------|------------|----------|
| `sale_id` | Unique identifier for each transaction | INT |
| `sale_reference` | Reference code for tracking the transaction | VARCHAR |
| `sale_date` | Date and time when the transaction occurred | DATETIME |
| `quantity` | Number of units sold in the transaction | INT |
| `method_of_payment` | Payment method used (Cash, Credit, Debit, Mobile) | VARCHAR |


### 🛍️ Product Information
| Column | Description | Data Type |
|--------|------------|----------|
| `product_id` | Unique identifier for the product | INT |
| `product_name` | Name of the product | VARCHAR |
| `price` | Price per unit of the product | DECIMAL |
| `department_id` | Identifier linking product to a department | INT |


### 🏬 Department Information
| Column | Description | Data Type |
|--------|------------|----------|
| `department_id` | Identifier linking product to a department | INT |
| `department_name` | Name of the department | VARCHAR |


### 👤 Customer Information
| Column | Description | Data Type |
|--------|------------|----------|
| `customer_id` | Unique identifier for each customer | INT |
| `name` | Name of the customer | VARCHAR |
| `email` | Customer email | VARCHAR |
| `gender` | Gender of the customer | VARCHAR |
| `state` | Customer address - state | VARCHAR |
| `town` | Customer address - town | VARCHAR |


### 👨‍💼 Employee Information
| Column | Description | Data Type |
|--------|------------|----------|
| `employee_id` | Unique identifier for each employee | INT |
| `name` | Name of the employee handling the transaction | VARCHAR |
| `email` | Employee email | VARCHAR |
| `department_id` | Department the employee belongs to | INT |


### 🌍 Location Data
| Column | Description | Data Type |
|--------|------------|----------|
| `state` | State where the transaction occurred | VARCHAR |
| `town` | Town or city of the transaction | VARCHAR |

---
<!--
## ⚙️ Data Characteristics & Design Notes

- 📌 **Granularity:** Transaction-level (1 row = 1 sale)  
- 📌 **Time Coverage:** Multi-year dataset enabling trend analysis  
- 📌 **Mixed Data Types:** Categorical + Numerical + Temporal  
- 📌 **Pre-calculated Fields:** Includes revenue, VAT, and profit-related columns  
- 📌 **Analytical Flexibility:** Can be easily transformed into:
  - Fact table → Sales  
  - Dimension tables → Customer, Product, Location  

---


## 🔍 Analytical Potential

This dataset enables multiple layers of analysis:

 📈 **Trend Analysis** → Revenue over time, seasonality  
 🛍️ **Product Insights** → Top-selling vs high-value items  
 🌍 **Geographical Insights** → Performance by city/state  
 👥 **Customer Behavior** → Segmentation and preferences  
 💳 **Payment Patterns** → Distribution across payment types  
 📊 **Operational Metrics** → Basket size, revenue per customer  

-->
### 💡 In One Line
This dataset transforms everyday retail transactions into a **multi-dimensional view of business performance**, bridging the gap between raw data and decision-making.

<div align="center">
 
  ## 🧾 Executive Dashboard  
</div>  

A quick snapshot of business health  
 💰 **Total Revenue:** 15.75M  
 🧾 **Transactions:** 20K  
 👥 **Customers:** 500  
 📦 **Quantity Sold:** 60K  
 🧮 **Avg Basket Value:** 787.47  
 📈 **YoY Growth:** 0.20  

This page answers: *“How is the business doing overall?”*

<img width="1476" height="847" alt="image" src="https://github.com/user-attachments/assets/d0fd31ef-77d1-410c-a7a2-7c7296328af7" />


---
<div align="center">
  
  ## 📈 Sales Trends Dashboard  
</div>

Understanding performance over time
- Rolling 12-month revenue trends  
- Monthly revenue + YoY growth comparison  
- Seasonal spikes and slowdowns  
- Revenue distribution by quarter  

This helps identify **growth patterns and demand cycles**

<img width="1477" height="835" alt="image" src="https://github.com/user-attachments/assets/92d7b6c0-2374-45a3-8cda-67eb313a2f22" />

---
<div align="center">
  
## 📦 Product Dashboard  
</div>  

What’s selling and what’s not
- Top products by revenue and quantity  
- Product performance across departments  
- Avg basket value per product  
- Fast-moving vs high-value items  

Example insight:  
Products like *Area Force* consistently lead in revenue contribution

<img width="1473" height="852" alt="image" src="https://github.com/user-attachments/assets/42d2253b-329c-4d4e-8ea5-17cdce5eb82e" />

---
<div align="center">
  
## 🌍 Geography Dashboard  
</div>

Where the business is strongest
- Revenue and quantity by state  
- Customer distribution across regions  
- Top-performing states and towns  
- Total coverage: **50 states, 13.17K towns**

This answers: *“Where should we expand or optimize?”*

<img width="1480" height="850" alt="image" src="https://github.com/user-attachments/assets/859d1163-7181-490c-973f-24cb6e5e5ccf" />

---
<div align="center">
  
## 👤 Customer Dashboard  
</div>

How customers behave
- Payment method preferences (cash, card, mobile)  
- Gender distribution  
- Active customers over time  
- Revenue per customer (31.50K avg)  

Shows **how customers interact with the business**

<img width="1477" height="852" alt="image" src="https://github.com/user-attachments/assets/df46502f-1723-4d85-a482-26c588a8c94f" />

---
<div align="center">
  
## 👨‍💼 Employee Dashboard  
</div>

Who is driving performance
- Employee revenue contribution  
- Department-wise performance  
- Top employee: **Jerry Martin (~1.08M revenue)**  
- Sales efficiency across teams  

This helps identify **top performers and optimization opportunities**

<img width="1477" height="847" alt="image" src="https://github.com/user-attachments/assets/dc66311e-b276-4f53-a683-e8ad1a32f825" />


## ⚙️ How it was built

### 1. Data Modeling
Structured relational data across:
- Sales  
- Products  
- Customers  
- Employees  
- Departments  

Defined relationships to enable cross-dimensional analysis


### 2. Data Processing (SQL)
Used SQL to:
- Clean and transform raw data  
- Create aggregated views  
- Calculate KPIs (revenue, YoY, averages)  
- Handle joins across multiple entities  


### 3. Power BI Development
Built dashboards with:
- DAX measures (KPIs, growth rates, averages)  
- Interactive slicers (Year, State, Gender)  
- Drill-down capability  
- Clean and structured layout  


### 4. Storytelling Layer
Every dashboard answers a specific business question:

| Dashboard | Question it answers |
|----------|--------------------|
| Executive | How are we performing overall? |
| Sales | Are we growing or declining? |
| Product | What should we sell more of? |
| Geography | Where are we strongest? |
| Customer | Who are our customers? |
| Employee | Who drives performance? |

<div align="center">
  
## 🛠️ Tech Stack
</div>

- **Database:** MySQL  
- **Analysis:** Excel, SQL (Joins, Aggregations, CTEs)  
- **Visualization:** Power BI  
- **Modeling:** Star schema + relational joins  
- **Metrics:** DAX  


<!--
## 📌 Key Insights

- Revenue is **evenly distributed across payment methods**, with slight dominance of cash and cards  
- Certain products consistently drive high revenue → strong candidates for promotion  
- Customer base is stable but shows **seasonal spikes**  
- Employee performance is relatively consistent → opportunity lies in **basket value growth**  
- Geography shows **clear high-performing states**, useful for expansion strategy  

---
-->
<!--
## 🎯 Why this project matters

This isn’t just a dashboard.

It’s a **decision-making tool**.

It shows how:
- Raw data becomes structured insight  
- Metrics become business signals  
- Dashboards become action  

---
-->
<div align="center">
  
## 📌 Key Findings & Insights
</div>

This analysis goes beyond reporting numbers — it uncovers patterns that directly impact business performance and decision-making.

### 💰 Revenue Performance & Trends
- The business generates a **strong overall revenue of ~15.75M**, with consistent transaction volume (~20K), indicating stable operational throughput.
- Revenue trends show **fluctuations over time rather than linear growth**, suggesting the presence of:
  - Seasonal demand cycles  
  - External market influences  
- Quarterly distribution remains relatively balanced, indicating **no over-dependence on a single sales period**.

📊 **What this means:**  
The business is stable, but growth is not optimized. There is an opportunity to **identify peak drivers and replicate them across slower periods**.

---

### 🛍️ Product & Department Insights
- A small group of products (e.g., *Area Force*) consistently drives **disproportionately high revenue**, indicating a **Pareto (80/20) pattern**.
- Departments such as **Sports & Outdoors and Clothing** lead revenue contribution, while others lag behind.
- Product performance reveals two clear segments:
  - **High-volume, low-value products** → drive quantity  
  - **Low-volume, high-value products** → drive revenue  

📊 **What this means:**  
The business can benefit from:
- Promoting top-performing products  
- Bundling high-volume + high-margin items  
- Re-evaluating underperforming categories  

---

### 👥 Customer Behavior & Value
- The customer base (~500 users) generates high average revenue (~31.5K per customer), indicating **strong per-customer value**.
- Gender distribution is nearly balanced, suggesting **no major demographic skew**.
- Customer activity shows **periodic spikes**, aligning with seasonal or promotional trends.

📊 **What this means:**  
- Focus should shift from acquisition → **retention and upselling**
- High-value customers can be targeted with **loyalty or premium offerings**

---

### 💳 Payment Behavior
- Revenue is **evenly distributed across payment methods** (cash, debit, credit, mobile), each contributing ~24–26%.
- No single dominant payment type indicates **diverse customer preferences**.

📊 **What this means:**  
- The business has strong flexibility in payment infrastructure  
- Opportunity exists to **promote digital payments** for faster and more trackable transactions  

---

### 🌍 Geographic Performance
- Sales are distributed across **50 states and 13K+ towns**, showing wide operational coverage.
- However, a few states contribute significantly higher revenue, forming **regional performance clusters**.

📊 **What this means:**  
- High-performing regions can be used as **benchmark markets**
- Low-performing regions present **expansion or optimization opportunities**

---

### 👨‍💼 Employee & Operational Efficiency
- Employee performance is relatively consistent, with top performers contributing slightly higher revenue (e.g., ~1M+).
- Department-level performance aligns closely with product demand rather than individual variation.

📊 **What this means:**  
- The system is operationally stable  
- Growth will come more from **strategy (products, pricing, demand)** than workforce changes  

---

### 📦 Basket Behavior & Transaction Patterns
- Average basket value (~787) indicates **moderate purchase size per transaction**.
- Quantity vs revenue analysis shows customers tend to:
  - Either buy **few expensive items**  
  - Or **multiple low-cost items**

📊 **What this means:**  
- Opportunity to increase basket size through:
  - Cross-selling  
  - Product bundling  
  - Smart recommendations  


<div align="center">
  
## 🎯 Final Takeaway
</div>

This analysis reveals a business that is **stable, diversified, and operationally consistent**, but with clear opportunities to:
- Increase revenue through **product strategy and bundling**
- Improve growth by **leveraging high-performing regions and products**
- Maximize customer value through **retention and upselling strategies**

## 🔮 What I would do next
<!--If this were a real business scenario: -->
- Add **forecasting models** for revenue prediction  
- Build **customer segmentation (RFM / clustering)**  
- Optimize **pricing and bundling strategies**  
- Automate pipeline for near real-time reporting  

---
<div align="center">
  
## 👋 About Me
</div>

I enjoy building data systems from scratch, taking messy data, structuring it, and turning it into something people can actually use.

This project reflects how I approach analytics:  clear thinking, structured data, and insights that make sense.

---

#### ⭐ If you liked this project

Feel free to star the repo or connect. I am always happy to talk data, dashboards or ideas.
