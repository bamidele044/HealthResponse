# Emergency Incident Monitoring and Automation System

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset Source](#dataset-source)
- [Dataset Overview](#dataset-overview)
- [System Architecture](#system-architecture)
- [Tools Used](#tools-used)
- [Dashboard Preview](#dashboard-preview)
- [Dashboard Pages](#dashboard-pages)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Key Insights](#key-insights)
- [Recommendations](#recommendations)
- [Business Impact](#business-impact)

### Project Overview

HealthResponse Ltd operates in a fast paced emergency environment where manual reporting, fragmented data sources, and delayed updates previously slowed operational decision making. This project delivered a fully automated, real time emergency incident monitoring system by integrating Google Sheets, Looker Studio, Microsoft Forms, and Power Automate.

The solution centralises 3,000 emergency incidents, improves data accuracy, accelerates response visibility, and enhances operational oversight. Key insights highlight high incident volumes in major cities, a 37.83‑minute average response time, and a significant proportion of mental‑health‑related emergencies.

### Dataset Source

The primary dataset was provided directly by HealthResponse Ltd and stored in Google Sheets as the central data repository.
This dataset served as the foundation for the dashboards, automation workflows, and performance insights generated throughout the project.

### Dataset Overview

The dataset contains 3,000 emergency incident records, with key fields including:
- Incident type
- Priority level
- Response time
- Location
- Patient condition
- Intervention type
- Outcome

These fields enabled comprehensive monitoring of incident trends, patient outcomes, and operational performance.

### System Architecture
1. Data Source
- Google Sheets (primary dataset)

2. Dashboard Layer
- Looker Studio for real‑time visualisation
- Two‑page dashboard consisting of:
  - Page 1: Executive Overview & Response Performance
  - Page 2: Patient Outcomes & Geographic Analysis

3. Form Input
- Microsoft Forms used to simulate new incident submissions
- Captures structured incident details for automated processing

4. Automation Layer (Power Automate)
A Power Automate flow was developed to:
- Trigger on new form submissions
- Retrieve and validate incident details
- Format date/time fields
- Insert new rows into Google Sheets
- Send email alerts for critical incidents
This ensures real‑time updates, accurate logging, and immediate escalation handling.

### Tools Used
- Google Sheets: dataset storage
- Looker Studio: real‑time dashboards
- Microsoft Forms: structured incident submission
- Power Automate: workflow automation and alerting

### Dashboard Preview

<img width="898" height="507" alt="Screenshot 2026-05-01 033018" src="https://github.com/user-attachments/assets/ccf6f178-211f-4e0d-af6a-8f90fc71d020" />

<img width="892" height="507" alt="Screenshot 2026-05-01 033112" src="https://github.com/user-attachments/assets/40381539-c19d-4038-8bcf-6ef9f48aa0b5" />

### Dashboard Pages

- Page 1: Executive Overview and Response Performance  
Incident trends, response times, priority levels, intervention types, and team efficiency.
- Page 2: Patient Outcomes and Geographic Analysis  
Patient demographics, condition insights, outcome distribution, and incident location analysis.

### Exploratory Data Analysis
1. What does the incident volume and trend show?
- 3,000 total incidents recorded
- Activity remains steady throughout the year
- High‑severity cases (Critical: 607) require rapid escalation handling

2. Which incident types are most common?
- Mental Health Crisis (605)
- Welfare Check (468)
- Suicide Risk (378)
- Self‑Harm Alert (310)
This reflects the mental‑health‑focused nature of HealthResponse’s operations.

3. What geographic patterns were identified?
Highest incident volumes occurred in:
- Bristol
- Nottingham
- Greater London
These regions require prioritised resource allocation.

4. What do patient demographics and conditions reveal?
- Majority of patients arrive distressed or stable
- Age distribution is broad, with 18-45 being the largest group
- Gender split is balanced across male and female categories

5. How efficient is the response performance?
- Average response time: 37.83 minutes
- Response time by priority:
  - Critical: 14.03 minutes
  - High: 24.82 minutes
  - Medium: 42.36 minutes
  - Low: 88.07 minutes
 
6. Which interventions and outcomes are most common?
Most used interventions:
- On‑site assessments
- Emergency transport
- De‑escalation support
- Remote counselling

Most common outcomes:
- Resolved on site
- Follow‑up required
- Referred to hospital
These patterns demonstrate strong frontline intervention capability.

### Key Insights

- Mental‑health‑related emergencies dominate incident categories
- Major cities show the highest incident density
- Response times are strong for high‑severity cases
- On‑site resolution is the most common outcome
- De‑escalation and remote counselling are heavily utilised

### Recommendations

1. Strengthen Escalation Protocols
- Improve triage workflows
- Ensure rapid notification pathways for critical cases

2. Optimise Deployment Using Geographic Insights
- Allocate more resources to high‑volume regions
- Adjust shift patterns based on incident density

3. Add SMS Alerts for Critical Cases
- Faster escalation beyond email
- Ensures immediate awareness for field teams

4. Review KPIs Monthly
- Track response time improvements
- Monitor shifts in incident types
- Identify emerging hotspots

5. Explore Predictive Analytics
- Forecast incident surges
- Predict high‑risk locations
- Improve proactive resource planning

### Business Impact

This automated system enables HealthResponse Ltd to:
- Improve real‑time response visibility
- Reduce manual reporting delays
- Enhance data accuracy
- Strengthen escalation handling
- Optimise resource deployment
- Support long‑term operational scalability
The solution provides a scalable foundation for future enhancements, including predictive analytics and advanced resource optimisation.
