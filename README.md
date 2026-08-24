# 🛍️ Retail Store Analytics Power BI Dashboard

An interactive, multi-page Power BI dashboard engineered to analyze retail sales performance, customer purchasing behavior, and category insights. Built with custom DAX calculations, structured data modeling, and modern UI styling.

---

## 📊 Executive Summary & Key Highlights

This project translates raw retail transactional data into actionable business intelligence. The interactive report enables stakeholders to track revenue trends, evaluate product performance, and uncover strategic growth opportunities across locations.

* **File Type:** Power BI Template (`.pbit`) / Power BI Project (`.pbip`)
* **Theme & UI:** Custom Fluent UI palette with standardized layouts
* **Reporting:** 3 dedicated report pages for executive, tactical, and deep-dive analytics

---

## 📁 Repository Structure

```text
├── DAXQueries/            # Custom DAX queries and measure definitions
├── Report/
│   ├── definition/
│   │   └── pages/         # Page layouts & visual configurations (Page 1 - 3)
│   └── StaticResources/   # Theme configs and registered visual assets
├── Retail_PBI.pbit        # Power BI project template file
└── README.md              # Project documentation

📈 Dashboard Architecture
Page 1: Executive KPI Overview
Key Metrics: High-level overview of total sales revenue, order volumes, average order value (AOV), and profit margins.

Trend Analysis: Time-series performance tracking key metrics across monthly and quarterly intervals.

Page 2: Category & Product Performance
Product Segmentation: Visual breakdown of sales by product categories and SKU performance.

Comparative Insights: Visual analysis comparing revenue generation vs. product margins.

Page 3: Transactional & Detailed Deep Dive
Granular Tables: Filterable tabular view for operational analysis and transaction-level auditing.

Diagnostic Analytics: Dynamic slicers and drill-through features to isolate specific regional or date-based trends.

Technical Details
Data Modeling: Multi-table relational model optimized using Star Schema principles (DataModelSchema).

DAX Formulas: Dynamic calculations for time intelligence (YoY growth, cumulative sales) and context-aware KPI cards stored in DAXQueries/.

.....
```
## Team Contributions:- 
# TNS INDIA FOUNDATION (C@TC PROGRAM)
* Jitesh Janardan Kalekar (UID:- T140200807)
├── Acquired Dataset and Cleaned the Dataset
* Pranav Vijay Kadam (UID:- T140200808)
├── Created Relationships between the datasets and Formulated DAX measures
* Omkar Pandharinath Umawane (UID:- T140200809)
├── Created Interactive and Clean Dashboard

