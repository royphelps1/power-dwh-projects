# CMMS Maintenance Analysis – Power BI Dimensional Model

## 🧰 Overview
This project demonstrates a dimensional model built in Power BI using maintenance data from a CMMS system. It includes a star schema with fact and dimension tables, surrogate keys, and calculated measures for KPI tracking.

## 📌 Business Goal
To provide visibility into line-level maintenance events, allowing stakeholders to track downtime, frequency of issues, and preventive vs corrective maintenance trends.

## 📊 Tools Used
- Power BI Desktop
- Power Query (ETL steps)
- DAX Measures
- Dimensional Modeling (Star Schema)


**Fact Table**
- FactCMMS: contains event counts, duration, type of maintenance, timestamps.

**Dimensions**
- DimLine: Line number and description
- DimDepartment: Department associated with the line
- DimDate: Shared date table
- DimEventType: Corrective vs Preventive

## 🧠 KPIs
- Average duration per line
- Count of maintenance events per type
- Total downtime hours
- Cost



