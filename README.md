# 🏥 Hospital Operations Analytics Dashboard

## Project Overview

This project is an end-to-end healthcare analytics solution that combines Python-based data preparation and analysis with Power BI dashboard development.

The goal was to investigate hospital operational performance, identify capacity bottlenecks, understand patient refusal patterns, evaluate staffing pressure, and provide data-driven recommendations for improving healthcare operations.

---

## Project Workflow

### 1. Data Preparation (Python)

The project started with multiple hospital-related datasets containing information about:

- Patients
- Hospital Services
- Staffing Levels
- Staff Schedules
- Operational Events

Python was used to:

- Clean raw datasets
- Handle missing values
- Standardize formats
- Create analytical features
- Aggregate operational metrics
- Generate service-level summaries
- Prepare data for Power BI

---

## Tools Used

- Python
- Pandas
- NumPy
- Jupyter Notebook
- Power BI
- DAX
- Data Visualization
- GitHub

---

## Feature Engineering

Several business metrics were created during the analysis:

- Admission Rate
- Refusal Rate
- Bed Utilization
- Capacity Gap
- Average Satisfaction
- Present Staff
- Absent Staff
- Absence Rate
- Patients per Staff
- Requests per Staff

---

# Dashboard Preview

## Page 1 — Hospital Capacity & Operational Performance Overview

![Page 1](images/page1.png)

### Objectives

This page provides a high-level operational overview of the hospital.

### KPIs

- Total Requests
- Total Admissions
- Refusal Rate
- Bed Utilization
- Patient Satisfaction
- Absence Rate
- Capacity Gap

### Key Insight

Emergency services experienced the highest refusal rates, while patient satisfaction remained relatively stable across departments.

---

## Page 2 — Staffing & Operational Pressure

![Page 2](images/page2.png)

### Objectives

Analyze staffing pressure and workload distribution across hospital services.

### KPIs

- Present Staff
- Absent Staff
- Absence Rate
- Patients per Staff
- Requests per Staff

### Key Insight

Operational pressure is concentrated in Emergency and General Medicine services. Refusal patterns vary significantly across departments, suggesting differences in operational efficiency and resource utilization.

---

## Page 3 — Operational Impact on Patient Experience

![Page 3](images/page3.png)

### Objectives

Understand how operational performance affects patient experience and admissions.

### KPIs

- Admission Rate
- Average Satisfaction
- Bed Utilization
- Total Refused Patients
- Capacity Gap

### Key Insight

Patient refusals remained high even during normal operating periods, suggesting underlying capacity limitations rather than temporary external events.

---

## Page 4 — Operational Bottlenecks & Strategic Recommendations

![Page 4](images/page4.png)

### Objectives

Identify root causes of operational inefficiencies and summarize strategic actions.

### Root Cause Summary

- High bed utilization is strongly associated with higher refusal rates.
- Emergency services experienced the highest refusal rates.
- Refusals remained elevated even in the absence of operational events.
- Operational pressure appears to be driven by structural capacity limitations.

### Recommendations

- Improve patient flow and admission coordination in Emergency services.
- Optimize bed allocation across departments.
- Monitor high-utilization services proactively.
- Investigate operational causes behind emergency patient refusals.
- Increase flexibility in handling periods of elevated demand.

---

# Exploratory Data Analysis (Python)

The following analyses were performed in Python before building the dashboard.

---

## Correlation Matrix

![Correlation Matrix](images/correlation_matrix.png)

### Purpose

Identify relationships between operational metrics and determine which factors have the strongest association with patient refusals and hospital performance.

---

## Event Impact Analysis

![Event Impact](images/event_impact.png)

### Purpose

Evaluate how operational events influence patient demand, admissions, and refusal patterns.

---

## Patients by Service

![Patients by Service](images/patients_by_service.png)

### Purpose

Compare patient distribution across hospital services and identify departments experiencing the highest demand.

---

## Service Pressure Analysis

![Service Pressure](images/service_pressure.png)

### Purpose

Measure workload intensity across departments and identify areas under the greatest operational pressure.

---

# Key Findings

- Emergency services showed the highest refusal rates.
- Bed utilization and refusal rates exhibited a strong positive relationship.
- Patient refusals persisted even without major operational events.
- General Medicine handled the largest share of patient demand.
- Capacity limitations appeared to be a larger issue than temporary external disruptions.

---

# Business Value

This dashboard supports hospital decision-makers by helping them:

- Monitor operational performance
- Detect service bottlenecks
- Track staffing pressure
- Understand refusal behavior
- Improve capacity planning
- Support data-driven operational decisions

---

# Author

**Reem Mohamednur**

Bioengineering Graduate | Data Analytics Enthusiast

Python • Power BI • Healthcare Analytics • Data Visualization
