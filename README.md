# 📊 ApexPlanet Internship — Data Analysis Portfolio
**Devi Sri | ApexPlanet Software Pvt. Ltd. | 2024**

A complete 5-task Data Analytics Internship portfolio — covering data wrangling, EDA, deep-dive dashboarding, statistical validation, and data storytelling using a real-world Indian e-commerce dataset.

---

## 🔗 Task Repositories

| Task | Title | Repo |
|------|-------|------|
| Task 1 | Data Wrangling & Cleaning | [🔗 View](https://github.com/devisrisarika22/Task1-DataWrangling) |
| Task 2 | Exploratory Data Analysis | [🔗 View](https://github.com/devisrisarika22/Task2-EDA-BusinessIntelligence) |
| Task 3 | Deep-Dive Analysis & Power BI Dashboard | [🔗 View](https://github.com/devisrisarika22/Task3-DeepDive) |
| Task 4 | Data Storytelling & Statistical Validation | [🔗 View](https://github.com/devisrisarika22/Task4-DataStorytelling-Validation) |
| Task 5 | Master Portfolio | *(This repo)* |

---

## 🔍 Project Overview
This project analyzes an Indian e-commerce sales dataset to extract business insights across revenue, profit, customer behavior, regional performance, and order fulfillment.

---

## 📁 Dataset
- **Name:** E-Commerce Sales Dataset
- **Features:** Revenue, Profit, Category, Region, Customer Segments, Payment Methods, Order Status, Acquisition Channels

---

## 🔧 Task 1 — Data Wrangling (Python)
- Handled missing values and removed duplicates
- Standardized column names
- Feature engineering: `profit_category`, `sales_category`, `sales_per_order`
- Exported cleaned dataset for downstream analysis

---

## 📊 Task 2 — Exploratory Data Analysis (Python + Power BI)
**Visualizations:** Sales by Category · Sales by Region · Revenue vs Loss · Customer Segments · KPIs

### Task 2 Dashboard
<img width="1152" height="720" alt="Task 2 Dashboard" src="https://github.com/user-attachments/assets/b8620979-e3d0-42b6-85eb-b57ba3ae6eb0" />

---

## 🔬 Task 3 — Deep-Dive Analysis & Interactive Dashboarding (Python + Power BI)

**Core KPIs:** AOV ₹19,482 | Cancellation 10.1% | Return Rate 8.4% | Rating 3.74/5 | Avg. Delivery 5.5 days

**Analyses:** Cohort Retention · Customer Segmentation · Acquisition Channel Analysis

**Deliverable:** 3-page interactive Power BI dashboard with slicers (Year, Category, Age Group)

### Task 3 Dashboard
<img width="1124" height="635" alt="Task 3 Dashboard" src="https://github.com/user-attachments/assets/2e974579-c6d2-4c95-ae30-380576e17165" />

---

## 📖 Task 4 — Data Storytelling & Statistical Validation (Python + PowerPoint)

Structured findings into a **5-chapter business narrative** with 4 hypothesis tests:

| Hypothesis | Test | P-Value | Result |
|---|---|---|---|
| Mobile App AOV > Website AOV | T-Test | 0.0828 | Not Significant |
| 36–45 AOV > 18–25 AOV | T-Test | 0.2317 | Not Significant |
| Cancellation rate differs by channel | Chi-Squared | 0.7467 | Not Significant |
| October AOV > Other months | T-Test | **0.0075** | ✅ Significant |

**Key Finding:** October revenue spike is statistically proven (p=0.0075) — the festive season effect is real.

📎 [Final Presentation Deck](./Task4_DataStorytelling_Presentation.pptx)

---

## 🚀 Key Insights
- Electronics generates the highest revenue
- Mobile App is the top customer acquisition channel
- 36–45 age group has the highest Average Order Value
- October shows a consistent, statistically significant revenue spike (festive season)
- Month-1 customer retention is only ~6% — loyalty program opportunity
- Regional and segment performance varies significantly

---

## 🗂️ Data Dictionary

| Column | Description |
|---|---|
| customer_id | Unique customer ID |
| city / state / region | Location fields |
| category / sub_category | Product classification |
| sales | Revenue |
| quantity | Units sold |
| discount | Discount applied |
| profit | Profit earned |
| profit_category | Profit or Loss |
| sales_category | High or Low sales |
| sales_per_order | Revenue per order |
| order_status | Delivered / Cancelled / Returned |
| age_group | Customer age group |
| acquisition_channel | Customer source |
| customer_rating | Satisfaction score (1–5) |
| days_to_delivery | Fulfillment time |

---

## 🛠️ Tools Used
`Python` `Pandas` `Matplotlib` `Seaborn` `SciPy` `Power BI` `SQL (SQLite)` `VS Code` `PowerPoint`

---

## 👩‍💻 Author
**Devi Sri** — Aspiring Data Analyst

