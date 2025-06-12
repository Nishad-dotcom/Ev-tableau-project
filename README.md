# Ev-tableau-project
🚗 Electric Vehicle Analytics & Insights Dashboard – Tableau Project
📊 Project Overview
This project presents an interactive, multi-layered dashboard built in Tableau, visualizing electric vehicle (EV) data from Washington State. The dashboard provides deep insights into electric vehicle types, geographic distribution, model performance, and Clean Alternative Fuel Vehicle (CAFV) eligibility, using a combination of advanced Tableau features and design best practices.

🎯 Objectives
Analyze and visualize EV adoption trends across different counties and cities.

Compare BEV (Battery Electric Vehicles) and PHEV (Plug-in Hybrid) usage.

Identify patterns in electric range, eligibility, and manufacturer popularity.

Use geospatial data to track EV distribution across census tracts and utilities.

Demonstrate advanced Tableau functionality in a unified, user-friendly dashboard.

🧩 Data Source
Dataset: Public electric vehicle registration data (WA state)
Fields Used:

VIN, Make, Model, Model Year

EV Type (BEV/PHEV), Electric Range

County, City, State, Postal Code

Utility Provider, Legislative District, Census Tract

CAFV Eligibility, MSRP, Vehicle Location (GeoPoint)

🔧 Tools & Technologies
Tableau Desktop (v2022+)

Tableau Public (for publishing)

Excel/CSV for data formatting

🛠️ Key Features & Techniques Used
✅ Data Cleaning & Shaping

Handled missing values and inconsistent formats

Split multi-value fields (e.g., utility providers)

✅ Data Modeling

Used data blending for external datasets (utility, population)

Created relationships and field hierarchies

✅ Advanced Calculations

LOD Expressions (e.g., total range by city)

Table Calculations (e.g., rank by range or MSRP)

Calculated Fields for custom KPIs

✅ Interactivity

Parameters for dynamic filters

Set/Group Actions for advanced user control

Hierarchical Filters (County → City → Model)

✅ Geospatial Mapping

Plotted data using POINT (lat long) fields

Used filled maps and symbol maps by census tract and utility

✅ Dashboard Design

Combined multiple dashboards using navigation buttons

Applied tooltips, highlight actions, and drilldowns

Included KPI cards and slicers for better UX



📈 Key Insights
Majority of BEVs are concentrated in urban counties like King and Snohomish.

Hyundai and Tesla dominate BEV range performance.

CAFV eligibility varies strongly with EV type and electric range.

Geographic clusters show infrastructure opportunities for utilities.

📁 Project Structure
markdown
Copy
Edit
📁 /EV-Tableau-Dashboard
├── 📊 Tableau Dashboard (.twbx)
├── 📄 Data Source (.csv/.xlsx)
├── 🖼️ Dashboard Screenshots
└── README.md
👤 Author
Nishad Burley
Aspiring Data Analyst | Tableau & Power BI Enthusiast
📫 LinkedIn | 🌐 Portfolio

Let me know if you'd like a minimal version or want me to generate the dashboard preview images for the README.
