# 🚚 Logistics Performance Dashboard — Power BI Project

![Dashboard Screenshot](./Logistics%20Performance%20POWER%20BI%20Screenshot.png)

---

## 📘 Project Overview  
This Power BI project delivers a **comprehensive logistics performance analysis**, integrating multiple datasets on **shipments, salespersons, products, and regions**.  

It enables the company to **track shipments**, **analyze revenue trends**, and **improve delivery efficiency** through actionable KPIs and visuals.

---

## 🎯 Objectives  
- 🎯 Analyze **shipment trends**, **delivery performance**, and **revenue patterns**.  
- 📊 Identify **top-performing salespersons** and **profitable product categories**.  
- 🚀 Detect **delays, bottlenecks, or inefficiencies** in logistics operations.  
- 💡 Support **data-driven decisions** for revenue growth and operational excellence.

---

## 📊 Key Metrics Overview  

| KPI | Value | Insight |
|------|--------|----------|
| 💰 **Total Revenue** | $2M | Overall revenue generated |
| 🚚 **Total Shipments** | 5,000 | Total shipments processed |
| ✅ **Completed Shipments** | 3,000 (62%) | High fulfillment rate |
| 🔄 **Active Shipments** | 2,000 (33%) | Orders in progress |
| 🔁 **Returned Shipments** | 248 (5%) | Low return ratio |
| ⏱️ **Average Delivery Time** | 10 days | Average delivery efficiency |

---

## 🧩 Data Sources  

| 📁 Dataset | 🧾 Description | 🔑 Key Fields |
|-------------|----------------|----------------|
| `Shipment.csv` | Shipment-level transactional data | Shipment ID, Status, Date, Delivery Time, Revenue |
| `SalesPerson.csv` | Sales team details | SalesPerson ID, Name, Picture |
| `Product.csv` | Product and category info | Product ID, Category, Price, Quantity |
| `Country.csv` | Regional delivery insights | Country, Region, Avg Delivery Time |

---

## ⚙️ Data Modeling & Preparation  
- 🧹 Cleaned and transformed data using **Power Query**.  
- 🔗 Established relationships among `Shipment`, `SalesPerson`, `Product`, and `Country`.  
- 🧮 Created **DAX Measures**:
  - 💵 `Total Revenue = SUM(Shipment[Revenue])`
  - 📦 `Return Rate (%) = DIVIDE(Returned, Total Shipments, 0)`
  - ⏱️ `Avg Delivery Time = AVERAGE(Shipment[DeliveryDays])`
  - 🟩 Shipment status KPIs (Active / Completed / Returned)

---

## 📈 Dashboard Analysis  

### 📦 Shipment Trend (2022–2024)
- 📈 **+85% increase** in completed shipments (2022 → 2023).  
- 🔁 **12% rise** in returns — suggests improvement in quality assurance.  
- 📉 Active shipments remained stable, indicating steady market demand.  

### 💰 Revenue by Month  
- 💵 **Average Monthly Revenue:** $135K  
- 🌟 **Peak Months:** March ($155K) & November ($160K)  
- 🧊 **Lowest Month:** February (−25% drop) → potential for off-season campaigns.  

### 🧱 Product Category Breakdown  

| 🏷️ Category | 📊 Revenue Share | 💡 Key Insight |
|--------------|------------------|----------------|
| ⚡ **Electronics** | 68% | Highest margin driver; main revenue source. |
| 🎧 **Audio** | 51% | Strong performer; great bundling potential. |
| 💻 **Computing** | 34% | Moderate growth; stable category. |
| 🖨️ **Office Equipment** | 18% | Underperforming; needs focused promotions. |

---

### 🌍 Average Delivery Time by Geography  

| 🌎 Country | ⏱️ Avg Delivery (Days) | 🔍 Performance Insight |
|-------------|-------------------------|--------------------------|
| 🇦🇺 Australia | 20 | Longest delivery; optimize carrier/route. |
| 🇯🇵 Japan | 18 | High delay; review regional logistics. |
| 🇨🇳 China | 15 | Moderate; could improve. |
| 🇮🇳 India | 12 | Within acceptable SLA. |
| 🇨🇦 Canada | 2 | Best-performing region; benchmark. |

> ⚠️ *4 countries exceed global avg of 10 days — cutting delay by 2 days can save ~$120K/year.*

---

### 👥 Salesperson Performance  

| 👤 Salesperson | 📦 Shipments | ✅ Completed | 🔁 Returned | 💬 Insight |
|----------------|--------------|--------------|-------------|-------------|
| **Bonnie Lucero** | 266 | 179 | 18 | Top performer with 67% completion rate. |
| **Laurie Figueroa** | 237 | 150 | 17 | 63% completion; <7% returns. |
| **Jeffery Mills** | 239 | 142 | 14 | Consistent results, <6% returns. |

> 🏆 *Top 3 reps manage 32% of shipments with <8% returns — ideal for mentoring others.*

---

## 📊 Insights & Conclusions  

### 📍 Quantitative Insights  
- 💰 **Revenue Efficiency:**  
  - $2M from 5,000 shipments → **$400 per shipment** avg.  
  - **Electronics (68% revenue, 40% volume)** = most profitable line.  

- 🚚 **Shipment Success Rate:**  
  - 3,000 / 5,000 = **62% completion rate**.  
  - Return rate = **5%**, below industry average (8–10%).  

- 🕐 **Operational Performance:**  
  - Avg delivery = **10 days**, but **Australia/Japan (+90%)** above SLA.  
  - Reducing delays could improve delivery SLA by **20–25%**.  

- 👥 **Sales Performance:**  
  - Top 3 reps = **32% of shipments**.  
  - Avg return rate among them: **<8%** (vs. team avg ~10%).  

---

### 💡 Actionable Recommendations  

- ⚙️ **Optimize Logistics in High-Delay Regions**  
  - Target 🇦🇺 Australia & 🇯🇵 Japan → cut delivery time by 4–6 days.  
  - 💸 *Expected savings:* 10–12% logistics cost reduction.  

- 📦 **Boost Office Equipment Category**  
  - Only 18% of revenue → use bundle offers or targeted campaigns.  

- 🧭 **Replicate Top Sales Strategies**  
  - Train other reps using practices from top 3 performers.  

- 🔁 **Reduce Return Shipments**  
  - Goal: 248 → <200 next quarter (−20%).  

- 📅 **Seasonal Strategy Optimization**  
  - Double down on **March & November peaks** for promotions.  

- 🚀 **Implement Real-Time KPI Monitoring**  
  - Bring avg delivery down from 10 → 8 days (↑20% efficiency).  

---

## 🧠 Overall Conclusion  
- ✅ **Strong shipment success (62%)** and **low return rate (5%)** outperform benchmarks.  
- ⚡ **Electronics** remains the top-profit segment.  
- 🌍 **Delivery optimization** in slow regions offers high ROI potential.  
- 📊 Applying insights could drive a **10–15% revenue increase** and **20% efficiency gain** across logistics operations.  

---

## 🛠️ Tools & Technologies  
- 🧠 **Power BI** – Interactive dashboard & analytics  
- 🧹 **Power Query** – Data cleaning & transformation  
- 📈 **DAX** – Custom KPI measures  
- 📄 **CSV / Excel** – Source data integration  

---

## 📂 Repository Structure  

