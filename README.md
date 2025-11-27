<h1 align="center">🔍 Crime Trends & Demographics Dashboard Report</h1>

A comprehensive Power BI analysis of crime incidents across the United States (2020–2025), focusing on trends, demographics, offense types, victim characteristics, and incident distribution. This report transforms raw crime records into actionable insights using interactive dashboards, drill-downs, custom tooltips, and data modeling.

---

## 📑 Table of Contents
- [🔎 Project Overview](#overview)
- [🎯 Business Objectives](#business-objectives)
- [📂 Dataset Information](#dataset)
- [🛠 Tools & Techniques](#tools)
- [🧹 Data Cleaning & Processing](#cleaning)
- [📊 Dashboard Analysis](#analysis)
- [📌 Key Insights](#insights)
- [📸 Dashboard Preview](#screenshot)
- [👤 Author & Contact](#contact)

---

## <a id="overview"></a>🔎 Project Overview
This project analyzes U.S. crime data (2020–2025) to uncover patterns in:
- Crime frequency by year, quarter, and month  
- Victim demographics (age distribution, age categories, sex)  
- Crime types and their severity  
- Status categories and crime code groups  
- High-level KPIs such as total crime count and unique offense types  

The dashboard is fully interactive with drill-downs, slicers, advanced tooltip pages, and demographic segmentation.

---

## <a id="business-objectives"></a>🎯 Business Objectives
The purpose of this analysis is to:

- Identify crime patterns and seasonal fluctuations  
- Understand demographic vulnerabilities (age groups, sex distribution)  
- Compare crime code descriptions and high-incidence categories  
- Provide a visual crime intelligence layer for policy-makers, safety teams, and law enforcement  
- Showcase Power BI storytelling, modeling, and dashboard UX  

---

## <a id="dataset"></a>📂 Dataset Information
- **Source File:** `Crime_Data_from_2020_to_2025.csv`  
- **Period Covered:** January 2020 – April 2025  
- **Rows:** ~860K criminal incidents  
- **Fields:** Register number, Crime Codes, Victim Age, Victim Sex, Crime Code Description, Status, Time, Year/Quarter/Month  

---

## <a id="tools"></a>🛠 Tools & Techniques
- **Power BI Desktop** (Main Visualization Tool)
- **Data Modeling** (relationships, DAX for KPIs)
- **Custom Tooltip Pages**
- **Drill-down / Drill-through**
- **Slicers & Filters**
- **Dark Theme Dashboard UI**
- **KPI Cards & Donut Charts**
- **Clustered Bar & Column Visuals**
- **Age Distribution Histogram**

---

## <a id="cleaning"></a>🧹 Data Cleaning & Processing
- Removed duplicates and null victim age categories  
- Standardized victim sex labels (M, F, X, H, O)  
- Categorized age into groups: *Child, Young, Adult, Senior Citizen*  
- Extracted **Year**, **Quarter**, **Month** from date fields  
- Cleaned crime code descriptions for tooltip display  
- Mapped crime status (IC, AO, AA) for clear comparison  

---

## <a id="analysis"></a>📊 Dashboard Analysis
Major analyses performed:

### **1. Crime Volume Trends**
- Crime count by **year**, **quarter**, and **month**  
- Sharp decline in late 2024–2025 (possible reporting lag or seasonality)

### **2. Demographic Distribution**
- Victim Age Histogram with peak around **around 30–35 years**  
- Crime count by Victim Sex shows:  
  - **Male victims:** 403K  
  - **Female victims:** 358K  
  - **Other categories:** significantly smaller share  

### **3. Crime Code Breakdown (Donut Chart + Tooltip Page)**
- Main highlight: **Interactive tooltip page**  
- Hovering over each crime code reveals the **full description and offense list**  
- Allows deeper understanding despite numeric crime codes  

### **4. Status-wise Crime Segmentation**
- IC (In Custody) contributes the majority of crime records  
- AO (Adult Other) and AA (Adult Arrested) significantly smaller  

### **5. Age Category × Sex Crime Patterns**
- Adults show the highest crime involvement (both sexes)  
- Children and seniors show minimal case volumes  
- Females show relatively higher crime incidence in young age groups compared to other categories  

### **6. Crime Code Description Summary (Tooltip Page #2)**
- Battery & Assault offenses contribute the highest volume  
- Vandalism and Theft also show significant totals  
- Burglary-related crimes show moderate volume  

---

## <a id="insights"></a>📌 Key Insights
- 🔥 **860K total crime records analyzed**
- 🧾 **139 unique crime codes**
- 👥 **Male victims constitute the largest demographic (403K)**
- 👩 **Female victims close behind (358K)**
- 🎯 **Age 20–40 is the highest-risk segment**
- 🔄 **Crime volume peaked between 2021–2023 before declining**
- 📊 **IC status accounts for the largest share of crimes**
- 🟡 **Tooltip-based crime descriptions enhance clarity for numeric codes**

---

## <a id="screenshot"></a>📸 Dashboard Preview
**Dashboard**


<img width="1822" height="1007" alt="Image" src="https://github.com/user-attachments/assets/b07d935f-1893-4af5-85a9-a382fda3925c" />



**ToolTip**


<img width="1457" height="796" alt="Image" src="https://github.com/user-attachments/assets/d00b83bd-9057-4256-ac46-6e8d80c0f7d3" />


---

## <a id="contact"></a>👤 Author & Contact
👤 Author: Vaibhav Goyal<br>
📧 Email: vg.goyal611@gmail.com<br>
💼 [LinkedIn](https://www.linkedin.com/in/vaibhav-goyal-29b70a30/)<br>
🧑‍💻 [Portfolio](https://github.com/vggoyal611)<br>
🌐 [Website](https://vaibhav-goyal-7nkea52.gamma.site) 

---
