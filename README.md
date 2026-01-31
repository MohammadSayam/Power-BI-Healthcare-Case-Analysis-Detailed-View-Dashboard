# 📊 Power BI Healthcare Patient Waitlist Analysis Dashboard

## Project Overview  
This project is an interactive **Power BI dashboard** built to analyze **healthcare patient waitlist data** across multiple dimensions such as **date, case type, specialty, age profile, and time bands**.

The dashboard consists of two main views:
- **Summary View** – high-level KPIs and trends  
- **Detailed View** – drill-down operational analysis  

It helps healthcare stakeholders monitor **patient waiting patterns, workload distribution, and specialty-wise performance**.

---

## Objectives  
The main objectives of this project are:

- To track **overall patient waitlist volumes**
- To compare **latest month vs previous month performance**
- To analyze wait times by **case type and specialty**
- To understand patient distribution by **age groups**
- To monitor trends across **day case, inpatient, and outpatient cases**
- To enable **interactive filtering and drill-down analysis**

---

## Dashboard Views  

### 1. Summary View  
The **Summary Dashboard** provides a high-level overview of key metrics and trends.

Key components include:
- KPI cards showing:
  - **Latest month waitlist**
  - **Previous month waitlist**
- Donut chart:
  - **Average wait time by case type**
- Stacked bar chart:
  - **Average/Median wait time by Time Bands and Age Profile**
- Line charts:
  - **Monthly trend analysis for Day Case, Inpatient, and Outpatients**
- Specialty table:
  - **Average wait time by medical specialty**

This view is mainly used for **executive-level insights and performance monitoring**.

![Summary View](Screenshots/summary.png)

---

### 2. Detailed View  
The **Detailed View Dashboard** allows users to perform deep operational analysis using a hierarchical matrix.

Key features:
- Interactive filters:
  - **Archive Date (Range Slider)**
  - **Case Type**
  - **Specialty Name**
  - **Age Profile**
  - **Time Bands**
- Hierarchical matrix:
  - Date → Specialty → Age Group → Time Band  
  - Displays **Day Case Count** and **Total Cases**
  - Expand/collapse for drill-down analysis

This view is mainly used for **analyst-level and operational decision-making**.

![Detailed View](Screenshots/detailed_view.png)

---

## Key Features  

- Fully interactive slicers for dynamic analysis  
- Multi-level drill-down hierarchy  
- KPI-based performance tracking  
- Trend analysis over time  
- Age-based and specialty-based segmentation  
- Clean and professional UI design  

---

## Business Use Cases  

This dashboard can be used for:

- Hospital management reporting  
- Patient flow monitoring  
- Identifying high waiting specialties  
- Resource and staff planning  
- Capacity and workload analysis  
- Strategic healthcare decision making  

---

## Tools & Technologies  

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Power Query (ETL)**
- Data modeling with relationships  
- Time intelligence calculations  
- Interactive visual analytics  

---

## Data Model  

The dataset includes the following key fields:

- `Archive_Date`  
- `Case_Type` (Day Case / Inpatient / Outpatient)  
- `Specialty_Name`  
- `Age_Profile` (0–15, 16–64, 65+)  
- `Time_Bands`  
- `Wait_List_Count`  
- `Average_Wait_Time`  
- `Median_Wait_Time`  

---

## Key Learnings  

Through this project, I gained practical experience in:

- Designing end-to-end analytical dashboards  
- Building executive and operational views  
- Writing optimized DAX measures  
- Implementing drill-down hierarchies  
- Applying healthcare analytics concepts  
- Creating data-driven business stories  

---

## Future Enhancements  

- Add forecast for patient waitlist  
- Include SLA breach indicators  
- Add hospital-level comparison  
- Implement Role-Level Security (RLS)  
- Publish to Power BI Service for web access  

---

## Author  

**Mohammad Sayam Fareez**  
Aspiring Data Analyst | Power BI Developer  
Electronics Engineering Graduate (2025)

---

## Repository Structure  

