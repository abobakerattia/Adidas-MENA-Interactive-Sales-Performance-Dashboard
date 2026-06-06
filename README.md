# Adidas MENA Interactive Sales Performance Dashboard

A comprehensive, multi-dimensional business intelligence dashboard engineered in Microsoft Excel to analyze retail and e-commerce transactional data for Adidas. This solution converts complex sales data into real-time, interactive insights covering regional revenue, profit optimization, category demand, discount distribution, and customer demographics across core Middle East and North Africa (MENA) markets.

**Developed by:** Aboubakr Attia (Data Analyst)

## 📊 DashBoard overview

<img width="1756" height="587" alt="Capture" src="https://github.com/user-attachments/assets/69d0caca-a2e9-4a68-838c-5cc6bc8354e2" />

---

<img width="1767" height="584" alt="Capture2" src="https://github.com/user-attachments/assets/152a622f-2baf-4446-8b73-e8bcd014b7ec" />

---

## 📊 Core Architecture & Tracked Metrics

The system utilizes an integrated data model to synthesize operational metrics, allowing stakeholders to drill down from high-level corporate KPIs to itemized product performance instantly:
* **Gross Revenue (Sum of Sales):** Tracked dynamically across multi-year cycles, individual months, and specific product categories.
* **Profitability Mapping (Sum of Profit):** Evaluated alongside sales charts to monitor margin health and operational efficiency.
* **Promotional Impact (Sum of Discount):** Isolated by country, consumer gender profile, and product line to study discount elasticity.
* **Volume Metrics:** Monitored via distinct order volumes (Count of Order_ID) and individual product identification codes (Count of SKU).

---

## 🛠️ Interactive Features & Slicer Matrix

The dashboard layout features an advanced cross-filtering system that dynamically recalculates all charts across two separate analysis screens:

### 1. Chronological Slicers (Left Panel)
* **Years:** Offers fast filtering across multi-year strategic periods (**2023, 2024, 2025**).
* **Months:** Complete calendar breakdown from **Jan to Dec** for micro-trend tracking.

### 2. Market Segmentation Slicers (Right Panel)
* **Geographical Region:** Targeted localization filtering for key MENA territories: **Egypt, Iraq, Kingdom of Saudi Arabia (KSA), Lebanon, and Oman**.
* **Payment Gateways:** Granular tracking of modern financial channels including **Apple Pay, Cash, Credit Card, Debit Card, Google Pay, NetBanking, PayPal, and UPI**.
* **Category Focus:** Main product sectors broken into **Accessories, Apparel, and Footwear**.

### 3. SKU Filter Ribbon (Bottom Panel)
* Full horizontal cross-filtering capability for specific product lines, such as **Adicolor Hoodies, Adilette Slides, Copa Sense, Essentials, Gym Bag, NMD_R1, Stan Smith, Superstar, and Ultraboost 22**.

---

## 📈 Dashboard Layout & Visual Analytics

### Screen 1 View (As shown in Capture_2.JPG)
Focuses heavily on volume metrics, geographic layouts, and margin analysis:
* **Sum of Sales and Profit Timeline:** A clustered vertical bar chart contrasting total incoming sales against true net profit by category and fiscal year.
* **Gender By Discount:** A column chart breaking down promotional discount distributions between *Female, Male, and Other* demographic groups.
* **Region by Discount:** A ranking bar chart identifying which local countries are consuming promotional margins.
* **Geospatial Map Visualization:** An integrated world map chart displaying regional sales distribution across the Middle East.
* **Category Breakdown Donut:** A central donut model tracking order share distribution by product categories.

### Screen 2 View (As shown in Capture2_2.JPG)
Focuses on chronological trends, transaction methods, and detailed demographic behaviors:
* **TTL Sales Continuous Line Chart:** A continuous tracking timeline that visualizes seasonal spikes, lows, and macro trends month-by-month from 2023 through 2025.
* **TTL Sales and Discount Stacked Matrix:** Combines revenue and discount variables grouped simultaneously by category and gender profiles.
* **Total Sales By Category:** A deep purple concentric ring donut chart plotting structural market share percentages.

---

## 🚀 Technical Stack Used

* **Analytics Platform:** Microsoft Excel (Advanced Architecture)
* **Data Transformation:** Power Query (ETL pipeline for structuring raw transactional logs)
* **Modeling Logic:** Power Pivot & DAX expressions for creating calculated fields and KPI metrics
* **UI/UX Custom Design:** Unified thematic palette, functional dashboard navigation banners, and scannable interactive slicing tiles.

---
*Disclaimer: This project was built as a data analytics portfolio piece to demonstrate proficiency in retail business intelligence, corporate dashboard layout optimization, and multi-variable data modeling.*
