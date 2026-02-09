# 🍎 Apple Retail Sales Analysis

  ![Dashboard Preview](Apple-Retail-Sales-SQL-Project%20(1).png)

---







## 📌 Project Overview


This project analyzes Apple Retail Store Sales and Warranty Data using SQL to uncover insights related to sales performance, product trends, warranty behavior, and store efficiency across multiple countries.

The analysis focuses on store performance, product categories, customer demand, warranty risks, and life-cycle behavior using structured queries on a relational database.

**Dataset Scope:**
The analysis is performed on a dataset containing over 1 million rows of data, organized across 5 relational tables with 25+ columns covering stores, products, categories, sales transactions, and warranty claims.

---


## 🛠️ Tools & Technologies

Database: PostgreSQL

Language: SQL

Analysis Areas: Sales, Stores, Products, Warranty Claims

---


## 🗂️ Database Schema




![Dashboard Preview](Schema.png)

**The project is built on five core tables:**

### 1️⃣ stores


💠 Stores information for Apple retail locations.

● **store_id** – Unique store identifier

● **store_name** – Store name

● **city** – City

● **country** – Country

### 2️⃣ category

💠 Product category details.

● **category_id** – Unique category ID

● **category_name** – Category name

### 3️⃣ products


💠 Apple product details.

● **product_id** – Unique product ID

● **product_name** – Product name

● **category_id** – References category

● **launch_date** – Product launch date

● **price** – Product price

### 4️⃣ sales


💠 Sales transaction data.

● **sale_id** – Unique sale ID

● **sale_date** – Date of sale

● **store_id** – References stores

● **product_id** – References products

● **quantity** – Units sold

### 5️⃣ warranty

💠 Warranty claim records.

● **claim_id** – Unique claim ID

● **claim_date** – Date of claim

● **sale_id** – References sales

● **repair_status** – Claim status (complete, pending, rejected, etc.)

---


## 📊 Key Business Insights & Results


| Question                                       | Result                                                                     |
| ---------------------------------------------- | -------------------------------------------------------------------------- |
| **Total stores per country**                   | USA leads with **15** stores, followed by Australia & China (**7** each).  |
| **Top unit-selling store (all-time)**          | **ST-56 Apple Southland** – **77,795** units sold.                         |
| **December 2023 sales performance**            | **18,076** transactions totaling **99,631** units.                         |
| **Stores with ZERO warranty claims**           | **0** – every store has at least one claim.                                |
| **Warranty completion rate**                   | Only **24.89%** of claims reach *Completed* status.                        |
| **Best performing store in 2023 (units)**      | **ST-14 Apple The Americana** – **164,617** units.                         |
| **Unique products sold in 2023**               | **89** different product models.                                           |
| **Highest avg. price category**                | Tablet – **$1,479.5**                                                      |
| **Lowest avg. price category**                 | Smart Speaker – **$734.1**                                                 |
| **Early-life failures (≤180 days)**            | **5,733** warranty claims within first 6 months.                           |
| **Countries with highest claim risk**          | Austria (**0.59%**), Netherlands (**0.56%**), Taiwan (**0.54%**).          |
| **Hottest USA sales months (last 3 yrs)**      | **22** months exceeded **5,000** units; peak **20,051** units in Mar-2024. |
| **Most problematic category (2024)**           | Accessories – **4,650** open claims.                                       |
| **Product life-cycle split (AirPods 2nd Gen)** | **66%** of sales (**44,681 units**) occur after 18+ months.                |


---

## 🔍 Analysis Highlights



⁘  The USA dominates retail presence and sales volume, reinforcing its role as the primary revenue market.

⁘  Warranty claims are widespread, with no store operating claim-free.

⁘  A low warranty completion rate (24.89%) highlights operational or process gaps.

⁘  Accessories show the highest risk in 2024 due to unresolved claims.

⁘  Long product life cycles (e.g., AirPods 2nd Gen) prove sustained customer demand well beyond launch.

---


## 📈 Project Objectives


»  Evaluate store-level and country-level sales performance

»  Identify top-selling stores and products

»  Analyze warranty behavior and risk exposure

»  Understand product life-cycle patterns

»  Support data-driven retail and warranty strategy decisions

---


## 🚀 Conclusion


This SQL project demonstrates how structured retail data can be transformed into actionable business insights. By combining sales trends, warranty analysis, and product life-cycle evaluation, the project highlights critical areas for performance optimization and risk management in Apple retail operations.

---


## 🤝 Connect

If you like this project or want to collaborate, feel free to connect!

📌 LinkedIn:  [LinkedIn](https://www.linkedin.com/in/iampravinchavan/) 

