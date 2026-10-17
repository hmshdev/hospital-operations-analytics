
# Hospital Operations & Resource Optimization Analytics

> **Dataset:** [https://www.kaggle.com/datasets/jaderz/hospital-beds-management](https://www.kaggle.com/datasets/jaderz/hospital-beds-management)

## Overview
This project explores hospital operations data to understand service demand, bed availability, admission outcomes, patient satisfaction, staff morale, and staff attendance.

## Business Problem
Hospital operations involve balancing patient demand with available resources. Analyzing weekly service data alongside patient records and staff schedules can help identify patterns that deserve further investigation.
This project will examine the relationship between service demand, reported bed capacity, admission refusals, and staff attendance.

## Business Questions
1. Which hospital services receive the highest number of patient requests?
2. How many patient requests are refused, and what is the refusal rate by service and week?
3. How does patient demand compare with reported available beds?
4. What patterns appear between staff attendance and service outcomes?
5. How do patient satisfaction and staff morale vary across services and weeks?
6. Are different patterns observed during weeks associated with recorded events?
7. Which services may warrant further investigation of resource allocation?

## Repository Structure
```text
hospital-operations-analytics/
├── dashboard/              
├── data/
│   ├── raw/                 
│   └── processed/           
├── docs/                    
├── notebooks/               
├── reports/                 
├── sql/                     
├── .gitignore
├── requirements.txt
└── README.md
```

## Dataset
| File | Rows | Columns | Description |
|---|---:|---:|---|
| `patients.csv` | 1,000 | 7 | Patient-level records, dates, service, and satisfaction |
| `services_weekly.csv` | 208 | 10 | Weekly service demand, admissions, refusals, bed availability, satisfaction, morale, and events |
| `staff.csv` | 110 | 4 | Staff identifiers, roles, and service assignments |
| `staff_schedule.csv` | 6,552 | 6 | Weekly staff schedule and attendance records |


## Technology Stack
- Pandas
- PostgreSQL
- Power BI
- Git and GitHub

## Project Workflow
1. Project setup and initial documentation
2. Data quality audit and validation using Python
3. Exploratory data analysis (EDA) using Python
4. PostgreSQL database schema design
5. CSV import and data validation in PostgreSQL
6. SQL-based business analysis and KPI calculations
7. Power BI data modeling and dashboard development
8. Findings, recommendations, and limitations
9. Final documentation and reproducibility checks

