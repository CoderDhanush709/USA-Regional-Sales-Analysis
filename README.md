# 📊 USA Regional Sales Analytics & Executive Dashboard

An end-to-end business intelligence and sales performance project analyzing **64,000+ B2B transactions** totaling **$1.24 Billion in gross revenue** for Acme Co. across the United States. 

This project combines deep Exploratory Data Analysis (EDA) in **Python** with an interactive, 3-tier multi-page **Power BI Dashboard** to reveal regional market disparities, channel profitability, and seasonal purchasing cycles.

---

## 🖥️ Interactive Dashboard Showcase

### Page 1: Executive Overview & Macro Trends
> Tracks high-level business performance, monthly revenue rhythm, customer order spending distribution, and unit price vs. profit margin correlation.

![Executive Overview & Trends](executive_overview.png)

---

### Page 2: Product & Channel Performance
> Deep dives into revenue generators vs. margin drivers across sales channels (Wholesale, Distributor, Export) and highlights portfolio profitability.

![Product and Channel Performance](product_channel_performance.png)

---

### Page 3: Geographic & Customer Insights
> Breaks down regional volume vs. profitability (West, Midwest, South, Northeast), top-performing states, and enterprise client contributions.

![Geographic and Customer Insights](geographic_customer_insights.png)

---

## 📈 Key Performance Indicators (KPIs)

| Metric | Overall Value | Key Business Note |
| :--- | :--- | :--- |
| **Total Revenue** | **$1.24 Billion** | Generated across Wholesale, Distributor, and Export routes |
| **Total Gross Profit** | **$461.80 Million** | Represents a healthy aggregate profit baseline |
| **Profit Margin %** | **37.36%** | Stable margin maintained across diverse pricing tiers |
| **Total Order Count** | **64,000 Orders** | Distributed across 4 major US geographic regions |
| **Average Revenue per Order** | **$19.30K** | Large B2B average basket size |

---

## 💡 Core Business Insights

* **Channel Concentration vs. Margin Equivalence:**
  * **Wholesale** is the primary revenue driver, contributing **54.06% ($668.20M)** of gross sales and **53.56% ($247.35M)** of total profit.
  * **Distributor** generates **31.32% ($387.14M)**, while **Export** captures **14.61% ($180.63M)**.
  * All three channels maintain nearly identical profit margins (**Export: 38.01%**, **Distributor: 37.65%**, **Wholesale: 37.02%**), proving pricing discipline across distribution partners.
* **Geographic Market Disparities:**
  * **California dominates the country**, generating **$228.79M (19.5% of total sales)**—more than double the second largest state (Illinois at $111.05M).
  * Regionally, the **West ($372.1M, 30.1%)** and **South ($335.1M, 27.1%)** make up over **57%** of enterprise demand, while delivering consistent ~37.4% margins.
* **Product Portfolio Dynamics:**
  * **Revenue Champions:** `Product 26` ($120M) and `Product 25` ($110M) lead enterprise volume.
  * **Margin Champions:** `Product 9` (40.0%), `Product 30` (39.1%), and `Product 28` (38.9%) lead operating efficiency.
  * Scatter plot analysis reveals that profit margin is decoupled from unit price, demonstrating steady value-based pricing rather than margin erosion on expensive SKUs.
* **Seasonality & Demand Pulses:**
  * Sales volume experiences repeatable peaks in **May** and **September–December**, with a noticeable Q1 lull (hitting an annual trough in **February**).

---

## 🛠️ Tech Stack & Workflow

```text
  Data Ingestion         Data Cleaning & EDA          Data Modeling & DAX        Executive Delivery
┌─────────────────┐     ┌─────────────────────┐     ┌─────────────────────┐     ┌──────────────────┐
│  Excel Sheets   │ ──> │ Python (Pandas/     │ ──> │ Power BI Desktop    │ ──> │ Power BI Report  │
│ (Orders/Clients)│     │ NumPy/Seaborn)      │     │ (Star Schema / DAX) │     │ & PPT Pitch Deck │
└─────────────────┘     └─────────────────────┘     └─────────────────────┘     └──────────────────┘
