# 🌐 Global Supply Chain Risk & Financial Disruption Monitor

An interactive, corporate-grade Excel Dashboard designed to track, analyze, and mitigate supply chain vulnerabilities, delays, and associated financial penalties in real-time.

---

## 📊 Key Insights & Metrics Captured
* **Total Order Exposure:** ~$197.72M total volume monitored across global regions.
* **Total Loss / Financial Penalties:** ~$30.97M leakages tracked due to delivery anomalies.
* **Disrupted Shipments:** 20,000 affected shipments analyzed to isolate bottlenecks.
* **AVG Delayed Days:** Maintaining a baseline of 3.14 days across modes of transport.

---

## 🛠️ Features & Technical Implementation

### 1. Advanced Data Processing & ETL
* Cleaned and structuralized raw transactional logs into a highly optimized operational sheet (`raw_data`).
* Integrated a dynamic background computation layer (`Processing_sheet`) to feed isolated pivot tables without cluttering UI.

### 2. Interactive UI/UX Architecture
* Built on a custom **Royal Dark Metallic Theme** optimized for corporate presentations and dark-mode reporting.
* **Dynamic Slicers:** Connected `Global_Region` (APAC, EMEA, LATAM, NAM) and `Risk_Severity` (Critical Disruption, Minor Delay, On-Time) parameters across all analytical charts via multi-pivot report connections.

### 3. Data Visualization & Analytics Core
* **Vendor Risk Profile:** Dual-axis combined column/line chart showcasing *Total Penalty vs. Average Days Delayed* per logistics partner.
* **Material Disruption Breakdown:** Stacked volume charts isolating severe risks down to critical supply units (e.g., Semiconductors, Lithium-Ion Batteries).
* **Logistics Telemetry:** Horizontal bar charts analyzing shipment distribution and financial impacts across Air Cargo, Ocean Freight, Rail, and Road Express.

---

## ⚙️ How to Use This Project
1. Clone or download the `Global_Supply_Chain_Risk_Monitor.xlsx` file.
2. Open in Microsoft Excel (2019 or later recommended for full slicer compatibility).
3. Use the interactive slicers on the right panel to filter the entire supply chain telemetry by Region or Severity Level.


<img width="1882" height="697" alt="Screenshot 2026-07-16 152326" src="https://github.com/user-attachments/assets/6edd9adb-9819-40c0-abc8-9fcb0cba750c" />
