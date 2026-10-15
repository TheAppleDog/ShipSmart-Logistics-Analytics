# 🚚 ShipSmart — Logistics & Delivery Intelligence

An end-to-end data analytics project that analyzes shipment performance, delivery reliability, shipping costs, and courier partner efficiency using Excel, SQL, and Power BI.

## 📌 Project Overview

ShipSmart explores how data analytics can help a logistics business monitor deliveries, identify delays, compare courier performance, and track operational KPIs.

The project uses simulated logistics data to demonstrate a complete analytics workflow, from data validation and SQL analysis to interactive dashboard development.

## 🎯 Business Objectives

- Monitor total shipment volume and delivery status.
- Measure the on-time delivery rate for completed shipments.
- Analyse average delivery time and shipping costs.
- Compare courier partners based on delivery performance.
- Track shipment trends over time.
- Build interactive dashboards to support data-driven decisions.

## 🛠️ Tools & Technologies

- **Microsoft Excel:** Data validation, formulas, KPI calculations, PivotTables, charts, and dashboard creation.
- **SQL (SQLite):** Data querying, aggregations, joins, and operational performance analysis.
- **Microsoft Power BI:** Data modelling, DAX measures, interactive visuals, slicers, and dashboard development.

## 📂 Dataset

The project contains three related datasets:

| Dataset | Records | Purpose |
|---|---:|---|
| Shipments | 1,000 | Shipment dates, delivery dates, status, costs, routes, and performance metrics |
| Customers | 100 | Customer information linked to shipments |
| DeliveryPartners | 5 | Courier partner details for performance comparisons |

**Important:** All records are simulated for educational and portfolio purposes. They do not represent actual company operations or verified real-world performance.

## 📊 Key Performance Indicators

The dashboard tracks the following KPIs:

- Total Shipments
- Completed On-Time Rate
- Average Delivery Days
- Total Shipping Cost
- Courier-wise On-Time Delivery Performance
- Monthly Shipment Trends
- Shipment Status Distribution

In the unfiltered dataset, the on-time rate is approximately **75.2%**, calculated as on-time completed shipments divided by all completed shipments. This calculation excludes pending or in-transit shipments.

The dashboard's KPI values may change when filters are applied.

## 🔍 Analysis Performed

### 1. Data Preparation — Excel
- Organised shipment, customer, and delivery partner data.
- Validated unique IDs and relationships between datasets.
- Calculated delivery days, delay days, and on-time status.
- Created KPI summaries, PivotTables, and charts.

### 2. SQL Analysis — SQLite
- Analysed shipment volumes and delivery status.
- Compared courier partner performance.
- Examined shipping costs and delivery trends.
- Used aggregations, conditional logic, and joins to answer business questions.

### 3. Interactive Dashboard — Power BI
- Created DAX measures for shipment volume and delivery performance.
- Built KPI cards and a monthly shipment trend visual.
- Compared courier partners using on-time delivery rates.
- Visualised shipment status distribution.
- Added slicers for exploring shipment data by month, shipping mode, and delivery partner.

## 💡 Key Observations

- The completed on-time delivery rate is approximately 75.2% in the unfiltered simulated dataset.
- Courier performance varies across the five delivery partners, making partner-level comparisons useful.
- Shipment status and monthly trends provide additional context for operational monitoring.
- Shipping cost analysis helps demonstrate how logistics expenses can be tracked alongside delivery performance.

These observations describe only the simulated dataset; they should not be interpreted as findings about a real logistics company.

## 📁 Repository Structure

```text
ShipSmart-Logistics-Analytics/
├── README.md
├── Shipments.csv
├── Customers.csv
├── DeliveryPartners.csv
├── ShipSmart_Import_SQLite.sql
├── ShipSmart_Analytics.xlsx
├── ShipSmart_Logistics_Analytics.pbix
└── ── excel-dashboard.png
    ── powerbi-dashboard.png
```

*Include only files that you actually upload. If you do not upload the Excel workbook or Power BI file, remove those entries from this list.*

## 🚀 How to Explore the Project

1. Review the CSV files to understand the dataset structure.
2. Open the SQL script in a compatible SQLite environment to inspect and run the analysis.
3. Open the Excel workbook to explore the calculations and dashboard.
4. Open the Power BI report in Power BI Desktop to interact with the visuals and slicers.

## 📚 Skills Demonstrated

Data Cleaning · Data Validation · Excel Formulas · PivotTables · SQL Queries · Joins · Aggregations · Data Modelling · DAX · KPI Tracking · Dashboard Design · Business Analysis · Data Visualization

## ⚠️ Limitations

- The dataset is simulated and does not represent real logistics operations.
- The analysis demonstrates analytical methods rather than validated business outcomes.
- Recommendations for a real business would require reliable operational data and additional context.

## 👩‍💻 Author

Created as a data analytics portfolio project to demonstrate practical skills in Excel, SQL, Power BI, and business performance analysis.
