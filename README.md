#  Crime Analytics Dashboard (750K+ Records)

<img width="1137" height="638" alt="image" src="https://github.com/user-attachments/assets/d2be8410-b834-42e6-90e5-20aaba1b8ac7" />


## Project Overview
This project provides a comprehensive analysis of criminal activity using a dataset of over **750,000 records**. By leveraging **Python** for data engineering, **SQL** for analytical querying, and **Power BI** for interactive visualization, this dashboard identifies critical patterns in crime frequency, victim demographics, and weapon involvement.

---

## Tech Stack
* **Data Cleaning:** Python (Pandas, NumPy)
* **Database:** PostgreSQL / MySQL
* **Visualization:** Power BI (DAX, Power Query)
* **Documentation:** Markdown

---

## Key Features & Analysis
### 1. Data Engineering (Python)
* **Temporal Extraction:** Derived `crime_hour`, `day_type` (Weekday/Weekend), and `year` from raw timestamps.
* **Demographic Binning:** Segmented victim ages into categories (Kid, Young Adult, Middle Age, Senior) to identify high-risk groups.
* **Noise Reduction:** Filtered out "No Weapon" and "Unknown" categories from weapon analysis to focus on actionable threats.

### 2. Analytical Insights (SQL & DAX)
* **Trend Analysis:** Identified a 17.5% increase in reported crimes from 2020 to 2022.
* **Hourly Distribution:** Discovered peaks in crime activity at noon and late evening hours.
* **Weapon Profiling:** Isolated "Physical Force" as the leading weapon type, accounting for over 140K incidents.

---

##  Dashboard Preview
The interactive dashboard includes:
* **KPI Cards:** Total Reports, Average Victim Age, Gender Distribution.
* **Top 10 High-Risk Areas:** Ranking by incident volume (Central, 77th Street, etc.).
* **Hourly Trend Analysis:** Line chart visualizing the 24-hour crime cycle.
* **Interactive Slicers:** Dynamic filtering by **Year** and **Age Group**.

---

##  Strategic Recommendations
* **Deployment:** Increase patrol frequency in "Central" and "77th Street" precincts during peak evening hours.
* **Victim Support:** Develop safety awareness programs specifically targeting the "Young Adult" demographic (33% of victims).
* **Policy Focus:** Prioritize de-escalation training, as Physical Force remains the most common incident factor.

