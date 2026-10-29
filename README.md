# Shalini Kuruguntla

Dublin-based graduate with an **MSc in Computer Science** (TU Dublin, 2.1) and a **First Class BSc in Business and IT**. I work across data pipelines, SQL and full-stack apps, and I run operations at Nexseyon, an AI automation business building CRM platforms for Irish companies.

**Irish citizen · Available immediately**

[Portfolio](https://shalinikuruguntla.github.io) · [LinkedIn](https://linkedin.com/in/shalini-k-dublin) · shalini.k3579@gmail.com

---

## Projects

### SafePath: MSc dissertation (team of five)
A live safe-route planner for London, built over 11 sprints. We surveyed 53 people (78% put safety before speed) and ran usability tests before launch.

[Code](https://github.com/KaranJoseph12/SafePath) · [Live app](https://safepath-deploy.vercel.app) · [Demo video](https://youtu.be/jXcPZIOq7zg)

My part:
- Built the pipelines that clean Met Police crime data (dropping records with missing coordinates or crime types, filtering to London) and load it into a 1km grid in PostGIS.
- Designed the scoring: weighted 14 crime types by severity, ranked grid cells by percentile to find hotspots, and combined crime, collisions, lighting and hazards with weights users can adjust.
- Built the APIs and their security: JWT authentication, password hashing and input validation.
- Built the map views (React-Leaflet), including a safest-vs-fastest comparison and live hazard alerts over WebSockets.

`Node.js` `React` `Next.js` `TypeScript` `PostgreSQL/PostGIS` `Socket.IO`

### Oracle query tuning: MSc Advanced Databases (individual)
Wrote 10 analytical SQL queries on order and sales data (918K sales rows), including year-on-year growth, RFM customer segmentation and seasonal demand. Tested indexes, materialized views and partitioning against a baseline (materialized views gave the biggest gain), and set up row-level security (VPD), compared with PostgreSQL.

`Oracle SQL` `window functions` `query tuning`

### Time-series databases: MSc Advanced Databases (pair)
TimescaleDB vs MongoDB on live stock-market data. I built the Python ingestion from Yahoo Finance (prices, dividends and splits, with incomplete records dropped), set up the compression and retention policies, and read the query plans in both databases.

`Python` `TimescaleDB` `MongoDB`

### CRM platforms: Nexseyon (with my team)
CRM platforms for our clients, including a solar installer and a tiling company, on Frappe (Python, MariaDB, Redis) and Vue 3, with Next.js apps for job scheduling and on-site forms. Releases go through GitHub Actions, gated by about 220 automated checks. This is client work, so the code is private.

---

## Skills

- **Data & databases:** SQL (window functions, query tuning), PostgreSQL/PostGIS, Oracle, TimescaleDB, MongoDB, ETL, data cleaning, data mining
- **Analytics:** data visualisation, Tableau, Power BI, advanced Excel (Microsoft Office Specialist Excel Champion, UK & Ireland, 2021)
- **Languages & frameworks:** Python, JavaScript/TypeScript, React, Next.js, Node.js, Vue 3, Frappe
- **Delivery:** agile (Jira), GitHub Actions, regression testing, requirements gathering
