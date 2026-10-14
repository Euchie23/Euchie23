# Euchie Jn Pierre — Environmental Data Scientist & Risk Intelligence Builder 👋🌱

> I build **data-driven decision-support systems** that turn complex environmental, spatial, and operational data into **defensible, decision-ready insights**.

Interdisciplinary environmental data scientist and applied risk practitioner working across **environmental systems, spatial analytics, and operational risk (HSE)**.  
Trained in Taiwan and currently based in Saint Lucia, with experience in **regulated and high-uncertainty environments**.
<br>
[🌐 Portfolio Website — Environmental Data Science & HSE-Q Projects](https://euchie-portfolio.vercel.app)
<br><br>
<img src="https://img.shields.io/badge/-Data%20Scientist-276DC3?&style=for-the-badge&logo=r&logoColor=white" />
<img src="https://img.shields.io/badge/-Marine%20Ecology-0099cc?&style=for-the-badge&logo=fish&logoColor=white" />
<img src="https://img.shields.io/badge/-Business%20Background-0072b1?&style=for-the-badge&logo=briefcase&logoColor=white" />

---

## 🚀 Featured Project — Biomass Simulator (Climate Risk Tool)

**A scenario-based decision-support tool for evaluating how ocean warming assumptions may affect squid biomass and fisheries risk.**

Simulates how squid populations respond to ocean warming scenarios (+2°C default), supporting **fisheries risk assessment and climate-informed planning**.

**What it does:**
- Models biomass response under climate change scenarios  
- Translates long-term fisheries data into predictive insight  
- Supports early-stage ecological risk evaluation  

🔗 [View App](https://squidstock-ocean-dynamics.streamlit.app)

## 🧠 What I Build

I design **data-driven decision-support systems under uncertainty**, where:

- data must be validated before use
- uncertainty and model limitations are explicit
- analytical workflows are traceable and reproducible
- outputs support **real-world decisions**, not just analysis 

---

## 🎓 Background
- Marine Environmental Science + Applied Data Science 
  - MSc Biodiversity — National Taiwan University (Taiwan)
- Originally trained in business, bringing operational insight and analytical rigor to environmental data and decision-support work.
- Currently based in **Saint Lucia**

---

## 💡 What I Do
I design **decision tools**, not just analyses.

That means:
- validating data before interpreting it
- making uncertainty explicit
- translating outputs into **screening-level intelligence** people can actually use

Target environments include:
**environmental consultancies, regulators, NGOs, sustainability teams, and applied data groups**.

---

## 🧩 Decision-Support Architecture
Across projects, I follow a consistent decision-support architecture that emphasizes data credibility, traceability, and operational relevance.

```mermaid
flowchart LR

    %% --- Define subgraphs ---
    subgraph S1["Data Ingestion"]
      A["Data Sources\nField Sampling | Lab Analysis | Vessel Data\nRemote Sensing (netCDF) | Public Data"]
    end

    subgraph S2["Data Management"]
      B["PostgreSQL + PostGIS\nCleaning | Integration | QA/QC | Governance"]
    end

    subgraph S3["Analytics"]
      C["R | Python | Statistics | ML"]
    end

    subgraph S4["Applications"]
      D["Shiny | Streamlit Apps"]
    end

    subgraph S5["Stakeholders"]
      E["Regulators | Consultancies | ESG | HSE"]
    end

    %% --- Define connections ---
    A --> B --> C --> D --> E

    %% --- Increase font size ---
    classDef bigFont font-size:16px, font-family:Arial, font-weight:bold;
    class A,B,C,D,E bigFont;
```
*Turning environmental and operational data into **defensible, decision-ready risk intelligence**.*

---
## 🧠 Decision Intelligence Systems (Repositories)

A collection of applied systems designed to support **decision-making under uncertainty** across environmental and operational risk contexts.

## 🦑 SquidStack
**Environmental Contaminants & Human Health Screening**  
Interactive **R Shiny dashboards** translating marine pollution data into **risk-aware insights**.


**Decision flow:**
- QA/QC & data credibility
- Pattern detection & prioritization
- Temporal trend analysis (incl. COVID-era effects)
- Human health screening (EDI / HQ)

[*More about SquidStack*](https://github.com/Euchie23/SquidStack/)  

🔗 Apps:  
- 🧱 [Foundation](https://euchie23.shinyapps.io/foundation/) 
- 🤿 [Exploration](https://euchie23.shinyapps.io/exploration/) 
- 📈 [Fluctuations](https://euchie23.shinyapps.io/fluctuation/) 
- ☣️ [Risk Evaluation](https://euchie23.shinyapps.io/risk_evaluation/)

Used for: screening environmental contamination and translating it into human health risk insights.

*🎥 Guided dashboard walkthroughs are available for selected applications within the repository and individual dashboard documentation.*
  
---

## 📈 SquidStock
**Fisheries Dynamics & Risk-Aware Modeling**  

Python & Streamlit tools supporting **stock assessment and planning under uncertainty**.

Includes:
- CPUE standardization (GAMs, Tweedie)
- Biomass simulation (EDSPM-style models)
- Scenario-aware forecasting
- Exploratory ML with explicit validation limits

[*More about SquidStock*](https://github.com/Euchie23/SquidStock/) 

🔗 Apps / Notebooks:  
- 📈 [Temporal CPUE Analysis](https://github.com/Euchie23/SquidStock/blob/main/notebooks/Temporal_Catch_Analysis/Temporal_Catch_Analysis.ipynb) 
- 📊 [CPUE Standardization & Prediction](https://squidstock-course-correction.streamlit.app) 
- 🌡️ [Biomass Simulation under Warming Scenarios](https://squidstock-ocean-dynamics.streamlit.app)
- ⚙️ [Predictive Squid Catch Models using AutoML](https://squidstock-the-engine-room.streamlit.app)

Used for: stock assessment, effort standardization, and forecasting under environmental and climate variability.

*🎥 Guided dashboard walkthroughs are available for selected applications within the repository and individual dashboard documentation.*

---

## 🌍 GeoTentacles 
**Marine Ecosystem Spatial Intelligence**  

Interactive dashboards turning marine data into actionable insights on hotspots, pollution, and ecosystem health

Highlights:
- 20+ years of spatio-temporal hotspot analysis for fisheries and marine ecosystems
- Machine learning models for **probabilistic hotspot prediction**
- **Marine pollution monitoring** and ecosystem condition analytics
- **Spatial interpolation** and predictive environmental **risk modeling** (e.g., IDW surfaces)
- **Geospatial analytics** built using tools such as **PostGIS, Folium, and interactive web frameworks**
- Interactive applications deployed with scalable cloud databases like **Neon (serverless PostgreSQL)**

[*More about GeoTentacles*](https://github.com/Euchie23/GeoTentacles/)  

🔗 App(s):  
- [🗺️ **Hotspots — Historical and Predicted Squid Catch Hotspots**](<https://euchie23.shinyapps.io/geotentacles__hotspots/>)
- [🌎 **Marine Scope - Your Window into Marine Ecosystem Health**](https://geotentacles-marinescope.streamlit.app)

Used for: identifying ecological hotspots, pollution patterns, and spatial risk distribution in marine systems.

*🎥 Guided dashboard walkthroughs are available for selected applications within the repository and individual dashboard documentation.*

---

## 🦺 HSE–Q Risk Intelligence (Personal Project - In Development)

**A decision-support platform for HSE-Q operational environments**, designed to turn field activities, safety observations, incidents, emergency drills, and daily reporting into **structured, traceable, and management-ready operational intelligence**.

**Current System Components:**

- Relational operational data model (PostgreSQL)
- Guided field data-entry application (Streamlit)
- Daily operations workflow with controlled end-of-day confirmation
- Planning records (PWP, PTW, JSA, Method Statements)
- Personnel, team, zone, and site setup management
- Observations, hazards, controls, and corrective-action workflows
- Incident / event recording and lifecycle handling
- Emergency drill tracking and report generation
- Daily management report snapshots and operational traceability 
- KPI / analytics-ready architecture for future dashboard expansion
  
👉 [How It Works (Simple Overview)](https://github.com/Euchie23/HSEQ_Risk_Intel/blob/main/HOW_IT_WORKS.md)

**Purpose:**  
To structure real-world HSE-Q field data into **audit-ready, explainable, and operationally useful decision-support records for regulated and safety-sensitive work environments**.

## 📌 Conceptual Operational Model 

Below is a high-level, operational risk intelligence ERD diagram showing how risk information flows through the system.

```mermaid
erDiagram

    SITE ||--o{ SITE_SECTION : contains
    SITE_SECTION ||--o{ ZONE : governs
    ZONE ||--o{ PHASE : supports

    ORGANIZATION ||--o{ PERSON : employs
    ORGANIZATION ||--o{ TEAM : owns
    PERSON ||--o{ TEAM : supervises_or_joins

    SITE_SECTION ||--o{ ATTENDANCE_SHIFT : records
    ATTENDANCE_SHIFT ||--o{ ATTENDANCE_PERSONNEL : includes
    PERSON ||--o{ ATTENDANCE_PERSONNEL : attends

    PHASE ||--o{ TASK_TEMPLATE : defines
    TASK_TEMPLATE ||--o{ TASK_EXECUTION : instantiated_as
    TEAM ||--o{ TASK_EXECUTION : performs
    WEATHER ||--o{ TASK_EXECUTION : influences

    SITE_SECTION ||--o{ PLANNED_WORK_PACKAGE : manages
    PLANNED_WORK_PACKAGE ||--o{ PTW : links
    PLANNED_WORK_PACKAGE ||--o{ JSA : links
    PLANNED_WORK_PACKAGE ||--o{ METHOD_STATEMENT : links
    PLANNED_WORK_PACKAGE ||--o{ TASK_EXECUTION : guides

    TOOLBOX_MEETING ||--o{ TOOLBOX_ATTENDEES : includes
    TOOLBOX_MEETING ||--o{ TOOLBOX_MEETING_TOPICS : covers
    TOOLBOX_MEETING ||--o{ TOOLBOX_MEETING_TASKS : references

    OBSERVATION ||--o{ OBSERVATION_ZONES : affects
    OBSERVATION ||--o{ HAZARD : may_generate
    OBSERVATION ||--o{ CORRECTIVE_ACTION : may_create

    HAZARD ||--o{ HAZARD_CONTROLS : mitigated_by
    HAZARD ||--o{ CORRECTIVE_ACTION : may_require

    INCIDENT ||--o{ INCIDENT_PEOPLE : involves
    INCIDENT ||--o{ INCIDENT_TASK_LINKS : relates_to
    INCIDENT ||--o{ INCIDENT_OBSERVATION_LINKS : relates_to
    INCIDENT ||--o{ INCIDENT_STATUS_HISTORY : tracks

    EMERGENCY_DRILL ||--o{ EMERGENCY_DRILL_PARTICIPANTS : includes
    EMERGENCY_DRILL ||--o{ EMERGENCY_DRILL_TASK_LINKS : relates_to
    EMERGENCY_DRILL ||--o{ EMERGENCY_DRILL_INCIDENT_LINKS : relates_to
    EMERGENCY_DRILL ||--o{ EMERGENCY_DRILL_OBSERVATION_LINKS : relates_to
    EMERGENCY_DRILL ||--o{ EMERGENCY_DRILL_CORRECTIVE_ACTION_LINKS : relates_to

    DAILY_CONFIRMATION_BATCH ||--o{ DAILY_CONFIRMATION_EMERGENCY_DRILLS : includes
    DAILY_CONFIRMATION_BATCH ||--|| DAILY_MANAGEMENT_REPORT_SNAPSHOT : freezes

    APP_USER ||--o{ APPROVAL_REQUESTS : submits
```

📘 System workflows, rules, and implementation notes are documented in the
*(See [Database Operations Manual](https://github.com/Euchie23/HSEQ_Risk_Intel/blob/main/docs/Database_Operations_Manual.md) for full implementation guide)*

[*More about HSE-Q Risk Intelligence*](https://github.com/Euchie23/HSEQ_Risk_Intel/)  

---

## 🔭 Planned Version 2 Directions
Future extensions I would like to explore include:
- Bowtie-style hazard visualization
- Barrier / control integrity intelligence
- Scenario and preparedness simulation
- richer analytics and management dashboards
- smarter decision-support and natural-language querying
> These are not yet part of the current Version 1 baseline, but represent the next stage of development I want to test against real operational data. 
---

## ⚠️ Data Governance

All data is anonymized or simulated to ensure compliance with professional and ethical standards.

- Sensitive identifiers are pseudonymized at ingestion  
- Site and organizational details are abstracted  
- Operational structure is preserved without exposing proprietary information  

---

## 🛠 Technical Skills

**Data & Analytics**
- R, Python, SQL, PostgreSQL  
- QA/QC workflows, ETL pipelines  
- Statistical modeling, GAMs, applied ML  

**Spatial Systems**
- PostGIS, QGIS, NetCDF  
- Spatio-temporal analysis & hotspot modeling  

**Dashboards & Tools**
- R Shiny, Streamlit  
- Decision-focused data applications  

---

## 🌱 Domain Experience

- Marine pollution & bioindicators
- Human health exposure screening
- Fisheries stock assessment
- Environmental monitoring systems
- HSE-Q indicators in regulated construction environments

---

## 🧾 Certificates
- 365 Data Science (in progress)
  - [Statistics](https://learn.365datascience.com/certificates/CC-AAD35FAB67/)
  - [Python](https://learn.365datascience.com/certificates/CC-35DE6E8ECC/)
  - [SQL](https://learn.365datascience.com/certificates/CC-8A7C7EED63/)
  - [Machine Learning in Python](https://learn.365datascience.com/certificates/CC-BA4E35B27D/)
- European Energy Centre — Renewable Energy & Energy Efficiency

---

## 🤳 Connect with me:
- 📧 Email: euchiejnpierre@gmail.com <br>
- 🔗 <a href="https://www.linkedin.com/in/euchiejnpierre/" target="_blank">LinkedIn</a>

---

<details>
<summary><strong>📖 About My Work Philosophy</strong></summary>

I don’t optimize for hype or black-box performance.  
I build systems that make **assumptions visible**, **uncertainty explicit**, and **decisions defensible** — especially where environmental and human consequences matter.

</details>
