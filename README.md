# 🛢️ Oil & Gas Data Intelligence Power BI Dashboard

## 📌 Overview
This Power BI project features a comprehensive 6-page dashboard to analyze operational safety, process verification, training compliance, incident reports, and change control management in the oil & gas industry.

---

## 📂 Dataset Categories
Each dataset contains 1,000+ simulated entries to reflect real-world operational data:

| Dataset                  | Description                                                  |
|--------------------------|--------------------------------------------------------------|
| safety_observations.csv | Logs of site safety incidents by category, status, and date  |
| process_verifications.csv | Verification outcomes by safeguard and criticality          |
| dropped_objects.csv      | Reports of dropped object incidents and their resolution     |
| training_assessments.csv | Training scores, pass/fail status, and module assessments    |
| change_control_log.csv   | Change requests and integration data across IT systems       |

Each dataset contains 1,000 records and is date stamped from 2022–2024.
---

## 📊 Dashboard Pages

### 1. Executive Overview
- KPIs: Total Observations, Pass Rate, Incidents, Avg Score, Open Changes
- Line Chart: Safety Trends
- Matrix: Observation Status by Location
- Pie: Verifications by Criticality
- Bar: Change Requests by System

### 2. Safety Observations
- KPIs: Total, Verified %, Open
- Bar: Observations by Category
- Line: Trends Over Time
- Matrix: Location vs Status
- Table: Full Log

### 3. Process Verifications
- KPIs: Total, Pass %, Failed, This Month
- Bar: By Safeguard
- Pie: Criticality Breakdown
- Matrix: Location vs Pass/Fail
- Table: Failed Details

### 4. Dropped Objects
- KPIs: Total, Avg Resolution Time, This Year
- Line: Trend Over Time
- Matrix: Area vs Risk
- Bar: Frequency by Object
- Table: Open Investigations

### 5. Training Assessments
- KPIs: Total, Pass %, Avg Score
- Bar: Score by Module
- Boxplot: Score Distribution (via custom visual)
- Table: Failed Learners

### 6. Change Control
- KPIs: Total, Open, This Month
- Pie: System Distribution
- Bar: Type of Changes
- Matrix: System vs Status
- Table: Unexecuted Requests

---

## 🧩 Data Model
All tables connect to a single `DateTable` via their respective date fields. Relationships are one-to-many and unidirectional.

---

## 🛠️ Project Structure
```bash
/Oil_Gas_Data_Intel_Dashboard/
├── safety_observations.csv
├── process_verifications.csv
├── dropped_objects.csv
├── training_assessments.csv
├── change_control_log.csv
├── date_table.csv
├── OilGas_Safety_Dashboard.pbix
├── README.md
```

---


## 🔗 Connect
Built for industry-level portfolio impact. Connect with me:
- [LinkedIn](https://www.linkedin.com/in/the-madonald)
- [GitHub](https://github.com/themacdonald)

---
> "Data drives decisions. Decisions drive safety."

