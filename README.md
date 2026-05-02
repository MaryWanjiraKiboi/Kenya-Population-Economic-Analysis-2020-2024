
Is Kenya's economy growing faster than its population?

The answer turns out to be yes, and meaningfully so: while population grew 7.4% over five years, GDP per capita grew 41.0%, leaving a 33.5% real income gain per person. The dashboard makes that gap visible at a glance.

**About this project**
This project transforms a raw long-format dataset of Kenyan economic indicators into an interactive, formula-driven Excel dashboard. 
The goal: turn a 80-row table of (id, indicator, year, value) into a one-page view that answers a single question — is Kenya's economy growing faster than its population? 
The dashboard makes that gap visible at a glance.
<img width="612" height="518" alt="image" src="https://github.com/user-attachments/assets/8919c9e7-89d0-4f1a-ab4e-232ba53eef43" />

**Approach**
The workbook is structured in three layers, mirroring how production data tools are built:

**Data layer — the raw indicators table (indicators dataset)**
Calculation layer — pivot tables and helper ranges that aggregate values and compute growth rates (Pivot table)
Presentation layer — KPI cards and charts that reference the calculation layer, never the raw data (Dashboard)
This separation means the dashboard updates automatically when new years of data arrive — only the source table needs to change.

**What's on the dashboard**
5 KPI cards: latest-year population, latest-year GDP per capita, 5-year population growth, 5-year GDP per capita growth, and real income gain
Population trend chart (line) — shows steady ~1.8% annual growth
GDP per capita trend chart (line) — shows the climb from KSh 219K to KSh 309K
Growth comparison chart (clustered column) — the punch line: GDP growth dwarfs population growth every year

**Data source**
Kenya National Bureau of Statistics (KNBS), 2020–2024.

