# 🎓 Student Housing Dashboard & Data Visualization

A comprehensive **Tableau**‑powered dashboard showcasing key insights from a student housing survey at Arizona State University. Built as part of IFT 598: Data Visualization & Reporting to IT, this project guides prospective tenants, administrators, parents and investors through interactive charts on rent, amenities, commute, lease periods and more.

---

## 📖 Overview

Students and stakeholders need clear, data‑driven insights when choosing on‑ or off‑campus housing. We collected **194** survey responses covering:

- Apartment types & rents  
- Campus affiliation  
- Amenities & challenges  
- Mode of transportation  
- Lease periods & living expenses  

Using modern visualization techniques (pie, bar, line, maps, highlight tables), we deliver an at‑a‑glance decision support tool.

---

## 📂 Repo Structure
```bash
student‑housing‑dashboard/
├── dashboards/
│ └── StudentHousing.twb # Tableau workbook (Phase III)
├── data/
│ └── housing_survey.csv # Cleaned survey data (194×11)
├── docs/
│ ├── Project‑Phase_1_Planning.docx
│ ├── Project‑Phase_II_DecisionMaking.docx
│ └── Project‑Phase_III_Dashboard.docx
└── README.md
```

## 🚀 Phases

### Phase I – Planning  
- Defined stakeholder personas (students, parents, admins, investors)  
- Collected & cleaned 194 × 11 survey fields  
- Drafted key user questions & requirements :contentReference[oaicite:4]{index=4}

### Phase II – Decision Making  
- Pre‑processed missing & duplicate values in Google Sheets & Excel  
- Finalized list of 10 dashboard questions (rent vs. lease, commute patterns, preferred apartments, etc.) :contentReference[oaicite:5]{index=5}

### Phase III – Dashboard Implementation  
- Built interactive **Tableau** dashboard with:
  - Pie chart: Mode of transport  
  - Bar charts: Rent vs. apartment, lease periods, student preferences  
  - Line chart: Lease period trends  
  - Map: Student housing populations  
  - Highlight tables: Campus distributions  
- Connected interactivity filters (amenities, transport, apartment types) 

---

## 📊 Dashboard Highlights

| Chart                            | Interaction                                     | Preattentive Cue |
|----------------------------------|-------------------------------------------------|------------------|
| Mode of Transport (pie)          | Filter by on‑/off‑campus                        | Hue              |
| Rent vs. Apartment (bar)         | Checkbox filter by apartment type               | Length           |
| Avg. Lease Period (bar)          | —                                               | Length           |
| Domestic vs. International (bar) | —                                               | Length           |
| Lease Period Trends (line)       | —                                               | Position         |
| Preferred Apartment (bar)        | —                                               | Length           |
| Population Map                   | —                                               | Size / Hue       |
| Priorities 1–5 (bar series)      | —                                               | Length           |
| Average Monthly Expenses (bar)   | —                                               | Length           |
| Amenities (bar)                  | Dropdown filter by amenity                      | Length           |

> **Try it live:**  
> https://public.tableau.com/app/profile/priyanka.avasarala/viz/StudentHousing_16823150698610/StudentHousing?publish=yes

---

## 🔗 References

- **Dataset:**  
  https://docs.google.com/spreadsheets/d/1gFjxwLkoc8m8XyK-yXLxn3_xOE9CCs9dLJCriyD0POs/edit#gid=0

- **Team Mural Board:**  
  https://app.mural.co/t/dvproject4029/m/dvproject4029/1681347522570/4c64ed49e9ee0da22fdaa67737ca786a22d9ec6e

---

## 👥 Team

- Priyanka Avasarala  
- Aishwarya Devi Akkim  
- **Neeharika Mereddy**  
- Ganavi Hemachandra  

Prof. Asmaa Elbadrawy | Department of Information Technology, ASU

---

## 💡 Next Steps

- **Live Data Refresh:** connect to a database for real‑time updates  
- **Advanced Analytics:** integrate predictive ML for rent forecasting  
- **Mobile‑Friendly UI:** embed dashboard in a responsive web app  
- **User Testing & Feedback:** iterate based on stakeholder input  

---

*April 2023*  
*IFT 598: Data Visualization & Reporting to IT*  

