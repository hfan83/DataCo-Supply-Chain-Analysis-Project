# 🏬 Retail Smart Supply Chain Analysis & BI Dashboards

**Tagline:**  
*An end-to-end data analytics project leveraging Power BI, Python, and Tableau to analyze business performance, delivery issues, and customer segments for a large-scale retail chain.*

---

## 📌 Project Overview

This project provides a comprehensive view of a large multi-national retail dataset, combining data cleaning, machine learning, and interactive dashboards. The primary goal is to uncover actionable insights that can drive strategic decisions around business growth, logistics optimization, and customer retention.

---

## 📊 Tools & Tech Stack

- 🖥️ **Power BI:** Data cleaning, modeling, and main dashboards  
- 🐍 **Python (Pandas, Scikit-learn):** RFM analysis & customer segmentation using KMeans  
- 📊 **Tableau:** Executive & delivery performance dashboards for dynamic visual exploration  

---

## 💾 Dataset

- ~180,000 rows × 52 columns  
- Contains rich transaction-level data: orders, customers, products, shipping, financials
- Enables multi-angle analysis on:
  - Business performance (revenue, profit, costs)
  - Delivery efficiency (on-time vs late, shipping modes)
  - Customer shopping behavior & loyalty
- Data Source: [Kaggle - DataCo Smart Supply Chain](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis)
- Data modeling: ![DataCo RDM](https://github.com/user-attachments/assets/fc2abd52-dbf0-4ae1-b01b-3545d729fd1b)

---

## 📊 Interactive Dashboards
![1  Excutive Dashboard](https://github.com/user-attachments/assets/a4af18ab-3de9-4c63-896c-c8594ba144a3)
![2  Delivery Performance Dashboard](https://github.com/user-attachments/assets/7e19124c-6b34-49df-ada1-aa5f98244e4c)
![3  RFM Analysis Dashboard](https://github.com/user-attachments/assets/8d960aba-da66-4e2c-b471-09afb19a16bb)


### 🚀 Links to dashboards
- **📈 Tableau Dashboard:**  
  [View on Tableau Public](https://public.tableau.com/app/profile/truonghuyphan.da/viz/TABLEAU-DataCoDashboard/EXCUTIVEdashboard) or file: Project/blob/main/TABLEAU%20-%20DataCo%20Dashboard.twbx 
- **📈 Power BI Dashboard**
  
### 📸 Dashboard previews
_Add images like this after uploading screenshots:_

![Executive Dashboard](images/executive_dashboard.png)
![Delivery Dashboard](images/delivery_dashboard.png)
![Customer Segmentation](images/customer_segmentation_dashboard.png)

---

## 🚀 Project Goals

✅ Build **three core dashboards** to deeply analyze the dataset across strategic dimensions:

1. **📈 Executive Dashboard:**  
   - Monitor overall sales, profits, costs, and top-performing regions/products.

2. **🚚 Delivery Performance Dashboard:**  
   - Analyze shipment delays, shipping class problems, and regional bottlenecks.

3. **👥 RFM Analysis Dashboard:**  
   - Use RFM scores & KMeans clustering to segment customers by loyalty and profitability.

---

## 📈 Project Workflow

### 🔨 Data Cleaning & Modeling
- Primarily performed in **Power BI**:  
  - Removed duplicates, handled nulls, ensured consistent data types.
  - Built data models & relationships for efficient aggregation.

### 🧮 Customer Segmentation
- Calculated **RFM metrics** (Recency, Frequency, Monetary) using **Python (Pandas)**.
- Applied **KMeans clustering** to group customers into actionable segments:  
  - Loyal, Potential, New, Churn.

### 📊 BI Dashboards
- Created multiple dashboards in **Power BI** & **Tableau** to visualize:
  - Business KPIs
  - Delivery service quality
  - Customer segmentation patterns

---

## 🔍 Key Insights & Findings

### 🏦 Business & Financial Overview
- **High cost structure:**  
  - Discounts ~11%, other costs ~81%, leaving **net profit margin ~8.3%**, quite low for retail.
- **Large scale operations:**  
  - >15,000 stores worldwide; USA has the largest store base (54.1%), but **Puerto Rico contributes the most revenue (>38.5%)**.
- **Regional revenue shares:**  
  - Asia-Pacific (33.2%) & Europe (31.9%) lead.
  - The USA has the highest absolute sales (~$5M) despite only 10.4% share by store count.
- **Growth trend:**  
  - Stable over time, but **2017 saw revenue & profit drop** due to Q4 slump, even as order volume rose by 4.6% → lower AOV.

---

### 🚚 Delivery Performance
- **Fulfillment high but timing poor:**  
  - 95.65% orders completed, yet **54.8% delivered late**, a critical issue.
- `First Class` nearly always late, doubles the risk; `Second Class` raises risk 1.55x.
- Even `Same Day` shipping sees high delays.
- Actual delivery times exceed expected across the board, e.g. `Second Class` ~2 days late on average.
- Late deliveries scale with order volume consistently across periods & regions.

---

### 👥 Customer Segmentation Insights
- **Low retention:**  
  - After first quarter, only **~33% of customers return**; long-term retention (>2 yrs) extremely low.
- **Pareto rule applies:**  
  - `Loyal (16.6%)` & `Potential (30.6%)` customers = ~47% base, driving ~80% profits.
- **New Customers:**  
  - ~37% of base, but only ~8% of value.
- **Churned:**  
  - Highest AOV & past profits before leaving, indicating they were once very valuable.
- **Discount strategy misaligned:**  
  - `Loyal` get fewer discounts yet high profits → should prioritize experience.
  - `Potential` get most discounts but underperform.
  - `Churned` still left despite heavy promotions → suggests need for product & service improvements.

---

## 💡 Recommendations

✅ **Fix delivery issues:**  
- Investigate `First Class` & `Second Class` delays; consider restructuring or pausing these shipping options.  
- Optimize warehouses, adjust realistic delivery promises, communicate ETA transparently.

✅ **Target geographic hot spots:**  
- East/North Africa & Health & Beauty categories exacerbate delays — prioritize improvements there.

✅ **Refine discount strategy:**  
- Personalize offers by customer segment to avoid wasted promo spend.  
- Focus on enhancing experience (not just price) for `Loyal` and `Churn` segments.

---


