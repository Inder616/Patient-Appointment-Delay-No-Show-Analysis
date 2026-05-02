<div align="center">

<img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
<img src="https://img.shields.io/badge/DAX-E84646?style=for-the-badge&logo=microsoftpowerbi&logoColor=white" />


<br/><br/>

```
                                                  PATIENT APPOINTMENT DELAY & NO-SHOW ANALYSIS
```

# 🏥 Patient Appointment Delay & No-Show Analysis

### *Understanding delays. Improving healthcare decisions.*

<br/>

[![Stars](https://img.shields.io/github/stars/Inder616/Netflix-content-strategy-dashboard?style=social)](https://github.com/Inder616/Patient-Appointment-Delay-No-Show-Analysis)
[![Forks](https://img.shields.io/github/forks/Inder616/Netflix-content-strategy-dashboard?style=social)](https://github.com/Inder616/Patient-Appointment-Delay-No-Show-Analysis)
[![LinkedIn](https://img.shields.io/badge/Connect-LinkedIn-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/inder-a61a57307/)

</div>

---

## 🔴 What Is This?

> **A fully interactive Power BI dashboard** that analyzes 110506+ patient appointments — revealing how appointment delays, age groups, and scheduling patterns drive no-show behavior, helping healthcare providers make smarter operational decisions.

No fluff. Pure signal.

---

## 📊 Dashboard at a Glance

<div align="center">

| Metric | What It Answers |
|--------|----------------|
| 🎯 **KPI Cards** | How many patients? What's the no-show rate? |
| ⏳ **Delay Analysis** | How does wait time impact no-show risk? |
| 👥 **Demographics** | Which age groups and genders miss the most? |
| 📅 **Day Analysis** | Which weekdays have the longest waits? |
| 📈 **Waiting Groups** | At what point does no-show risk spike? |
| ⚠️ **Risk Tracker** | How many patients are in the high-risk zone? |

</div>

---

## 🚀 Key Business Insights

<table>
<tr>
<td width="50%">

### ⏰ The 5-Day Threshold
- No-show rate **jumps from 9% → 23%** once wait time exceeds 2 days
- Keeping appointments **under 5 days** is the single biggest lever to reduce no-shows

</td>
<td width="50%">

### 👶 Age Group Patterns
- **Teens have the highest no-show rate (25.96%)**
- Seniors are the most reliable — only **15.20%** miss their appointments

</td>
</tr>
<tr>
<td width="50%">

### 📅 Day-of-Week Effect
- **Monday has the longest average wait (9.84 days)**
- Saturday appointments are scheduled fastest at **3.23 days**

</td>
<td width="50%">

### ⚠️ High-Risk Volume
- **45,000 patients** fall in the high-delay category
- High-delay patients carry a **31.47% no-show rate** — over 3× the low-delay group

</td>
</tr>
</table>

---

## 🧠 Strategic Recommendations

```
┌─────────────────────────────────────────────────────────────────┐
│  1. ⏳  Cap appointment wait time at 5 days wherever possible   │
│  2. 📲  Send SMS/call reminders for high-delay appointments     │
│  3. 👶  Create teen-specific outreach — highest at-risk group   │  
└─────────────────────────────────────────────────────────────────┘
```

---

## 🛠️ Tech Stack

```
Data Pipeline
─────────────
Excel Dataset  ──►  Python (Clean & Prep)  ──►  Power BI
                                                   │
                                       ┌───────────┴───────────┐
                                  Power Query              DAX Measures
                               (Transformations)      (No-Show %, Avg Wait)
```

| Layer | Tool | Purpose |
|-------|------|---------|
| 🐍 **Python** | Pandas | Data cleaning & preprocessing |
| 📑 **Excel** | — | Raw data storage & initial validation |
| 🔄 **Power Query** | Data Transformation | Column shaping, type fixes, filtering |
| 📐 **DAX** | Measures | No-Show %, KPIs, risk group calculations |
| 📊 **Power BI** | Desktop | Dashboard, visualizations, interactivity |

---

## 📁 Dataset Details

> **Source:** [Healthcare appointment dataset containing patient scheduling records with attendance outcomes.](https://www.kaggle.com/datasets/joniarroba/noshowappointments?utm_source=chatgpt.com&select=KaggleV2-May-2016.csv)

**Dataset includes:**
- Patient demographics (Age Group, Gender)
- Appointment scheduling information (Appointment Day, Waiting Days)
- Attendance outcome (Show / No-show)
- Delay classification (Low / Medium / High)

**⚠️ Note on Waiting Days:**
Waiting days represent the gap between scheduling date and appointment date. 
Patients with same-day or short wait times (`0–1 days`) show the lowest no-show rate (~9%), indicating that shorter waiting periods improve attendance.

---

## 📸 Dashboard Preview

![Dashboard](Patient-Appointment-Delay-No-Show-Analysis/Image/dashboard_preview.png)

---

### 🔗 Repository Link
[Open Repository](https://github.com/Inder616/Patient-Appointment-Delay-No-Show-Analysis)

---

## ▶️ How to Run

```bash
# Step 1 — Clone this repo
git clone https://github.com/yourusername/patient-noshow-dashboard.git

# Step 2 — Open the dashboard
# Launch Power BI Desktop → Open File → select the .pbix file

# Step 3 — Explore
# Use filters (Gender, Age Group, Delay Category) to slice every visual
```

---

## 👤 About the Author

<div align="center">

**Aspiring Data Analyst** passionate about transforming raw data into decisions that matter.

`Excel` · `Python` · `Power BI` · `DAX` · `Healthcare Analytics`

[![LinkedIn](https://img.shields.io/badge/Let's%20Connect-LinkedIn-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/inder-a61a57307/)

</div>

---

<div align="center">

*Built with 🎬 for the data-curious and the strategy-obsessed*

⭐ **If this project helped you, drop a star!** ⭐

</div>

