# Dashboard: ABC Revenue & Contract Structure Analysis

## 📌 Project Overview

This project presents a management dashboard built in Tableau to analyze company revenue structure and contract segmentation using ABC-analysis.

The dashboard allows evaluation of:
- Revenue distribution by service category
- Contract contribution to total revenue
- ABC-segmentation of services and contracts
- Key performance indicators (KPI)

---

## 📊 Dashboard Components

### 1. KPI Block
- Total revenue
- Number of contracts
- Average check

### 2. Revenue Structure by Services
Bar chart showing revenue share by service category.

### 3. ABC-Analysis of Services
Cumulative revenue curve with 80% threshold.

### 4. ABC-Analysis of Contracts
Contract ranking by revenue contribution:
- A segment (top 80%)
- B segment (80–95%)
- C segment (below 95%)

---

## ⚙️ Techniques Used

- Calculated fields
- Running total
- Window functions (table calculations)
- ABC classification logic
- Dual-axis charts
- KPI cards
- Interactive dashboard layout

---

## 📁 Data

The dashboard was built using a structured dataset containing:
- Contract ID
- Service category
- Revenue amount

The focus of the project is analytical logic and visualization design.

---

## 🎯 Business Value

The dashboard helps:
- Identify key revenue-generating services
- Detect high-value contracts
- Focus management attention on A-segment clients
- Support strategic decision-making

---

## Key Insights

- Service "Software Development" generates the majority of revenue (~62%), representing the core business driver.
- A small number of contracts (Segment A) contributes to a disproportionate share of total revenue, confirming Pareto distribution.
- Segment C contains many low-value contracts with minimal revenue contribution, indicating potential inefficiencies.
- Revenue concentration suggests high dependency on a limited number of contracts, which may increase business risk.


---


## 🚀 How to Use

1. Download the `.twbx` file from the `dashboards` folder
2. Open it in Tableau Desktop or Tableau Public
3. Use filters to explore the data interactively

---
