# 📊 Power BI Healthcare Case Analysis – Detailed View Dashboard

## Project Overview  
This project is an interactive **Power BI dashboard** designed to analyze healthcare case data across multiple dimensions such as **date, case type, specialty, age profile, and time bands**.  

The dashboard provides a **detailed drill-down view** that helps stakeholders understand patient distribution, workload patterns, and performance trends over time.

---

## Objectives  
The main objectives of this project are:

- To analyze **day case volumes** over a selected time period  
- To identify trends across **medical specialties**  
- To understand case distribution by **age groups**  
- To measure patient flow using **time band segmentation**  
- To enable users to perform **interactive filtering and drill-down analysis**

---

## Key Features  

### 1. Interactive Filters  
The dashboard includes dynamic slicers for:
- **Archive Date (Range Slider)**
- **Case Type**
- **Specialty Name**
- **Age Profile**
- **Time Bands**

These filters allow users to customize the analysis in real time.

---

### 2. Hierarchical Matrix View  
The main visual is a **hierarchical matrix table** that shows:

- Date → Specialty → Age Group → Time Band  
- Displays both **Day Case Count** and **Total Cases**  
- Expand/collapse functionality for deep analysis  

---

### 3. Drill-Down Analysis  
Users can:
- Drill from **overall date level** to **specialty**
- Further drill into **age groups**
- Finally analyze **time-based patient distribution**

This enables multi-level operational insights.

---

## Dashboard Screenshots  

### Detailed View  
Interactive matrix with drill-down by Date, Specialty, Age Profile, and Time Bands.  
![Detailed View](Screenshots/detailed_view.png)

### Overview Dashboard  
High-level summary view with key filters and metrics.  
![Overview](Screenshots/overview.png)

---

## Business Use Cases  

This dashboard can be used for:

- Hospital operations monitoring  
- Resource and staff planning  
- Identifying high-load specialties  
- Understanding patient demographics  
- Performance reporting for management  

---

## Tools & Technologies  

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Power Query (ETL)**
- Data modeling with relationships  
- Interactive slicers and matrix visuals  

---

## Data Model  

The data model includes the following key fields:

- `Archive_Date`  
- `Case_Type`  
- `Specialty_Name`  
- `Age_Profile`  
- `Time_Bands`  
- `Day_Case`  
- `Total_Cases`  

---

## Key Learnings  

Through this project, I gained hands-on experience in:

- Designing professional dashboards  
- Creating hierarchical drill-down reports  
- Writing optimized DAX measures  
- Applying data modeling best practices  
- Building user-friendly analytical interfaces  

---

## Future Enhancements  

- Add KPI cards for quick summary  
- Include trend charts (line/area)  
- Implement role-level security (RLS)  
- Add forecasting using time intelligence  

---

## Author  

**Mohammad Sayam Fareez**  
Aspiring Data Analyst | Power BI Developer  
Electronics Engineering Graduate (2025)

---

## Repository Structure  

