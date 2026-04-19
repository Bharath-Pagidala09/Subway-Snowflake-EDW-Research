# Subway Snowflake EDW Research (Data Management Strategy Analysis)

## ⚠️ Note
This is a research and written analysis report — it does not contain 
any code. It was produced as part of an MSc Business Analytics module 
on Data Management Strategies and Technologies.

---

## Overview
This report critically evaluates the technical and managerial impact 
of adopting a cloud-based Enterprise Data Warehouse (EDW) using 
Snowflake as a new data management technology for Subway, one of the 
world's largest quick-service restaurant chains. The analysis examines 
Subway's existing data infrastructure, identifies key limitations, 
proposes a solution and evaluates its benefits and risks from both 
technical and business perspectives.

---

## What Was Done

### 1. Company Identification and Existing Data Strategy
Subway operates approximately 37,000 locations across 100+ countries 
and has been undergoing a major digital transformation in partnership 
with Capgemini. Key existing improvements include a modernised mobile 
app and website, direct integration of digital orders with in-store 
PoS systems, an automated menu publication system and smart fridge 
technology. Despite this progress, Subway continued to rely on 
fragmented legacy infrastructure limiting global analytics, 
governance and scalable data access.

---

### 2. Proposed Technology — Snowflake EDW
A cloud-based Enterprise Data Warehouse (EDW) using Snowflake was 
proposed to centralise data from multiple sources including PoS 
systems, mobile apps, inventory databases and customer feedback 
platforms. Key features of the proposed solution:

- Separation of storage and compute for dynamic scalability
- Support for semi-structured data formats such as JSON
- Real-time data ingestion via ETL/ELT pipelines using tools 
  like Fivetran
- Role-based access control (RBAC) for secure franchise-wide 
  data sharing
- BI integration with Tableau and Power BI for real-time dashboards
- Compliance with GDPR and CCPA across global operations

---

### 3. Technical Evaluation
The EDW architecture was mapped across three decision levels aligned 
with Devon's Information Systems Model:

- **Operational level** — store managers access real-time dashboards 
  for stock, staffing and service performance
- **Tactical level** — marketing and supply chain teams use 
  behavioural data and demand alerts
- **Strategic level** — corporate leadership monitors KPIs including 
  franchise profitability, digital engagement and customer loyalty

The solution also aligns with Porter's Value Chain, improving both 
primary activities (inbound logistics, operations, service) and 
support activities (HR, procurement, technology infrastructure).

---

### 4. Managerial Evaluation
Key business benefits identified:

- Centralised data access across 37,000+ global franchise locations
- Predictive analytics for demand forecasting and staffing optimisation
- Hyper-personalised marketing campaigns based on unified customer data
- Automated workflows reducing manual processing time by approximately 75%
- Improved franchisee empowerment through location-specific dashboards

---

### 5. Risks and Mitigation Strategies

| Risk | Mitigation |
|---|---|
| Data migration errors | Staged migration with sandbox testing and rollback procedures |
| Unpredictable cloud costs | Automated budget controls and real-time cost dashboards |
| User adoption resistance | Training programmes and Cloud Centre of Excellence (CCoE) |
| Vendor lock-in | Hybrid-cloud approach with open-source ETL tools |
| Legacy system integration | Phased deployment with compatibility testing |

---

## Key Takeaway
Implementing Snowflake as a cloud-based EDW positions Subway to 
transition from a reactive, fragmented data environment to a 
predictive, data-first enterprise. The solution addresses existing 
infrastructure limitations while enabling real-time decision-making, 
stronger governance and scalable analytics across its entire global 
franchise network.

---

## Technologies Referenced
- **Snowflake** — cloud-based Enterprise Data Warehouse
- **Fivetran** — automated ETL/ELT data pipeline tool
- **Tableau / Power BI** — business intelligence and dashboards
- **ActiveBatch** — workload automation
- **NetSuite Analytics Warehouse** — finance and IT reporting

---

## Type of Work
This is a **research and written analysis report** produced using 
academic and industry sources. No datasets or code files are included. 
The full report is available as a PDF in this repository.
