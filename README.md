# 🚦 Smart City Traffic Analytics Dashboard: San Francisco (SoMa)

Welcome to a data-driven project aimed at improving urban traffic safety and city planning using real-world data from the SoMa neighborhood in San Francisco. This end-to-end project leverages **Python, Power BI, and public datasets** to identify accident hotspots, complaint trends, and potential policy actions.

---

## 🌐 Project Overview
**Objective:** Analyze traffic-related 311 complaints and reported accidents to discover patterns, identify high-risk zones, and deliver actionable insights to support smart city decision-making.

This project answers:
- Where are most accidents and complaints occurring in SoMa?
- Are there connections between complaint types and accident locations?
- When (days/months/times) do accidents peak?
- What recommendations can improve traffic safety?

---

## 🔧 Tools & Technologies Used
| Tool | Purpose |
|------|---------|
| **Python (Pandas, Jupyter)** | Data cleaning, merging, datetime formatting |
| **Power BI Desktop** | Data visualization & dashboard building |
| **CSV Data** | Source: [SF Open Data Portal]|

---

## 📚 Dataset Description
We used three datasets:
- `accidents_soma.csv` — SF police-reported accidents in SoMa
- `complaints_soma.csv` — 311 complaints (e.g., blocked driveways, traffic signal issues)
- `merged_accidents_complaints.csv` — Cleaned + merged for analysis on complaint-accident correlation

---

## 📊 Dashboard Pages & Insights

### 📈 Page 1: Traffic Accident Analysis
**Visuals:** Map, Bar Chart by Day, Slicers (Year, Neighborhood)

**Insights:**
- **Folsom & 7th** is a major accident hotspot.
- **Fridays** and **evening hours** report highest accidents.
- **SoMa** remains consistently high in volume and density.

**Recommendation:** Install pedestrian signals & increase patrols near hotspots.

---

### 📉 Page 2: 311 Complaint Trends
**Visuals:** Complaint Type Frequency, Neighborhood vs. Type Matrix, Line Chart (Time Trend)

**Insights:**
- "**Traffic Signal Issue**" is the top complaint type in SoMa.
- Complaints peak in **October to December**, likely due to congestion, holidays, or construction.
- **SoMa and Mission** have the highest volume of complaints.

**Recommendation:** Conduct signal audits and improve public signage during peak months.

---

### 🔗 Page 3: Combined Complaint + Accident View
**Visuals:** Complaint+Accident Map, Type vs. Frequency Matrix, Slicers

**Insights:**
- Overlapping zones for **high complaints and accidents** — strong correlation.
- Complaint resolution delays could contribute to recurring issues.

**Recommendation:** Prioritize high-complaint areas for enforcement and urban redesign.

---

## 📸 Screenshots
(Screenshots of dashboard pages is included  in a `screenshots/` folder)

---

## 📝 How to Use This Project
1. Clone or download the repo
2. Open the Jupyter notebook `Phase3_Data_Cleaning.ipynb` to understand the cleaning & merging process
3. Open `smart_city_traffic_analytics.pbix` in Power BI Desktop
4. Interact with slicers (Neighborhood, Year, Complaint Type)
5. Read insights in each page's **textbox** for key findings

---

## 🏆 Key Results Summary
| Area | Key Insight | Actionable Solution |
|------|-------------|---------------------|
| Folsom & 7th | High accident + complaint density | Pedestrian signal, police monitoring |
| Fridays, Evenings | Peak accident timings | Public awareness campaigns |
| Traffic Signal Complaints | Top complaint in SoMa | Routine signal maintenance |
| SoMa, Mission | Highest overlap zones | Safety audits & city planning focus |

---

## 👤 Author
**K Praveen Kumar**  
📧 [inkedin.com/in/praveen-kumar-kummari-100a62366/] 
    Email ID [Praveenkumarkummari2103@gmail.com]
🎓 Certified Data Analyst | Python | Power BI | SQL

---

## 🌍 Acknowledgements
Thanks to:
- [San Francisco Open Data Portal](https://data.sfgov.org)
- [Power BI Community](https://community.powerbi.com)
- [Pandas Documentation](https://pandas.pydata.org/)



> "Smart cities are not built by sensors alone — they’re driven by smart analytics."
