# 🏥 Hospital Emergency Room Dashboard — Monthly Report

**Author:** Khushal Singh Sankhla
**Tool:** Microsoft Excel
**Domain:** Healthcare Analytics / Hospital Operations
**Report Period:** 2023 – 2024 (Monthly)

---
<img width="1547" height="628" alt="Image" src="https://github.com/user-attachments/assets/44f3d537-27c4-4c89-b817-77261a00e336" />

## 📌 Overview

The **Hospital Emergency Room Dashboard** is an interactive Excel-based monthly reporting tool designed to monitor and analyze emergency room operations. It provides hospital administrators and medical staff with real-time visibility into patient volume, wait times, satisfaction scores, department referrals, demographic breakdowns, and wait time risk levels — all filterable by year and month.

---

## 🎯 Objectives

- Track key ER performance metrics: patient count, wait time, and satisfaction score
- Monitor admission status and patient flow efficiency
- Analyze patient volume patterns by age group and hour of day
- Identify peak and least busy hours to optimize staffing
- Understand department referral distribution
- Evaluate wait time risk levels (Critical, Warning, Safe)
- Explore demographic breakdowns by gender and race

---

## 📈 Key Metrics (KPI Cards)

| Metric                     | Value       |
|----------------------------|-------------|
| No. of Patients            | 530         |
| Average Wait Time          | 35.11 mins  |
| Patient Satisfaction Score | 5.18 / 10   |

---

## 📊 Dashboard Components

### 1. Patients Attended Within Time (Pie Chart)
- **On Time:** 61%
- **Delayed:** 39%
> More than 1 in 3 patients experienced delays — a key area for improvement.

### 2. No. of Patients by Gender (Pie Chart)
- **Female:** 51%
- **Male:** 49%
> Near-equal gender distribution across ER visits.

### 3. Admission Status
| Status        | Patients | % of Total |
|---------------|----------|------------|
| Not Admitted  | 288      | 54.34%     |
| Admitted      | 242      | 45.66%     |

### 4. No. of Patients by Age Group (Bar Chart)
| Age Group | Patients |
|-----------|----------|
| 0–9       | 80       |
| 10–19     | 63       |
| 20–29     | 63       |
| 30–39     | 65       |
| 40–49     | 60       |
| 50–59     | 65       |
| 60–69     | 72       |
| 70–79     | 73       |
| 80+       | 69       |

> Elderly patients (60–79) form the largest ER visitor group.

### 5. No. of Patients by Department Referrals (Bar Chart)
| Department        | Patients |
|-------------------|----------|
| None (Walk-in)    | 307      |
| General Practice  | 109      |
| Orthopaedics      | 53       |
| Cardiology        | 12       |
| Gastroenterology  | 10       |
| Neurology         | 14       |
| Physiotherapy     | 18       |
| Renal             | 7        |

> The majority of ER patients (307) are walk-ins with no prior referral.

### 6. Patient Volume by Hour (Grouped Bar Chart)
- **Peak Hour:** 6:00 AM (highest patient volume)
- **Least Busy:** 13:00 (1:00 PM)
- Color-coded bars by hour for easy shift planning

### 7. Load vs Wait Time Analysis (Combo Line Chart)
- Dual-axis chart showing **Count of Patients** (bars) vs **Average Wait Time** (line) across dates
- Helps identify correlation between patient load and waiting times throughout the month

### 8. Race-wise Patient Analysis (Horizontal Bar Chart)
| Race / Ethnicity              | Patients |
|-------------------------------|----------|
| White                         | 138      |
| African American              | 101      |
| Two or More Races             | 77       |
| Declined to Identify          | 80       |
| Asian                         | 66       |
| Pacific Islander              | 42       |
| Native American/Alaska Native | 26       |

### 9. Patient Wait Time Risk Distribution (Donut Chart)
| Risk Level | Patients | Share |
|------------|----------|-------|
| Warning    | 229      | 43%   |
| Critical   | 202      | 38%   |
| Safe       | 99       | 19%   |

> 81% of patients fall in Warning or Critical wait time zones — indicating significant pressure on ER throughput.

---

## Filters / Slicers

| Slicer    | Options                                                              |
|-----------|----------------------------------------------------------------------|
| **Year**  | 2023, 2024                                                           |
| **Month** | Jan, Feb, Mar, Apr, May, Jun, Jul, Aug, Sep, Oct, Nov, Dec          |

All dashboard visuals update dynamically based on selected year and month.

---

## 🗂️ Dataset Details

| Attribute        | Details                                                              |
|------------------|----------------------------------------------------------------------|
| Report Type      | Monthly Emergency Room Report                                        |
| Years Covered    | 2023 – 2024                                                          |
| Patient Sample   | 530 (current view — August)                                          |
| Departments      | Cardiology, Gastroenterology, General Practice, Neurology, Orthopaedics, Physiotherapy, Renal |
| Demographics     | Gender (Male/Female), Age Groups (0–80+), Race/Ethnicity             |
| Risk Categories  | Critical, Warning, Safe                                              |

---

## 🛠️ Tools & Technologies

- **Visualization Tool:** Microsoft Excel (Pivot Charts, Pivot Tables, Slicers)
- **Data Source:** Excel Workbook (Hospital ER Patient Records)
- **Chart Types Used:** KPI Cards, Pie Charts, Bar Charts, Horizontal Bar Chart, Donut Chart, Combo Chart (Bar + Line), Grouped Bar Chart

---

## 🚀 How to Use

1. Open the `.xlsx` file in **Microsoft Excel** (2016 or later recommended)
2. Navigate to the **Dashboard** sheet
3. Use the **Year** buttons (2023 / 2024) to switch reporting periods
4. Use the **Month** slicer to filter all visuals to a specific month
5. All charts update dynamically — no manual refresh required
6. Hover over chart segments for exact patient counts and percentages

---

## 💡 Key Insights

- 🚨 **38% of patients are in Critical wait time** — immediate operational intervention needed
- ⏰ **Peak hour is 6:00 AM** — early morning staffing should be reinforced
- 👴 **Elderly patients (60–79)** represent the highest ER footfall by age group
- 📋 **307 out of 530 patients are walk-ins** — no prior referral, putting pressure on triage
- ⚡ **Only 61% of patients are attended on time** — 39% face delays
- 🏥 **45.66% admission rate** — nearly half of ER visitors require inpatient care
- 👩 **Women account for 51%** of ER visits, slightly outnumbering men

---

# 🌐 Connect With Me

<div align="center">

## 👨‍💻 Khushal Singh Sankhla

<p align="center">

  <a href="https://github.com/khushalsinghsankhla2808" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-khushalsinghsankhla2808-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>

  <a href="https://www.linkedin.com/in/khushal-singh-sankhla" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Khushal%20Singh%20Sankhla-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>

  <a href="mailto:khushalsinghsankhla203@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>

</p>

</div>

---

*This dashboard was created for healthcare analytics and hospital operations reporting, delivering actionable emergency room insights using Microsoft Excel.*
