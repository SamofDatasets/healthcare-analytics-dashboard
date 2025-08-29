# Velia Hospital Healthcare Analytics Dashboard

 <img width="1425" height="791" alt="Image" src="https://github.com/user-attachments/assets/90d964da-626a-4dc2-a65b-102633a9af95" />

 <img width="1426" height="795" alt="Image" src="https://github.com/user-attachments/assets/0907d232-07e9-4e1c-9e78-9858025ff46b" />

 [**View Live/Interactive Dashboard**](https://app.powerbi.com/view?r=eyJrIjoiMmU0NWI2ZjItNWZiYS00YmNmLTk1NDMtZWM5NWQwNDRmMTRkIiwidCI6IjljNmZkNWQ5LWMyMjgtNGIyMi1iZTljLTg5ZTk2NTgwZWRiMSJ9)

## 📌 Problem Statement  
Healthcare organizations generate vast amounts of data from patients, providers, diagnoses, and financial transactions.  
Velia Hospital seeks to **understand its finances, provider performance, and patient trends** in order to make **data-driven decisions** that improve operational efficiency, optimize revenue streams, and enhance patient care.  

This project provides a **comprehensive Power BI dashboard** that transforms raw hospital data into actionable insights through clear KPIs, interactive reports, and trend analysis.  

---

## 📊 Dataset Overview  
The dataset consists of **8 interconnected tables** representing different aspects of hospital operations:  

- **Visits** – Records of patient hospital visits (date, service type, referral source, etc.)  
- **Providers** – Information about healthcare providers (specialty, department, performance metrics).  
- **Procedures** – Details of medical procedures performed, linked with costs.  
- **Patients** – Demographic information such as age, gender, and race.  
- **Insurance** – Insurance provider details and coverage amounts.  
- **Diagnoses** – Records of medical diagnoses per visit.  
- **Departments** – Hospital departments (Cardiology, Pediatrics, etc.).  
- **Cities** – Geographic data (city, state) for location-based analysis.  

### 🔑 Key Columns (Highlights)  
- **Date** – Standardized date dimension (Year, Quarter, Month, WeekType, Weekday).  
- **Revenue** – Billing amount generated from services.  
- **Insurance Coverage** – Amount covered by insurance providers.  
- **Out-of-Pocket** – Patient’s self-paid expenses.  
- **Medication Cost, Room Charges, Treatment Cost** – Breakdown of hospital financial metrics.  
- **Diagnosis & Service Type** – Medical details used for patient and provider analysis.  
- **Referral Source** – How patients were referred (e.g., doctor referral, self, insurance).  

---

## ⚙️ Methodology  

1. **Data Preparation**  
   - Imported 8 hospital tables into Power BI.  
   - Performed **data cleaning & quality checks** to ensure consistency.  
   - Created relationships between tables for a proper star-schema model.  
   - Designed a **custom Date Table** with Year, Month, Quarter, WeekType, and Weekday.  

2. **Data Modeling & DAX Measures**  
   Defined KPIs using DAX, including:  
   - `Total Revenue` & `Average Billing Amount`  
   - `Insurance Coverage` & `Average Insurance`  
   - `Out-of-Pocket` & `Average Out-of-Pocket Cost`  
   - `Medication Cost`, `Room Charges`, `Treatment Cost` (Total & Average)  

3. **Dashboard Design**  
   - Created **2 dashboard pages** with clear themes visualizing;  
     - **Financial Overview** → Hospital’s financial health & revenue breakdown  
     - **Provider Insights** → Provider efficiency & department-level performance  
     - **Trend Analysis** → Patient visits, treatments, and billing trends over time  
     - **Additional Insights** → Insurance coverage patterns, diagnoses, service types  
   - Designed a **custom background layout** in PowerPoint with professional colors, icons, and shapes.  
   - Implemented **Light & Dark Mode themes** for better user experience.  

4. **Interactivity**  
   - Added a **dynamic filter pane** (by race, year, quarter, month, insurance, department, etc.).  
   - Filters apply globally across pages, ensuring cohesive storytelling.  
   - Drill-throughs and slicers for deeper analysis.  

---

## 📈 Key Visualizations  

- **Cards**: KPIs for revenue, insurance, out-of-pocket, and costs  
- **Clustered Bar Chart**: Revenue by city/state  
- **Stacked Charts**: Patients by referral source & insurance provider  
- **Department Analysis**: Insurance coverage by department & provider  
- **Diagnosis Trends**: Patients by diagnosis and service type  
- **Time-Series Analysis**: Revenue and visits over time (Year, Quarter, Month)  

---

## 🎨 Dashboard Features  

- **Clean, Professional Layout** → PowerPoint-designed backgrounds  
- **Light & Dark Mode Toggle**  
- **Dynamic Filters & Drilldowns**  
- **Comprehensive KPIs** at a glance  
- **Interactive & User-Friendly** storytelling visuals  

---

## 💡 Business Insights Uncovered

- **Overall Performance:** £3.4M hospital revenue with an average billing of £674.86 per patient; insurance (£2.2M) covers most costs, while out-of-pocket payments (£1.1M) remain significant.
- **Cost Drivers:** Treatment (£2.6M) and medication (£546K) are the largest expenses, while room charges (£180K) contribute minimally.
- **Geographic Insights:** Revenue is concentrated in Wales (£1.3M) and Northern Ireland (£1.05M), together driving nearly 70% of total hospital revenue.
- **Patient Insights:** 4,973 patients treated, with a balanced mix of emergency, self-referrals, and physician referrals; chronic conditions such as hypertension (54%) and asthma (41%) are major drivers.
- **Departmental Insights:** Cardiology (£570K), Orthopedics (£532K), and General Surgery (£523K) lead in insurance coverage, while Neurology (£317K) and Pediatrics (£283K) lag behind, highlighting potential growth areas.
---

## 🔗 Access Dashboard & Dataset

* [**Datasets(CSV)**](https://github.com/SamofDatasets/power-bi-bmw-car-sales-analytics/blob/main/01%20BMW_Sales_Data.csv)
* [**Power BI Dashboard (.pbix)**](https://github.com/SamofDatasets/power-bi-bmw-car-sales-analytics/blob/main/04%20BMW%20Car%20Sales%20Analytics.pbix)
* [**Live/Interactive Dashboard**](https://app.powerbi.com/view?r=eyJrIjoiMmU0NWI2ZjItNWZiYS00YmNmLTk1NDMtZWM5NWQwNDRmMTRkIiwidCI6IjljNmZkNWQ5LWMyMjgtNGIyMi1iZTljLTg5ZTk2NTgwZWRiMSJ9)
* [**Power BI Dashboard image 1 (Dashboard.png)**](https://github.com/SamofDatasets/power-bi-bmw-car-sales-analytics/blob/main/02%20BMW%20Overview%20Dashboard%20Page%201.PNG)
* [**Power BI Dashboard image 2 (All Models.png)**](https://github.com/SamofDatasets/power-bi-bmw-car-sales-analytics/blob/main/03%20BMW%20All%20Models%20Page%202.PNG)

---

## 👨‍💻 Tools & Skills Used

- **Power BI (DAX, Power Query, Data Modeling)**
- **Data Cleaning & Transformation**
- **Interactive Data Visualization**
- **Design (PowerPoint Custom Backgrounds)**
- **Business Intelligence & Analytics**

---

## 📣 Contact

If you're interested in collaborating, feel free to reach out via [LinkedIn](http://www.linkedin.com/in/samuel-kayode-22371b216).

---

> *This project showcases my passion for data storytelling, dashboard design, and business insight generation in real-world scenarios. Thank you for checking it out!*

