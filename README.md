# 🏥 Healthcare Data Analysis with Power BI

This project presents a comprehensive Power BI dashboard analyzing patient-level healthcare data. The goal is to derive meaningful insights about patient demographics, medical conditions, treatment patterns, financials, and operational metrics using real-world-style hospital data.

---

## 📌 Project Objective

To explore and visualize healthcare data to answer business-relevant questions such as:

- Which medical conditions are most common by age group and gender?
- How do different admission types (Emergency, Elective, etc.) impact billing and stay duration?
- Which doctors, medications, and hospitals are associated with higher patient turnover or costs?
- What billing trends exist across insurance providers and medical conditions?

This analysis aims to help healthcare managers, analysts, and hospital administrators improve decision-making, patient care, and cost management.

---

## 🗃 Dataset Summary

- **Source**: Synthetic hospital data (Educational Use)
- **Records**: ~1,000+ patient entries
- **Timeframe**: 2019
- **Location**: Houston Methodist Hospital (fictionalized)

### 🔍 Key Columns

| Category          | Fields |
|-------------------|--------|
| Patient Info      | Patient ID, Age, Gender, Blood Type |
| Medical Details   | Medical Condition, Medications, Test Results, Doctor |
| Operational Info  | Admission Type, Room Number, Date of Admission/Discharge |
| Financial         | Billing Amount, Insurance Provider |
| Geographic        | Hospital Name, Latitude, Longitude |

> 📎 See the `Data Dictionary` tab in the Excel file for detailed descriptions.

---

## 📊 Dashboard Features

Built using **Power BI**, the interactive dashboard provides:

- **Summary Cards**: Total Patients, Average Billing, Average Length of Stay
- **Filters & Slicers**: Age group, Gender, Admission Type, Insurance Provider
- **Visuals**:
  - Bar charts of top medical conditions
  - Line charts tracking billing trends over time
  - Heatmaps of room usage or patient density by department
  - Pie charts showing distribution by gender, blood type, or admission method

---

## ⚙ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Power BI** | Data cleaning, modeling, DAX measures, visual design |
| **Excel** | Source data preparation & validation |
| *(Optional)* Python (pandas) | Future scalability for preprocessing |

---

## 📂 Project Structure

```text
📁 Healthcare-Analysis-PowerBI
│
├── 📊 Healthcare Analysis Dataset.xlsx         # Raw data + data dictionary
├── 📁 screenshots/
│   ├── dashboard1.png
│   └── dashboard2.png
├── 📈 Healthcare Dashboard.pbix                # Power BI report file (optional)
└── 📄 README.md                                 # This file
