## Project Title
**Healthcare Data Analysis Using Power BI**
## Overview
This project presents a dynamic healthcare analysis dashboard that visualizes critical hospital metrics such as total patients, average length of stay, total billing, feedback scores, diagnosis distribution, and bed occupancy. The goal is to assist hospital management in monitoring performance and making informed decisions.
## Problem Statement
Hospitals face challenges in understanding large amounts of patient data, diagnosis trends, and financial billing details. Without centralized and visual analytics, it becomes difficult to monitor efficiency, identify resource shortages, or improve patient care. This dashboard solves that gap with clear visual insights.
## Dataset Used
- <a href="https://github.com/manshipriya01/healthcare_dashboard.pbix/blob/main/healthcare_data_analysis.xlsx">Dataset</a>
## Tech Stack
- **Power BI Desktop** – for data visualization
- **Microsoft Excel / CSV** – as the data source
- **DAX** – to calculate KPIs like average length of stay
- **Power Query Editor** – for data cleaning and transformation
## Dashboard Components
- **KPI Cards**
  - Total Patients: `7157`
  - Average Length of Stay: `8.25 Days`
  - Total Billing: `₹190.43M`
- **Slicers/Filters**
  - Date Range Picker (From Dec 2022 to Mar 2024)
  - Diagnosis Filter (e.g., Flu, Fracture)
  - Doctor Filter
- **Visual Charts**
  - Bar Chart: Bed Occupancy by Bed Type (Private, General, ICU)
  - Donut Chart: Feedback Score per Doctor
  - Horizontal Bar Chart: Patients by Diagnosis (Top: Viral Infection, Flu)
  - Line Chart: Billing vs Insurance Amount per Diagnosis
- **Data Table**
  - Detailed patient-level data: ID, Admit & Discharge Dates, Doctor Name, Feedback Score
