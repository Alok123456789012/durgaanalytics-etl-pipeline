# DurgaAnalytics – End-to-End Data Pipeline Project

## 📌 Overview
A simulation of a multi-tenant BI data pipeline with ETL, transformation, and Power BI dashboard, based on a 2-day capstone project.

---

## 📁 Files Included
- `campaign.csv` – Campaign data
- `targets.xlsx` – Regional targets
- `customers.json` – Customer metadata
- `load_and_merge.py` – ETL script using pandas
- `final_merged_data.csv` – Clean merged dataset
- `dashboard.pbix` – Power BI dashboard file (export this)

---

## 🛠️ How to Run
1. Install Python + pandas
2. Run `load_and_merge.py` to generate `final_merged_data.csv`
3. Open `dashboard.pbix` in Power BI Desktop

---

## 📊 Dashboard Includes
- CTR, Spend, ROI per tenant
- Conversion funnel
- Time-series of conversions
- Slicer for tenant filter
