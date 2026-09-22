# Emergency-Room-Dashboard
An interactive Power BI dashboard developed to analyze hospital emergency-room performance, patient flow, waiting times, admissions, referrals, demographics, and patient satisfaction.

[View Dashboard](https://github.com/akankshapillaii/Emergency-Room-Dashboard/blob/main/Hospital%20Emergency%20Room%20Dashboard.pbix)

# Business Problem
Hospital emergency departments experience fluctuating patient volumes, making it challenging to monitor patient flow, waiting times, admissions, referrals, and overall operational performance. A centralized dashboard was needed to bring these metrics together and provide clear insights for informed decision-making.

# Business Objective
Develop an interactive reporting solution to help hospital administrators:
- Monitor patient volume and emergency-room activity
- Track average waiting time and service timeliness
- Analyze admission and referral patterns
- Identify peak patient periods
- Understand patient demographics
- Monitor patient satisfaction

# Key Stakeholders
- **Hospital Management** — Monitor overall emergency-room performance and support operational decision-making
- **Emergency Department Managers** — Track patient flow, waiting times, admissions, and peak periods
- **Doctors & Department Heads** — Understand referral patterns and departmental demand
- **Operations & Nursing Teams** — Support staffing and resource allocation based on patient-volume trends
- **Data / BI Teams** — Maintain analytical reporting, KPIs, and performance monitoring

# Project Objectives
The main objectives of this project were to:
- Analyze emergency-room patient volume and flow.
- Monitor key operational KPIs.
- Analyze patient waiting times.
- Understand admission patterns.
- Identify demographic trends.
- Analyze department referral patterns.
- Identify peak periods of emergency-room activity.
- Build an interactive reporting solution for decision-making.

# Project Workflow
**Requirements → Data Cleaning → Data Transformation → Data Modeling → DAX → Dashboard Development → Insights**
- Cleaned and transformed raw healthcare data using **Power Query**
- Built relationships and prepared the **data model** for analysis
- Created **DAX measures** for key operational KPIs
- Designed an **interactive dashboard** with filters and multiple report views
- Analyzed patient trends across **time, demographics, admissions, and referrals**

# Tools & Technologies
- **Power BI** — Interactive dashboard development, KPI cards, filters, and data visualization
- **Power Query** — Data cleaning, transformation, validation, and preparation
- **DAX** — KPI and calculated measure development for patient volume, wait time, satisfaction, referrals, and admissions
- **Data Modeling** — Structured relationships for patient, demographic, referral, and time-based analysis
- **Data Visualization** — Interactive charts, tables, and KPI visuals for clear performance reporting
- **Data Analytics** — Exploratory analysis, trend identification, KPI development, and insight generation

# Dashboard Pages
Monthly View | Consolidated View | Patient Details | Key Takeaways
<table>
  <tr>
    <td><img src="Dashboard Preview/ER Final Dashboard.png" width="400"></td>
    <td><img src="Dashboard Preview/Consolidated view.png" width="400"></td>
  </tr>
  <tr>
    <td><img src="Dashboard Preview/Patient Details.png" width="400"></td>
    <td><img src="Dashboard Preview/Key takeaways.png" width="400"></td>
  </tr>
</table>
  
# 💡 Key Takeaways
| Area | Key Finding |
|---|---|
| **Patient Volume** | **9,216 patients** analyzed across 19 months |
| **Wait Time** | Average wait time of **35.3 minutes** |
| **Satisfaction** | Average satisfaction score of **4.99/10** |
| **Referrals** | **General Practice (1,840)** and **Orthopedics (995)** had the highest referrals |
| **Peak Periods** | Highest patient volumes occurred on **Monday, Saturday & Tuesday** |
| **Age Group** | **30–39 years (1,200)** was the largest patient age group |
| **Admissions** | **4,612 admitted** vs. **4,604 treated & released** |

# 🔍 Deep Dive Analysis & Findings

## Understanding the Emergency Room Through Data
Across **9,216 patient visits over 19 months**, the analysis reveals that emergency-room activity is not evenly distributed. Looking beyond overall patient volume helps identify **when demand increases, where it is concentrated, and how patients move through the system**.

## Demand Has Distinct Peaks
Patient activity was highest on **Monday (1,377 visits), Saturday (1,322), and Tuesday (1,318)**. At the hourly level, **11 AM, 1 PM, 7 PM, and 11 PM** emerged as notable high-volume periods.

> **Finding:** Patient demand follows identifiable time patterns that can help inform staffing and resource planning.

## Referrals Reveal Demand Concentration
**5,400 patients required no department referral**, while **General Practice (1,840)** and **Orthopedics (995)** recorded the highest referral volumes among referred patients.
> **Finding:** Referral demand is concentrated in specific departments, highlighting areas where further capacity and patient-flow analysis may be valuable.

## Waiting Time Adds Another Layer
The average waiting time was **35.3 minutes**, alongside an average patient satisfaction score of **4.99/10**.
> **Finding:** These metrics provide an opportunity to investigate whether patient experience varies across waiting-time categories and periods of higher demand.

## Patient Outcomes Are Almost Evenly Split
The analysis recorded **4,612 admissions** compared with **4,604 treated-and-released patients**.
> **Finding:** Patient volume alone does not fully capture ER workload; patient outcomes provide an additional perspective for understanding operational demand.

## Overall Finding
The analysis moves beyond **“How many patients visited?”** to understand **when demand peaks, where referrals are concentrated, how long patients wait, and what happens after their visit**.
By bringing these dimensions together, the dashboard provides a data-driven view of emergency-room operations and highlights areas where **patient flow, staffing, and resource planning can be explored further**.
