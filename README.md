# 📊 HR Analytics Team Dashboard
📊 This interactive HR Analytics Dashboard, built entirely in Microsoft Excel, is designed to comprehensively track and visualize key workforce metrics. 📈 It empowers management teams by providing deep insights into year-over-year headcount growth and evaluating employee turnover trends. 👥 Furthermore, it clearly breaks down employee demographics, departmental distribution, and organizational hierarchy, enabling smarter, data-driven decisions for retention and workplace stability. 🚀

<img width="1386" height="653" alt="hr_dashboard" src="https://github.com/user-attachments/assets/3f0ccc82-b545-4110-bad0-63b7fedf3b61" />


## 📑 Table of Contents
* [Project Overview](#project-overview)
* [Business Problem](#business-problem)
* [Key Performance Indicators (KPIs)](#key-performance-indicators-kpis)
* [Dashboard Visualizations & Insights](#dashboard-visualizations--insights)
* [Technical Methodology](#technical-methodology)
* [Business Recommendations](#business-recommendations)
* [How to Use This File](#how-to-use-this-file)

---

## 🎯 Project Overview
This project features an interactive **HR Analytics Dashboard** built entirely in Microsoft Excel. The goal of this dashboard is to transform raw human resources data into actionable visual insights, enabling HR leadership to monitor workforce demographics, track employee turnover, and assess organizational stability. 

## ❓ Business Problem
Managing a growing workforce requires a deep understanding of employee dynamics. The HR and executive teams needed a centralized, easy-to-read dashboard to answer critical business questions:
* What is our current retention and attrition rate?
* How diverse is our workforce?
* Is our headcount growing sustainably over the years?
* How is our staff distributed across departments and management hierarchies?

---

## 📈 Key Performance Indicators (KPIs)
The top section of the dashboard highlights the most critical metrics at a glance:
* **Total Headcount:** 171 employees
* **Active Headcount:** 118 employees
* **Total Attrition:** 47 employees
* **Attrition Rate:** 27% (A key metric for retention strategies)
* **Transfers:** 6 internal role changes

  <img width="1150" height="165" alt="hrkpi" src="https://github.com/user-attachments/assets/6c6b9b68-164d-47c6-9e58-e38dc68e9bf0" />


---

## 📊 Dashboard Visualizations & Insights
The dashboard utilizes a variety of advanced Excel charts to slice the data across multiple dimensions:

1. **Headcount Growth (Combo Chart):** Tracks the timeline from 2020 to 2025, comparing Attrition, On-boarding, Transfers, and overall Headcount Growth. 
2. **Diversity % (Donut Chart):** Highlights the gender split (62% Male, 38% Female), providing a baseline for future diversity and inclusion initiatives.
3. **Job Levels % (Pyramid Chart):** Displays the organizational hierarchy, showing a base of Trainees (38%), scaling up through Professional (34%), Management (15%), and Contract roles (13%).
4. **Department by Headcount % (Donut Chart):** Visualizes workforce distribution. Notable concentrations include Operations (27%) and Marketing (22%).
5. **Headcount Reporting (Funnel Chart):** Shows the span of control for leadership, illustrating exactly how many employees report to managers like Ryan Simmons (58) vs. Geneva Hardy (7).
6. **Employee Type % (Stacked Column):** Compares Permanent staff (87% / 148 employees) to Contract staff (13% / 23 employees).
7. **Stability % (Bar Chart):** Analyzes employee tenure. A significant portion of the workforce has 5+ years of stability (54 employees), indicating strong long-term retention for a core group.

---

## ⚙️ Technical Methodology
This dashboard was developed using the following Excel features and techniques:
* **Data Cleaning & Transformation:** Structured raw HR data for accurate reporting.
* **Pivot Tables:** Used as the calculation engine behind all charts and KPIs to ensure dynamic updating.
* **Advanced Charting:** Implemented non-standard charts (like the Pyramid and Funnel charts) to best represent hierarchical and directional data.
* **Interactive Slicers:** Connected slicers to multiple Pivot Tables, allowing users to filter the entire dashboard by **Department** and **Reporting Manager** simultaneously.

---

## 💡 Business Recommendations
Based on the data visualized in this dashboard, the following actions are recommended:
1. **Investigate the 27% Attrition Rate:** This is a notably high figure. Exit interviews should be analyzed to understand if turnover is driven by compensation, management, or career growth limitations.
2. **Diversity Initiatives:** With a 62% male / 38% female split, the recruitment team may want to focus on sourcing strategies that encourage a more balanced gender representation.
3. **Managerial Workload:** Ryan Simmons has 58 direct/indirect reports. HR should evaluate if this span of control is too wide and if restructuring is necessary to prevent manager burnout.

---

## 🚀 How to Use This File
1. Download the `HR_Analytics_Dashboard.xlsx` file from this repository.
2. Open the file in Microsoft Excel (Desktop version recommended for full slicer functionality).
3. Navigate to the **Dashboard** tab.
4. Use the **Slicers** on the left-hand menu to filter by specific Departments (e.g., Finance, Legal) or specific Reporting Managers. All charts and KPIs will update dynamically based on your selection.
