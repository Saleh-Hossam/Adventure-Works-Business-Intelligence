# 🚲 Adventure Works 360°: Profitability & Operational Audit

## Project Overview
This project delivers an end-to-end business intelligence analysis for a
manufacturing company to evaluate profitability, operational efficiency,
and product-level performance.

The dashboard connects sales, production, downtime, and returns data to
help decision-makers identify hidden losses and operational bottlenecks.

---

## Key Insights
- One product (Mountain-200) is responsible for a disproportionate share of return costs.
- Material shortages are the primary cause of production downtime.
- Operational inefficiencies directly impact gross profit margins.

---

## Business Context
This BI audit analyzes a manufacturing business generating approximately
$25M in revenue with a 42% gross profit margin. The goal is to bridge the
gap between strong sales performance and underlying operational issues.

**Critical Finding:**  
The Mountain-200 bicycle alone accounts for **$202K in returns** (26% of total
return value), indicating a serious quality or production issue.

---

## 📊 Dashboard Showcase

### 1. Executive Overview
*High-level profitability and performance monitoring with dynamic slicing.*
![Executive Dashboard](assets/exec-dashboard.gif)

### 2. Sales Performance Trends
*Time-intelligence analysis of revenue growth versus targets.*
![Sales Trends](assets/sales.gif)

### 3. Production Intelligence
*Analysis of 1,323 total downtime hours to identify efficiency bottlenecks.*
![Production Dashboard](assets/production.gif)

### 4. Quality Control & Returns
*Drill-through analysis revealing Mountain-200 as the main loss driver.*
![Returns Analysis](assets/returns.gif)

---

## 🧠 Analytical Approach

| Area | Approach |
| :--- | :--- |
| Profitability | Product-level margin and return cost analysis |
| Operations | Downtime tracking by cause and duration |
| Quality | Drill-through from category to SKU-level defects |
| Usability | Interactive dashboards with dynamic parameters |

---

## 🛠️ Technical Stack

### Data Modeling
Star Schema integrating four fact tables:
- **Fact_Sales** – Revenue and sales transactions
- **Fact_Production_Lots** – Manufacturing output and efficiency
- **Fact_Downtimes** – Machine stoppage duration
- **Fact_Complaints_Returns** – Defects and return costs

Connected through shared dimensions such as Products, Date, and Machines.

![Data Model](assets/model.png)

### Power BI Features
- Field Parameters for dynamic dimension switching
- Drill-through navigation from category to SKU
- Numeric parameters for Top-N analysis
- DAX measures for efficiency, profitability, and downtime metrics

---

## 📉 Business Impact
- Identified **$202K** in hidden product losses requiring immediate action.
- Isolated material shortages as the root cause of ~30% of downtime.
- Enabled targeted operational and quality audits to protect margins.

---

*Created by Saleh Hossam | Tools: Power BI, DAX, Power Query*
