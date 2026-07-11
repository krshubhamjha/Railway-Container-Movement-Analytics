# 🚆 Railway Container Movement & Logistics Performance Analytics

An end-to-end analytics project that transforms raw Indian Railway container movement data into actionable business insights using **Python** and **Power BI**. The solution provides journey-level and leg-level analytics to monitor logistics performance, route efficiency, and operational KPIs for data-driven decision-making.

---

## 📌 Business Problem

Railway container movement generates large volumes of operational data across multiple stations. However, analyzing journey performance, route efficiency, and container movement patterns from station-level events is challenging.

The objective of this project was to:

- Analyze end-to-end container movement across the railway network.
- Measure logistics and operational KPIs.
- Monitor route performance and journey efficiency.
- Identify slow routes and operational bottlenecks.
- Build an interactive Power BI dashboard for business users.

---

## 🛠 Tech Stack

- **Python**
  - Pandas
  - NumPy
  - Matplotlib

- **Power BI**
  - DAX
  - Power Query
  - Azure Maps

- **Analytics**
  - KPI Analysis
  - Logistics Analytics
  - Route Performance Analysis
  - Origin-Destination (OD) Analysis
  - Data Validation

---

## 📊 Project Workflow

### Data Preparation

- Cleaned and validated raw movement data
- Removed duplicate records
- Converted timestamp columns into datetime format
- Sorted movement events using journey sequence
- Normalized destination railway divisions
- Created journey-level and leg-level analytical datasets

---

### Data Modeling

Constructed analytical datasets including:

- Journey-Level Fact Table
- Origin-Destination Summary
- Leg-Level Movement Table

Calculated key metrics including:

- Journey Time
- Route Speed
- Intermediate Stations
- Origin-Destination Pairs

---

## 📈 Dashboard Features

### Executive Overview

- Total Containers
- Total OD Pairs
- Average Journey Time
- Average Intermediate Stations
- Top Destination
- Daily Movement Trend

### Route Performance

- Azure Map Visualization
- Route Speed Categories
- Leg-Level Movement Analysis
- Origin × Destination Matrix

---

## 📌 Key KPIs

| KPI | Value |
|------|-------|
| Total Containers | **27,039** |
| Total OD Pairs | **27,047** |
| Average Journey Time | **74.19 Hours** |
| Average Intermediate Stations | **28.47** |

---

## 📈 Business Insights

- Identified high-volume railway container routes.
- Measured average journey duration across the network.
- Evaluated route efficiency using speed analysis.
- Analyzed Origin-Destination movement patterns.
- Highlighted slow route segments requiring operational attention.
- Improved visibility into journey-level logistics performance through interactive dashboards.

---

## 📷 Dashboard Preview

> Add dashboard screenshots here.

Example:

```
images/dashboard_overview.png
images/route_analysis.png
```

---

## 📂 Repository Structure

```
Railway-Container-Movement-Analytics
│
├── dashboard/
│   └── Railway_Container_Movement.pbix
│
├── notebooks/
│   ├── 01_EDA.ipynb
│   └── 02_KPI_Verification.ipynb
│
├── reports/
│   └── Indian_Railway_Container_Movement_Report.pdf
│
├── images/
│   ├── dashboard_overview.png
│   └── route_analysis.png
│
├── requirements.txt
├── LICENSE
└── README.md
```

---

## 🚀 Business Questions Answered

- Which routes have the longest journey times?
- Which destination divisions handle the highest container volume?
- Which routes require operational improvements?
- How efficient are container movements across different railway divisions?
- What are the overall network logistics performance trends?

---

## 📄 Note

The original datasets are not included in this repository due to file size and/or licensing constraints. The notebooks, Power BI dashboard, and project report demonstrate the complete analytics workflow.

---

## 👤 Author

**Shubham Kumar**
