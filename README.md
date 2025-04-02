# Oil & Gas Safety and Process Data Intelligence Dashboard

## 🔍 Objective
This project presents a comprehensive data support analyst dashboard built in Power BI to monitor, analyze, and automate insights around safety, process integrity, training compliance, and change control within oil & gas operations.

## 📊 Dataset Overview
Five datasets were simulated to reflect realistic industry data scenarios:

- **safety_observations.csv**: Logs of site safety observations (type, category, severity, verification status)
- **process_verifications.csv**: Results of safeguard verifications, pass/fail status, and criticality level
- **dropped_objects.csv**: Dropped object incidents by risk level and resolution status
- **training_assessments.csv**: Training and compliance data by module, score, and pass/fail outcome
- **change_control_log.csv**: System changes and data integrations with statuses and ownership

Each dataset contains 1,000 records and is date stamped from 2022–2024.

## 📈 Dashboard Features
### KPIs (Cards)
- Total Observations
- Verification Pass Rate (%)
- Dropped Object Incidents This Month
- Average Training Score
- Training Completion Rate
- Open MoC/Change Requests

### Visuals
- **Line Chart**: Observations over time by severity and category
- **Bar Chart**: Verifications by safeguard and criticality
- **Matrix Table**: Risk level of dropped objects by area
- **Pie Chart**: System distribution in change control logs
- **Boxplot or Strip Plot**: Training score distributions by module
- **Heatmap**: Open safety cases by location and status

### Slicers
- Location
- Year
- Module
- System
- Status
- Category

## 💡 Key Insights
- Most common safety observation category: Slips/Trips
- Pass rate for Process Safety Verifications: ~51%
- Helmets and valves are the most frequently dropped objects
- Over 65% of training modules have pass rates above 70%
- Majority of change control tasks involve SAP and PI Historian

## 📁 Project Structure
```bash
/Oil_Gas_Data_Intel_Dashboard/
├── safety_observations.csv
├── process_verifications.csv
├── dropped_objects.csv
├── training_assessments.csv
├── change_control_log.csv
├── OilGas_Safety_Dashboard.pbix
├── README.md
├── .gitignore
```

## 🔗 Connect
Built for industry-level portfolio impact. Connect with me:
- [LinkedIn](https://www.linkedin.com/in/the-madonald)
- [GitHub](https://github.com/themacdonald)

---
> "Data drives decisions. Decisions drive safety."

