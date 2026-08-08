# 🏦 RetailBank Data Warehouse & Analytics Portal

![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Power Query](https://img.shields.io/badge/Power_Query-5C2D91?style=for-the-badge&logo=microsoft&logoColor=white)
![Data Analytics](https://img.shields.io/badge/Data_Analytics-FF6F00?style=for-the-badge&logo=google-analytics&logoColor=white)

## 📌 Project Overview
The **RetailBank Analytics Portal** is a comprehensive Business Intelligence solution designed to provide a robust analytical foundation for understanding retail banking performance. Built using **SQL** for data extraction and **Microsoft Power BI** for visualization, this interactive dashboard transforms raw transaction logs into actionable executive insights.

### 🎯 Business Problem
Financial institutions generate massive volumes of transactional data daily. Without a structured Data Warehouse and clear visualization layer, it is impossible to accurately track merchant performance, understand customer loyalty, or monitor risk factors like transaction fraud.

### 💡 Objectives
- Extract and structure raw banking data using **SQL**.
- Develop a multi-page interactive dashboard for executive reporting.
- Calculate advanced financial KPIs using DAX.
- Monitor risk by isolating declined transactions and identifying fraud rates.
- Analyze consumer spending behavior across distinct merchant categories.

---

## 🖥️ Live Dashboard

View the interactive dashboard here:

[Open Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYTVlNmJiNTgtNTJmNS00NWNmLTgwZDItYzFkM2M2NzBkNDUxIiwidCI6IjJiYjZlNWJjLWMxMDktNDdmYi05NDMzLWMxYzZmNGZhMzNmZiIsImMiOjl9)

---

## 📊 Dashboard Pages & Features

The BI Dashboard is structured into four distinct analytical views:

<details>
<summary><b>1. Executive Overview</b></summary>
A high-level view of revenue, transaction volume, and overall business growth.
<br>

| Metric | Value |
| :--- | :--- |
| **Total Revenue** | $3.18M |
| **Total Transactions** | 50,000 |
| **Revenue Growth** | +18.12% |

> **Key Insight:** The "Home" category dominates the revenue mix at 39.32%.
</details>

<details>
<summary><b>2. Customer Analytics</b></summary>
Insights into customer value, loyalty tiers, spending behavior, and retention.
<br>

| Metric | Value |
| :--- | :--- |
| **Active Customers** | 1,000 |
| **Avg Customer Spend** | $3.18K |

> **Key Insight:** Female customers generated $1.66M in revenue, slightly outpacing male customers at $1.53M.
</details>

<details>
<summary><b>3. Merchant Analytics</b></summary>
Merchant contribution, category performance, and activity rankings.
<br>

| Metric | Value |
| :--- | :--- |
| **Active Merchants** | 400 |
| **Avg Merchant Revenue** | $7.96K |

> **Key Insight:** The highest-earning individual merchant ("fraud_Emmerich") contributed $198K in revenue.
</details>

<details>
<summary><b>4. Transaction Analysis</b></summary>
Detailed volume, timing, operational outcomes, and fraud monitoring.
<br>

| Metric | Value |
| :--- | :--- |
| **Avg Transaction Value** | $63.69 |
| **Fraud Rate** | 0.62% |

> **Key Insight:** Wednesday sees the highest weekly transaction revenue at $281.1K.
</details>

---

## ⚙️ Technical Architecture

### Data Extraction & SQL
- Utilized **SQL** queries to extract, join, and structure initial datasets from the relational database before passing them into the visualization layer.

### Data Modeling & Power Query
- Designed a **Star Schema** optimized for Power BI reporting.
- Utilized **Power Query** for further data cleansing, handling missing values, and standardizing categorical data (e.g., transaction statuses: approved, declined, refunded).

### DAX Measures
Advanced **DAX** formulas were created to establish dynamic KPIs, including:
- Period-over-Period Revenue Growth
- Fraud Rate Calculation
- Average Ticket Size & Average Daily Revenue

### UX/UI & Color Theme
- **Theme:** Enterprise Financial (Navy Blue, Soft Teal, Mint Green).
- **Navigation:** Implemented custom bookmarking and page navigation buttons for a seamless app-like user experience.
- **Slicers:** Interactive filtering by Category, Month, Channel, Loyalty Tier, Gender, and Transaction Status.

---

## 🚀 Business Value
This BI solution allows stakeholders to move away from static spreadsheets and independently discover trends. By providing a clear line of sight into the **0.62% fraud rate** and identifying top-performing merchant categories, the bank can reallocate resources to high-yield partnerships and tighten security protocols where necessary.

---

## 🛠️ Technologies Used

| Category | Technology | Purpose |
| :--- | :--- | :--- |
| **Database** | SQL | Database Querying & Data Extraction |
| **BI Tool** | Microsoft Power BI | Data Visualization, Dashboard Design |
| **ETL** | Power Query | Data Cleaning & Transformations |
| **Calculations** | DAX | Data Analysis Expressions for Measures |
| **Architecture** | Data Modeling | Star Schema Architecture |

---

*Author: Mohamed Samir Hamed Mohamed Ramadan Gadallah*
