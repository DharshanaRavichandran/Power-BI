
# Patient Waitlist Dashboard

## Overview
This repository contains a Power BI dashboard project that analyzes patient waitlist data in the healthcare system. It covers both In-Patient and Out-Patient records from 2018 to 2021, focusing on key metrics like wait time distributions, specialties, age profiles, and case types. The dashboard includes KPIs, filters, and interactive navigation for both high-level and detailed views.

This guided project showcases a multi-page Power BI report with interactive features, custom slicers, and performance KPIs (Average & Median).

## Dataset Highlights
The project integrates 9 CSV files to build a comprehensive dataset:

- 4 In-Patient files (2018–2021)
- 4 Out-Patient files (2018–2021)
- Mapping_Specialty.csv for descriptive labels

### Data Model Construction:
- In-Patient files were grouped into one consolidated table
- Out-Patient files were similarly grouped
- Both groups were merged to form an Overall Patient Waitlist table
- The Specialty field from the overall dataset was joined with Specialty_name from the specialty mapping table to provide readable labels

## Key Insights

### Wait Time Trends
- Majority of patients waited under 6 months
- Slight increase in long waits (12+ months) during 2020–2021 due to COVID impact

### Case Type Analysis
- Out-Patients represent a significantly higher volume
- In-Patients show longer median wait times on average

### Specialty Distribution
- High traffic in ENT, Dermatology, and Orthopaedics
- Specialty mapping ensures clarity and consistency in reporting

### Age Group Dynamics
- Largest group: 16–64 years
- Elderly patients (65+) experienced relatively longer wait durations

## Dashboard Features
The Power BI dashboard includes:

### Two main report pages:
- **Summary Dashboard**: High-level KPIs, slicers, trends
- **Detailed View**: Specialty-level breakdowns and data drilldowns

### KPI Cards:
- Average and Median Wait Times

### Interactive Slicers:
- Case Type (In-Patient / Out-Patient)
- Age Group
- Wait Time Band
- Trend visuals by year and specialty
- Bar charts, matrix tables, and filters for deep exploration

## Dependencies
- Microsoft Power BI Desktop (2025 or compatible version)

## Dashboard Preview
https://github.com/DharshanaRavichandran/Power-BI/tree/main/Dashboards/Patient/Preview

## Files Included
- `Patient_Waitlist.pbix` – Power BI dashboard file
- `IN_WL 2018.csv` – 2018 inpatient data files
- `IN_WL 2019.csv` – 2019 inpatient data files
- `IN_WL 2020.csv` – 2020 inpatient data files
- `IN_WL 2021.csv` – 2021 inpatient data files
- `Op_WL 2018.csv` – 2018 outpatient data files
- `Op_WL 2019.csv` – 2019 outpatient data files
- `Op_WL 2020.csv` – 2020 outpatient data files
- `Op_WL 2021.csv` – 2021 outpatient data files
- `Specialty_Mapping.csv` – Lookup file for readable specialty names
- `README.md` – Documentation

## Additional Notes
This dashboard emphasizes visual storytelling through clean design, structured relationships, and pre-processed datasets. While much of the data modeling is done through static aggregations and table joins in Power BI, **certain key measures (e.g., average, median waitlist values)** are calculated using **DAX expressions** to enhance analytical insights and interactivity.

## Connect With Me
- **LinkedIn**: Dharshana Ravichandran (https://www.linkedin.com/in/dharshuravi)
- **Email**: dharshuravi797@gmail.com
