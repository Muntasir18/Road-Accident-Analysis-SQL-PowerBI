# Road Accident Data Analysis (2021-2022) 🚗

## 📌 Project Overview
This project provides a comprehensive analysis of road accident data in the UK. The goal was to transform raw data into a strategic dashboard to identify safety trends, high-risk locations, and impact factors (weather, road type, vehicle type).

---
## 🖼 Dashboard Preview
<img width="2250" height="1252" alt="preview_dashboard" src="https://github.com/user-attachments/assets/cc4b3f69-00f1-4a3e-bf21-5526c2844469" />

I used **SQL** for rigorous data validation and KPI calculation, ensuring the accuracy of the numbers displayed in the final **Power BI** dashboard.

## 🛠 Tech Stack
- **Data Cleaning (Python):** I used Python (Pandas) to preprocess the raw dataset, handling date formatting (converting strings to datetime objects) and ensuring data consistency before analysis.
- **Database:** MySQL / SQL Server (Data extraction & KPI validation)
- **Visualization:** Power BI (DAX, Interactive Dashboards, Map Visuals)
- **Data Source:** Road Accident Dataset (2021-2022)

## 📊 Key Performance Indicators (2022 vs 2021)
- **Total Casualties (2022):** **195,737** (A decrease of **11.9%** vs previous year).
- **Total Accidents:** **144,419**.
- **Casualty Severity:**
  - Fatal: 2,855
  - Serious: 27,045
  - Slight: 165,837

## 📈 Key Insights from Dashboard
- **Monthly Trend:** Casualties peaked in **November (18.4K)** and reached their lowest in **January (13.2K)**.
- **Vehicle Type:** **Cars** are involved in the vast majority of casualties (**155,804**), while Motorcycles account for **15,579**.
- **Road & Environment:**
  - **61.95%** of casualties occur in **Urban areas**.
  - **Single carriageways** are the most dangerous road types, accounting for **145K casualties**.
  - **73.8%** of accidents happen during **Daylight**.
- **Geography:** **Birmingham** is the location with the highest number of casualties (**4,092**) in 2022.

## 💻 SQL Implementation
I performed complex queries to validate the dashboard metrics, including:
- **Time Intelligence:** Comparing Current Year (CY) vs Previous Year (PY).
- **Data Segmentation:** Grouping vehicle types (e.g., merging all motorcycle categories) and light conditions.
- **Ranking:** Identifying the Top 10 high-risk local authorities.

## 📂 Data Access
Due to the large size of the dataset, the raw files are hosted on Google Drive:
[👉 Access Dataset Here](https://drive.google.com/drive/folders/1pCNs-TRPznlbAn712gAGy7XfBnWs2QJm)





