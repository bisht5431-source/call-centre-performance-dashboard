<div align="center">

# 📞 Call Centre Performance Dashboard
### An Interactive Power BI Dashboard for Call Centre Operations & Customer Experience Analysis

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

*Transforming raw call logs into operational and customer experience insights.*

</div>

---

## 📌 Overview

The **Call Centre Performance Dashboard** is a two-page Power BI report analyzing over **32,900 customer interactions** across multiple channels — Call-Center, Web, Email, and Chatbot. It gives operations managers a clear view of call volume trends, response efficiency, customer sentiment, and regional performance, alongside a fully filterable interaction-level detail table for deep-dive analysis.

The report is built with a **two-page navigation model** — an **Overview** page for executive-level KPIs and trends, and a **Home/Detail** page for record-level exploration — connected through in-report navigation buttons and synced slicers.

---

## 🖼️ Dashboard Preview

### Overview Page
<img width="1378" height="732" alt="Screenshot 2026-07-06 122458" src="https://github.com/user-attachments/assets/713b142f-650a-4c56-86d8-9eaae71defb9" />


### Detail / Records Page
<img width="1375" height="732" alt="Screenshot 2026-07-06 122527" src="https://github.com/user-attachments/assets/8f12ab8b-e513-4035-a5ca-ef10124f7783" />

> 📁 *Add both screenshots to an `assets/` folder in your repo and update the paths above so they render correctly on GitHub.*

---

## 🎯 Key KPIs

| Metric | Value |
|---|---|
| Total Calls | 32.94K |
| Total Call Duration (hrs) | 13.74K |
| Total Call Duration (min) | 824.22K |
| Average Call Duration (min) | 25.02 |
| Response Time % | 75.26% |

---

## 🔍 Dashboard Features

**Overview Page**
- **Total Calls by Day** — Weekly call volume trend showing peak load on Thursdays and Fridays
- **Top 5 States by Total Calls** — Funnel chart ranking California, Texas, Florida, New York, and Virginia
- **Total Calls by Reason** — Treemap breakdown led by Billing Questions (23.46K), followed by Payments and Service Outages
- **Total Calls by Channel** — Donut chart comparing Call-Center, Chatbot, Email, and Web engagement share
- **Total Calls by Sentiment** — Bar chart spanning Very Positive to Negative sentiment buckets
- **Total Calls by Call-Centre City** — Ranks top-performing centres (Los Angeles, Baltimore, Chicago, Denver) by volume

**Detail Page**
- **Interaction-level data table** with Customer Name, Channel, State, Call Duration (hrs/min), Average Duration, CSAT Score, and Duration in Minutes
- **Cross-page slicers** — Customer Name, State, Call-Centre City, and Channel filters stay synced across both pages
- **Home/Overview toggle buttons** for smooth in-report navigation

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** — Report building, data modeling, DAX measures
- **DAX (Data Analysis Expressions)** — KPI calculations (Response Time %, Average Call Duration, etc.)
- **Power Query** — Data cleaning, shaping, and transformation
- **Excel / CSV** — Source data preparation

---

## 💡 Key Insights

- **Call-Center (32.3%) and Chatbot (25.06%) are the dominant channels**, together handling over half of all interactions
- **Billing Questions account for the vast majority of call reasons** (23.46K), far outweighing Payments and Service Outage issues combined
- **Negative and Neutral sentiment calls (11.1K and 8.8K) outnumber Positive sentiment calls**, signalling an opportunity to investigate root causes of customer dissatisfaction
- **Thursday and Friday see the highest call volumes** (5.5K–5.6K), suggesting staffing should scale up toward the end of the week
- **Los Angeles leads all call-centre cities** with 14K calls, nearly 30% more than the next closest centre (Baltimore)

---

## 📂 Repository Structure

```
call-centre-performance-dashboard/
│
├── assets/
│   ├── dashboard_overview.png
│   └── dashboard_detail.png
├── data/
│   └── call_centre_dataset.csv
├── CallCentre_Performance_Dashboard.pbix
└── README.md
```

---

## 🚀 How to Use

1. Clone this repository
   ```bash
   git clone https://github.com/<your-username>/call-centre-performance-dashboard.git
   ```
2. Open `CallCentre_Performance_Dashboard.pbix` in **Power BI Desktop**
3. Use the Customer Name, State, Call-Centre City, and Channel slicers to filter the report
4. Navigate between the Overview and Detail pages using the in-report **Home** / **Overview** buttons

---

## 👤 About Me

**Manish**
Data Analyst Intern @ Intellipaat Software Solutions | Advanced Data Analytics Certified (IIT Roorkee)

I'm a data analyst with ~6 years of cross-sector experience, currently building a portfolio in SQL, Power BI, and Python while pursuing entry-level data analyst roles.

- 📧 Email: bisht5431@gmail.com
- 💼 LinkedIn: www.linkedin.com/in/dataanalyst-manish
- 🐙 GitHub: https://github.com/bisht5431-source
- 📍 Location: Delhi, India

---

<div align="center">

⭐ If you found this project useful, consider giving it a star!

</div>
