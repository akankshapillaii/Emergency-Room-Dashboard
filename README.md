# Emergency-Room-Dashboard
An interactive Power BI healthcare analytics dashboard designed to analyze Emergency Room operations across 19 months (April 2023 – October 2024). The report transforms patient-level data into actionable insights around patient volume, wait times, satisfaction, referrals, admissions, demographics, and peak operating periods.

The objective is to help hospital stakeholders understand where operational pressure occurs, identify potential bottlenecks, and make more informed decisions around staffing, patient flow, referrals, and service quality.

## Executive Summary

The Emergency Room dashboard analyzes 9,216 patient records across a 19-month period.

The analysis highlights three major operational areas:

- Patient flow: Average patient wait time was 35.3 minutes, while the report tracks the proportion of patients seen within 30 minutes.
- Patient experience: Average patient satisfaction was 4.99/10, providing a metric for monitoring the relationship between operational performance and patient experience.
- Demand patterns: Patient volumes vary significantly by day and hour, with Monday, Saturday, and Tuesday among the busiest days and 11 AM, 1 PM, 7 PM, and 11 PM identified as high-volume hours.
- Referral demand: General Practice and Orthopedics account for the largest number of departmental referrals.
- Admission pattern: 4,612 patients were admitted, while 4,604 were not admitted, creating an almost even split between the two outcomes.

The dashboard converts these patterns into an operational view that can support resource planning, patient-flow monitoring, and performance improvement.

## Table of Contents
- Business Problem
- Dashboard
- Key Stakeholders
- Project Workflow
- Data Structure
- Dashboard Pages
- Key KPIs
- Key Findings
- Business Recommendations
- Tools & Technologies
- Conclusion

## Business Problem
Emergency departments handle continuously changing patient volumes, making it difficult to monitor operational performance using raw patient-level data alone.

The analysis focuses on answering the following business questions:

How many patients are visiting the Emergency Room over time?
What is the average patient wait time?
How effectively are patients being seen within 30 minutes?
When are the busiest days and hours?
Which departments receive the highest number of referrals?
What is the admission versus non-admission pattern?
How does patient satisfaction vary with operational activity?
What demographic groups represent the largest share of ER visits?
Where should hospital management investigate opportunities to improve patient flow and resource allocation?

The goal was to transform these questions into a decision-ready Power BI dashboard rather than simply presenting descriptive charts.

## Dashboard
Power Bi Report: [View Dashboard](https://github.com/akankshapillaii/Emergency-Room-Dashboard/blob/main/Hospital%20Emergency%20Room%20Dashboard.pbix)

The Power BI report contains four analytical pages:
| Dashboard Page	| Business Question|
|-----|------|
| Monthly View	| How is ER performance changing month by month? |
| Consolidated View	| What are the overall operational patterns across the complete period? |
| Patient Details	| What does the underlying patient-level data look like? |
| Key Takeaways	| What are the most important findings from the analysis? |

## Key Stakeholders
- **Hospital Management** — Monitor overall emergency-room performance and support operational decision-making
- **Emergency Department Managers** — Track patient flow, waiting times, admissions, and peak periods
- **Doctors & Department Heads** — Understand referral patterns and departmental demand
- **Operations & Nursing Teams** — Support staffing and resource allocation based on patient-volume trends
- **Data / BI Teams** — Maintain analytical reporting, KPIs, and performance monitoring
  
## Workflow

Business Understanding → Data Walkthrough → Data Cleaning & Quality Checks → Data Modeling → DAX Measures & KPI Development → Dashboard Design → Interactive Visualization → Trend & Performance Analysis → Business Insights → Recommendations

## Data Structure
The report uses two primary analytical components:
- Hospital ER_Data
- Date Table

<p align="center">
     <img src="Dashboard_Pages_Preview/Data Model.png" width="70%">   
</p>

The model enables the report to move between daily, monthly, demographic, operational, and patient-level analysis.

## Tools & Technologies
- **Power BI** — Interactive dashboard development, KPI cards, filters, and data visualization
- **Power Query** — Data cleaning, transformation, validation, and preparation
- **DAX** — KPI and calculated measure development for patient volume, wait time, satisfaction, referrals, and admissions
- **Data Modeling** — Structured relationships for patient, demographic, referral, and time-based analysis
- **Data Visualization** — Interactive charts, tables, and KPI visuals for clear performance reporting
- **Data Analytics** — Exploratory analysis, trend identification, KPI development, and insight generation

## Dashboard Pages
Monthly View | Consolidated View | Patient Details | Key Takeaways
<table>
  <tr>
    <td><img src="Dashboard_Pages_Preview/ER Final Dashboard.png" width="400"></td>
    <td><img src="Dashboard_Pages_Preview/Consolidated view.png" width="400"></td>
  </tr>
  <tr>
    <td><img src="Dashboard_Pages_Preview/Patient Details.png" width="400"></td>
    <td><img src="Dashboard_Pages_Preview/Key takeaways.png" width="400"></td>
  </tr>
</table>
  
## 💡 Key Takeaways
| Area | Key Finding |
|---|---|
| **Patient Volume** | **9,216 patients** analyzed across 19 months |
| **Wait Time** | Average wait time of **35.3 minutes** |
| **Satisfaction** | Average satisfaction score of **4.99/10** |
| **Referrals** | **General Practice (1,840)** and **Orthopedics (995)** had the highest referrals |
| **Peak Periods** | Highest patient volumes occurred on **Monday, Saturday & Tuesday** |
| **Age Group** | **30–39 years (1,200)** was the largest patient age group |
| **Admissions** | **4,612 admitted** vs. **4,604 treated & released** |

## 🔍 Deep Dive Analysis & Findings

### Understanding the Emergency Room Through Data
Across **9,216 patient visits over 19 months**, the analysis reveals that emergency-room activity is not evenly distributed. Looking beyond overall patient volume helps identify **when demand increases, where it is concentrated, and how patients move through the system**.

### Demand Has Distinct Peaks
Patient activity was highest on **Monday (1,377 visits), Saturday (1,322), and Tuesday (1,318)**. At the hourly level, **11 AM, 1 PM, 7 PM, and 11 PM** emerged as notable high-volume periods.

> **Finding:** Patient demand follows identifiable time patterns that can help inform staffing and resource planning.

### Referrals Reveal Demand Concentration
**5,400 patients required no department referral**, while **General Practice (1,840)** and **Orthopedics (995)** recorded the highest referral volumes among referred patients.

> **Finding:** Referral demand is concentrated in specific departments, highlighting areas where further capacity and patient-flow analysis may be valuable.

### Waiting Time Adds Another Layer
The average waiting time was **35.3 minutes**, alongside an average patient satisfaction score of **4.99/10**.

> **Finding:** These metrics provide an opportunity to investigate whether patient experience varies across waiting-time categories and periods of higher demand.

### Patient Outcomes Are Almost Evenly Split
The analysis recorded **4,612 admissions** compared with **4,604 treated-and-released patients**.

> **Finding:** Patient volume alone does not fully capture ER workload; patient outcomes provide an additional perspective for understanding operational demand.

### Overall Finding
The analysis moves beyond **“How many patients visited?”** to understand **when demand peaks, where referrals are concentrated, how long patients wait, and what happens after their visit**.

By bringing these dimensions together, the dashboard provides a data-driven view of emergency-room operations and highlights areas where **patient flow, staffing, and resource planning can be explored further**.
