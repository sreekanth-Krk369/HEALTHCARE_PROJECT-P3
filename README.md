# HEALTHCARE_PROJECT-P3
A collection of my Power BI dashboards and data analytics projects
# 🏥 Fortis Healthcare Analytics Dashboard

## 📌 Project Overview

A real-world healthcare analytics project focused on transforming raw hospital data into **actionable insights** using **Power BI, SQL, Excel, and Azure Data Factory (ADF)**. This system is designed for **internal hospital stakeholders** to track doctor availability, patient behavior, and diagnosis patterns.

> 🎯 Objective: Enable hospital admins and decision-makers to enhance operational efficiency and patient satisfaction by analyzing data across **locations, specialties, and diagnosis trends**.

---

## 👤 Role: Data Analyst | Tools Used

- **SQL Server** – Data querying, cleaning, and modeling  
- **Power BI** – Interactive dashboards with DAX logic  
- **Excel** – Preliminary analysis, outlier detection  
- **Azure Data Factory (ADF)** – ETL pipelines for raw data ingestion  

---

## 🛠️ Data Modeling & Engineering

Built a **centralized semantic model** from raw hospital datasets:

- ✅ Joined `Patient`, `Provider`, `Location`, `Encounter`, `Diagnosis`, and `PCP` tables
- ✅ Ensured referential integrity across `Loc_ID`, `Prov_ID`, and `Unique_Patient_ID`
- ✅ Performed data cleaning:
  - Removed canceled encounters (`Enc_Status_c = 'Cancelled'`)
  - Converted `Birth_date` into age buckets
  - Removed null providers and invalid diagnosis codes
- ✅ Created calculated columns (e.g., `Patient Age`, `MoM% Visits`, `Visit Status Flag`)

---

## 📊 Key Dashboards

### 📍 Home Navigation Dashboard
- Quick links to Provider Analysis, Patient Trends, and Diagnosis Insights  

![Health care Report (1)_page-0001](https://github.com/user-attachments/assets/ceda5822-4a79-44d0-8501-80a687504ffc)



---

### 👩‍⚕️ Provider Analytics
- 🔝 Top 5% Providers by Visit Volume  
- 👨‍⚕️ Doctors by Specialty & Location  
- 🗺 Doctor Heatmap (Locations 2 & 10 overcrowded)
  
![Health care Report (1)_page-0002](https://github.com/user-attachments/assets/2d7c7fbc-baa7-4967-80f4-08ef6a29dce8)
cf9cea)


---

### 🧑‍⚕️ Patient Analytics
- 👥 Gender Distribution → **Female Patients: XX%** (Calculated in DAX)
- 📊 Age Buckets: <18, 18–35, 36–50, 51+  
- 📆 MoM% Change in Patient Visits  
- 📍 Location-wise Footfall Trends  
- 🎯 Youngest Age Group Diagnosed per ICD Code

![Health care Report (1)_page-0003](https://github.com/user-attachments/assets/b0faf8cd-d00b-4076-8dfb-0e44077b99ab)
![Health care Report (1)_page-0004](https://github.com/user-attachments/assets/fe3a468c-595b-43fb-8a65-be1b4dcce2c2)


---

### 💉 Diagnosis Trends
- 🔬 Most Frequent ICD-10 Codes
- 📍 Location-wise Top Diagnoses
- 🧠 Rare disease hotspots (Locations 1 & 8)

---

## 💼 Business Scenarios Tackled

### ⚠️ Uneven Doctor Load
> Problem: Locations 2 & 10 had high doctor density  
✅ Solution: Heatmap enabled HR to redistribute staff and fill underserved locations

### 📉 Seasonal Drop in Visits
> Problem: February & June showed unusually low footfall  
✅ Solution: Correlated visit drop with public holidays, led to better campaign planning

### 🧭 Rare Disease Mapping
> Problem: Locations 1 & 8 had spikes in rare conditions  
✅ Solution: Recommended deploying specialist doctors for those areas

---

## 📌 Traits Demonstrated

- 🔍 **Data Cleaning**: Structured messy EHR data with SQL + ADF  
- 🧠 **Analytical Thinking**: Linked diagnosis patterns with geographies and age groups  
- 📈 **Visualization**: Intuitive, drill-down Power BI reports for non-technical users  
- 🤝 **Collaboration**: Worked with clinical and IT teams to align data insights with business goals

---

## 🔮 Future Enhancements

- Integrate live hospital APIs for real-time dashboards  
- Predict patient footfall with time-series models  
- Automate alerts for doctor overbooking or underutilization

---

## 📫 Let’s Connect

I’m actively seeking full-time opportunities in **Data Analytics / Healthcare Analytics / Food & Health Tech** domains.

📧 Email: *[Your Email]*  
🔗 LinkedIn: *[Your LinkedIn]*

---
