# Driver Monitoring System (DMS) – Data Analysis & Dashboard

## Overview
This project focuses on analyzing real-world driver monitoring data to identify unsafe driving patterns and improve road safety.

A Power BI dashboard was developed to visualize driver behavior, alert trends, and risk indicators such as fatigue, distraction, and overspeeding.

The goal is to transform raw telematics data into actionable insights for fleet management and safety optimization.

---

## Objectives
- Analyze driver behavior using alert-based data  
- Identify patterns in fatigue, distraction, and unsafe driving  
- Monitor speed trends and high-risk driving periods  
- Build an interactive dashboard for decision-making  
- Improve overall road safety insights  

---

## Tech Stack
- **Power BI** → Data visualization & dashboard  
- **Python (Pandas, NumPy)** → Data preprocessing & cleaning  
- **Excel / CSV** → Raw dataset handling  

---

## Dataset
- Real-world driver monitoring dataset (~74K records)  
- Data includes:
  - Driver ID  
  - Vehicle Number  
  - Speed  
  - Alert Type (drowsy, distracted, collision warning, etc.)  
  - Timestamp (hour, day, month)  
  - Location data  

---

## Dashboard Features

### 🔹 Alert Analysis
- Monthly and yearly alert trends  
- Alert distribution by type  
- Identification of dominant alerts (e.g., lane departure warnings)

### 🔹 Time-Based Risk Analysis
- Hour-wise alert trends  
- Day-wise and part-of-day analysis  
- Peak risk periods identified  

### 🔹 Speed & Driving Behavior
- Speed categorized into:
  - High, Medium, Low, Idle, Overspeed  
- Correlation between speed and alert generation  

### 🔹 Driver & Vehicle Insights
- Alert count by vehicle  
- Driver segmentation by age and experience  
- Identification of high-risk drivers/vehicles  

### 🔹 Geospatial Insights
- Map visualization of alert locations  
- Detection of high-risk routes  

---

## Key Insights
- Lane departure alerts contribute the majority of alerts (~79%)  
- Night-time driving shows higher risk levels  
- A small number of vehicles contribute disproportionately to total alerts  
- Overspeeding is strongly linked with collision warnings  
- Peak alert hours observed during mid-day and evening  

---

## Custom Metrics Created
- Fatigue Score  
- Alert Capture Rate  
- Speed Variance  
- Alerts per Vehicle  

---

## Applications
- Fleet performance monitoring  
- Driver risk assessment  
- Road safety analytics  
- Smart transportation systems  

---

## Limitations
- Limited number of vehicles → may not generalize  
- Primarily descriptive analysis (no predictive modeling)  
- Static dashboard (no real-time streaming)  

---

## Future Improvements
- Add machine learning models for risk prediction  
- Build real-time streaming pipeline  
- Develop driver risk scoring system  
- Deploy as a web-based analytics tool  

---

## Dashboard Preview
<img width="1282" height="721" alt="1" src="https://github.com/user-attachments/assets/e3461c48-69a9-4a93-9e9e-f15166080493" />
<img width="1278" height="722" alt="2" src="https://github.com/user-attachments/assets/a6c9ebd0-fed7-4bad-812d-6b8ec174ca07" />
<img width="1278" height="721" alt="3" src="https://github.com/user-attachments/assets/41c63cbf-1a0e-4447-8a8d-0ca208d61284" />


## 📌 Conclusion
This project demonstrates how data analytics and visualization can be used to extract meaningful insights from driver monitoring data and support safer transportation systems.
