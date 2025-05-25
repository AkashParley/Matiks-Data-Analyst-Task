# 📊 Matiks - Data Analyst Challenge

This repository contains my completed project for the **Matiks Data Analyst Task**, designed to showcase how I extract insights from data, communicate findings clearly, and build data-driven dashboards.

---

## 🚀 Overview

- **Company**: Matiks
- **Task**: Analyze behavioral and revenue data to identify key patterns and suggest growth opportunities.
- **Tools Used**: 
  - 🐍 Python (Pandas, Seaborn, Matplotlib)
  - 📊 Tableau (Interactive dashboard)
  - 📁 Excel (source data)

---
## 📎 Dataset

> [Matiks Dataset](https://docs.google.com/spreadsheets/d/1NyFJYCi5wF8QD0FIfxlyvYKksnnbKExzXOjioE_1hWA/edit?usp=sharing) (Google Sheets)

---
## 🔍 What’s Inside

| Folder | Contents |
|--------|----------|
| `notebooks/` | Python code for exploratory analysis, churn detection, user segmentation |
| `dashboard/` | Tableau dashboard link + screenshots |
| `insights_report/` | Final summary report (3–5 slides) with recommendations |
| `data/` | Dataset used for this task (source referenced) |

---

## 📈 Key Insights

- **Churn Risk**: Identified users with high churn risk based on inactivity and short sessions.
- **High-Value Users**: Users in the top 10% revenue mostly came from specific countries and subscription tiers.
- **Referral Sources**: Organic search users showed better retention and higher average revenue.

See detailed visuals and narrative in the [insights report](https://github.com/AkashParley/Matiks-Data-Analyst-Task/tree/main/insights).

---

## 📊 Dashboard Preview

- Built in **Tableau** to track:
  - DAU / WAU / MAU trends 📆
  - Revenue over time 💰
  - Breakdown by device, subscription tier, and game mode 🎮
  - Referral channel impact on user behavior 🌐

> 🔗 **[View Dashboard on Tableau Public](https://public.tableau.com/views/MatiksDashboard/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**  
<img width="1463" alt="Matiks_Dashboard" src="https://github.com/user-attachments/assets/a714d48e-7365-4e0c-a598-249c76d53a8a" />


---
## 🧪 Detailed Findings from Python Analysis

In addition to the Tableau dashboard, two in-depth analyses were conducted using Python to extract deeper insights:
<img width="588" alt="Screenshot 2025-05-25 at 4 02 12 AM" src="https://github.com/user-attachments/assets/956466e5-c0dd-4699-ac22-481fd39208a3" />   
<img width="449" alt="Screenshot 2025-05-25 at 4 02 45 AM" src="https://github.com/user-attachments/assets/9eae7aa5-083b-44e5-a516-6e636a499f68" /> <img width="462" alt="Screenshot 2025-05-25 at 4 02 57 AM" src="https://github.com/user-attachments/assets/a5a022f3-6dd0-47b6-b130-b1f44ccdbf26" />

<img width="552" alt="Screenshot 2025-05-25 at 4 04 05 AM" src="https://github.com/user-attachments/assets/d2fbb1d2-f4ff-40f6-92c1-16a5ca55543d" />  <img width="575" alt="Screenshot 2025-05-25 at 4 03 47 AM" src="https://github.com/user-attachments/assets/ced5466b-a772-4b69-860e-28ee846d25fb" />




---

### 📍 Task 1: Churn Risk & User Behavior

**Objective:** Detect early signs of churn and behavioral patterns.

#### 🔍 Key Findings:

- Users inactive for more than **30 days** were flagged as **churn-risk**.
- Users with **<10 sessions** and **<5 hours total playtime** were labeled **short session users**.
- A notable portion of users showed **sharp activity drop-offs**, especially post day-7.
- Visualizations revealed a **long tail of infrequent users**, signaling opportunities for re-engagement.

---

### 📍 Task 2: High-Value & High-Retention User Segments

**Objective:** Identify traits of top-performing user groups.

#### 🔍 Key Findings:

- **High-Value Users** (top 10% by revenue):
  - Tend to use premium subscription tiers and specific game modes.
  - Are often early adopters with higher session frequency.

- **High-Retention Users** (>30 sessions & >60 active days):
  - Show consistent engagement over time.
  - Tend to cluster in certain device types and regions.

These insights were visualized with styled tables and charts to understand what distinguishes top-tier users from the broader user base.


## 📌 Summary of Key Insights

| Area               | Insight                                                                 |
|--------------------|-------------------------------------------------------------------------|
| **Behavioral Patterns** | Peak usage times and high-frequency users stand out.                   |
| **Churn Risk**         | Gaps >7 days and <2-minute sessions signal potential churn.            |
| **High-Value Users**   | Frequent, early adopters with strong feature usage.                    |
| **Suggestions**        | Re-engagement, onboarding, loyalty programs, and personalization.     |


---
## 💡 Suggestions to Improve Retention or Revenue

Based on the insights gathered, the following **actionable recommendations** can help improve user retention and boost revenue:

- 🔁 **Send re-engagement notifications** after periods of inactivity (e.g., 7+ days)
- 🧪 **Improve onboarding** with tutorials or walkthroughs targeted by user type
- 🏆 **Introduce loyalty programs** to reward frequent or long-term users
- 📬 **Deliver personalized content** or game feature highlights to keep users engaged
- 📈 **Run A/B tests** to reduce early churn and gather direct user feedback

> Implementing these strategies can significantly increase user satisfaction, reduce churn, and grow lifetime value.

---


## 🧠 About Me

I’m passionate about transforming raw data into actionable business insights through storytelling, visualization, and analytics. Connect with me on [LinkedIn](https://www.linkedin.com/in/akash-parley-9446292a8).

---

## 📬 Submission

✅ Completed via Python, Tableau, and documented in report.  
✅ Delivered through GitHub with full reproducibility and visuals.

