# Import Data using Transform Maps (Spreadsheet) — ServiceNow

## 📌 Overview
This project demonstrates end-to-end bulk data ingestion into **ServiceNow** using **Import Sets** and **Transform Maps**. It simulates a real-world enterprise scenario where employee data supplied via external Excel spreadsheets (`.xlsx`) is staged, mapped, transformed, deduplicated, and visualized using ServiceNow reporting tools.

---

## 🎯 Key Objectives & Milestones
- **Milestone 1: Creation of Spreadsheet & Target Table**
  - Designed structured employee data in Excel (`.xlsx`).
  - Created a target table in ServiceNow with matching custom fields.
- **Milestone 2: Import Set & Transform Map Configuration**
  - Loaded raw spreadsheet data into a staging **Import Set Table**.
  - Configured a **Transform Map** to align source staging fields with target table attributes.
- **Milestone 3: Data Transformation & Coalescence (Deduplication)**
  - Executed data transformation and verified successful record insertion.
  - Set **Coalesce = true** on unique identifiers (`Employee ID`) to update existing records and prevent duplicate entries on re-imports.
- **Milestone 4: Reports & Dashboards**
  - Created reports to analyze employee data (*Employees by Department*, *Employees by Location*).
  - Built an **Employee Analytics Dashboard** consolidating all reports.

---

## 🛠️ Tools & Technologies
- **Platform:** ServiceNow Personal Developer Instance (PDI)
- **Features Used:** System Import Sets, Transform Maps, Field Mapping, Coalesce Rules, System Reports, Dashboards.
