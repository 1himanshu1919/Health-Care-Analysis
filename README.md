# 🏥 Hospital Patient Analytics Dashboard

A Power BI report analyzing hospital patient data — covering demographics, billing, clinical outcomes, and admission trends — built to surface actionable insights for hospital administrators and analysts.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)

## 📊 Overview

This report (`HealthCare_Report.pbix`) is a 2-page interactive dashboard built in Power BI Desktop, designed to give a quick yet thorough view of patient volume, costs, clinical risk indicators, and operational trends across a hospital (or hospital network).

## 📁 Pages

### 1. HealthCare Report (Main Dashboard)
- **KPI Cards:** Total Patients, Abnormal Test %, Emergency Admissions, Total Billing Amount, Avg. Length of Stay
- **Filters (Slicers):** Gender, Medical Condition, Admission Type, Insurance Provider
- **Visuals:**
  - Patients by Medical Condition (Clustered Bar)
  - Patients by Gender (Donut)
  - Patient Trend over Time (Line)
  - Billing Amount by Medical Condition (Clustered Column)
  - Patients by Admission Type (Donut)
  - Patients by Test Results (Pie)
  - Patients by Age Group (Clustered Column)
  - Avg. Length of Stay by Medical Condition (Clustered Bar)
  - Patients by Insurance Provider (Clustered Bar)

### 2. Insights (Summary Page)
KPI cards plus four narrative insight panels:
- 👥 **Patient Insights** — age distribution, gender split, blood type spread
- 💰 **Billing Insights** — average billing, most/least expensive conditions, insurer cost comparison
- 🏥 **Clinical Insights** — abnormal test rate, stay duration by condition, most prescribed medication
- 📈 **Operations & Trends** — admission type breakdown, year-over-year admission trend, top insurer by volume

## 🔑 Key Findings
- Middle-aged patients (35–54) make up the largest segment (~29.6%)
- Gender distribution is nearly balanced (Female 50.05% / Male 49.95%)
- ~1 in 3 patients (33.56%) shows an abnormal test result
- Elective admissions are the most common admission type (33.61%)
- 2020 was the peak year for admissions; volumes have been stable since
- Cigna leads by patient volume among insurance providers

## 📂 Data
- **Source file:** `HealthCare_Report.pbix`
- **Granularity:** One row per patient encounter/admission
- **Key fields used:** Patient demographics (Age, Gender, Blood Type), Medical Condition, Admission Type, Admission/Discharge Dates, Doctor, Hospital, Insurance Provider, Billing Amount, Medication, Test Results

> ℹ️ If the underlying dataset is a public/sample dataset (e.g. a synthetic healthcare dataset), add a note and link to the original source here for attribution.

## 🛠️ Tools Used
- Power BI Desktop (data modeling, DAX measures, visualization)

## 🚀 How to Use
1. Download `HealthCare_Report.pbix` from this repo.
2. Open it in **Power BI Desktop** (free download from Microsoft).
3. Use the slicers on the main page to filter by Gender, Medical Condition, Admission Type, or Insurance Provider.
4. Explore the **Insights** page for a narrative summary of key takeaways.

## 📌 Notes
- This is a personal/portfolio analytics project intended to demonstrate dashboard design, DAX measures, and data storytelling in Power BI.
- All monetary figures are in ₹ (INR).

## 📜 License
Specify a license here (e.g. MIT) if you want others to freely reuse this report's structure/measures.

---
*Built with Power BI.*
