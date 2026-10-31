# Shalini Kuruguntla

Dublin-based graduate with an **MSc in Computer Science** (TU Dublin, 2.1) and a **First Class BSc in Business and IT**. I work across the full software lifecycle: APIs, data pipelines and front ends, shipped through CI/CD into Docker on Linux servers. I'm Operations Manager at Nexseyon, an AI automation business building CRM platforms for Irish companies, and I'm training in AWS and DevOps.

**Irish citizen · Available immediately**

[Portfolio](https://shalinikuruguntla.github.io) · [LinkedIn](https://linkedin.com/in/shalini-k-dublin) · shalini.k3579@gmail.com

---

## Featured project

### SafePath: MSc dissertation (team of five)
A live safe-route planner for London, built over 11 agile sprints from requirements to tested release. We surveyed 53 people (78% put safety before speed) and ran usability tests before launch.

[Code](https://github.com/KaranJoseph12/SafePath) · [Live app](https://safepath-deploy.vercel.app) · [Demo video](https://youtu.be/jXcPZIOq7zg)

My part:
- Built the Node.js REST APIs and their security: JWT authentication, password hashing and input validation.
- Built the map views (React-Leaflet), including a safest-vs-fastest comparison and live hazard alerts over WebSockets.
- Built the pipelines that clean Met Police crime data and load it into a 1km grid in PostGIS.
- Designed the scoring: weighted 14 crime types by severity, ranked grid cells by percentile to find hotspots, and combined crime, collisions, lighting and hazards with weights users can adjust.
- Drew the architecture diagrams.

`Node.js` `React` `Next.js` `TypeScript` `PostgreSQL/PostGIS` `Socket.IO`

## Other work

- **CRM platform** (Nexseyon, with my team, private client work): a CRM on Frappe (Python, MariaDB, Redis), Vue 3 and Next.js, running in Docker Compose on Ubuntu servers behind nginx. Every release goes through GitHub Actions with about 220 automated tests, with nightly backups, role-based access and an audit trail. Includes a GPT-4o assistant, an MCP connector for secure AI access to CRM data, and a Python/Playwright bot that files grid-connection forms.
- **Oracle query tuning** (MSc Advanced Databases, individual): 10 analytical SQL queries on 918K sales rows, including year-on-year growth and RFM segmentation. Tested indexes, materialized views and partitioning against a baseline, and set up row-level security (VPD).
- **Time-series databases** (MSc Advanced Databases, pair): TimescaleDB vs MongoDB on live stock-market data. I built the Python ingestion and set up the compression and retention policies.

More detail on my [portfolio](https://shalinikuruguntla.github.io).

---

## Skills

- **Languages & front end:** Python, JavaScript/TypeScript, SQL, Node.js, React, Next.js, Vue 3
- **APIs & data:** REST APIs, WebSockets, webhooks; MariaDB, PostgreSQL/PostGIS, Oracle, MongoDB, TimescaleDB; ETL
- **Delivery & ops:** Git, GitHub Actions (CI/CD), automated testing, Docker, Linux, nginx, agile (Jira)
- **AI & security:** AI coding tools (Claude Code), LLM APIs, MCP; RBAC, JWT, OAuth, audit logs
- **Analytics:** Power BI, Tableau, advanced Excel (Microsoft Office Specialist Excel Champion, UK & Ireland, 2021)

**Learning:** AWS Cloud Practitioner and Microsoft SC-900 exams (December 2026), plus AWS DevSecOps training: Linux, CI/CD, Terraform, Docker and Kubernetes.
