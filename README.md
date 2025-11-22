# Global Digital Behavior & Cyber Exposure Analysis (Excel Project)

This project explores how people across 44 countries engage with digital devices, internet services, streaming, gaming, and social media.  
The analysis was fully carried out in **Excel**, using **Power Query** for cleaning, **Power Pivot** for data modeling and measures, and **Pivot Tables/Charts** for building a KPI-driven interactive dashboard.

---

## 📂 Project Structure

```
excel-global-digital-behavior-exposure-analysis/
│
├── data/
│ ├── raw_dataset.csv
│ ├── cleaned_dataset.csv
│
├── excel_workbook/
│ └── Digital_Behavior_Dashboard.xlsx
│
└── report/
└── Global_Cyber_Exposure_and_Digital_Behavior_Index_Report.pdf
```

---

## 🧹 Data Preparation (Power Query)

The initial dataset contained inconsistencies in formatting, missing values, and mixed numeric/text fields.  
Using **Power Query**, the following transformations were applied:

- Standardized country names  
- Fixed numeric type issues  
- Cleaned percentage and time fields  
- Added a custom **Continent** column  
- Removed unused or redundant fields  
- Ensured clean, analysis-ready schema

The cleaned dataset was then loaded into **Power Pivot** for modeling.

---

## 🧠 Data Modeling (Power Pivot)

Several **calculated columns** and **DAX measures** were created to quantify digital behavior patterns:

### Key Calculated Columns
- **Mobile_Internet_Share**  
- **Computer_Internet_Share**  
- **SocialMedia_Time_Ratio**  
- **Gaming_Time_Ratio**  
- **Streaming_Time_Ratio**  
- **Podcast_Time_Ratio**  
- **MusicStreaming_Time_Ratio**

### Composite Indexes
- **DDI — Digital Dependency Index**  
- **CSI — Connectivity Structure Index**  
- **EPI — Engagement Penetration Index**  
- **ERS — Exposure Risk Score**

These composite metrics help capture deeper digital-behavior insights across countries and continents.

---

## 📊 KPI Set Used in Dashboard

The dashboard focuses on six primary KPIs:

1. **Average DDI by Continent**  
2. **Highest EPI (Engagement) per Continent**  
3. **Average CSI (Connectivity Strength)**  
4. **Average ERS (Exposure Risk)**  
5. **Max Gaming Time by Continent**  
6. **Highest Social Media Time Ratio**

Slicers were added for:
- Continent  
- Country  
- Selected Index

This makes the dashboard fully interactive and exploration-ready.

---

## 🔍 Key Insights (Highlights)

- **South America and Africa** show the **highest digital dependency (DDI)**.  
- **Asia** leads with the **highest global EPI value (83.12)**—showing strong entertainment and engagement usage.  
- **Europe and Oceania** demonstrate **strong connectivity (highest CSI)** driven by fast fixed internet speeds.  
- **Exposure Risk (ERS)** is noticeably higher in **Europe and Oceania**, driven by heavier streaming + gaming behavior.  
- **Africa** records the **highest gaming console time**, an unexpectedly strong entertainment indicator.  

These insights highlight how differently regions depend on and engage with digital ecosystems.

---

## 🖼️ Dashboard

The final Excel workbook contains:
- KPI cards  
- Slicer-driven navigation  
- Bar charts, line charts, and heatmaps  
- Composite index visuals  
- Clean and minimal layout designed for hiring managers

(You may add screenshots here.)

---

## 🛠️ Tools Used

- **Microsoft Excel**
- **Power Query**
- **Power Pivot**
- Pivot Tables & Pivot Charts
- DAX Measures

---

## 📑 Report

A full analytical PDF summarizing the methodology, KPIs, interpretations, and visual insights is included in the `report/` directory:

**Global_Cyber_Exposure_and_Digital_Behavior_Index_Report.pdf**

---

## 🚀 Purpose

This project demonstrates end-to-end **data analytics workflow in Excel**, covering:
- Data cleaning  
- Data modeling  
- Feature engineering  
- Index creation  
- KPI design  
- Dashboard building  
- Portfolio-level reporting  

Perfect for data analytics roles where Excel proficiency is highly valued.
