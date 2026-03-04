# Dashboard: ABC Revenue & Contract Structure Analysis

## Project Overview

This project presents a management dashboard built in Tableau to analyze company revenue structure and contract segmentation using ABC-analysis.

The dashboard allows evaluation of:
- Revenue distribution by service category
- Contract contribution to total revenue
- ABC-segmentation of services and contracts
- Key performance indicators (KPI)

---

## Dashboard Components

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

## Techniques Used

- Calculated fields
- Running total
- Window functions (table calculations)
- ABC classification logic
- Dual-axis charts
- KPI cards
- Interactive dashboard layout

---

## Data

The dashboard was built using a structured dataset containing:
- Contract ID
- Service category
- Revenue amount

The focus of the project is analytical logic and visualization design.

---

## Business Value

The dashboard helps:
- Identify key revenue-generating services
- Detect high-value contracts
- Focus management attention on A-segment clients
- Support strategic decision-making

---

## Key Insights

### 1. Strong Revenue Concentration by Service Line

Software Development accounts for **62% of total revenue**, making it the dominant business driver.

Technical Support contributes approximately **36%**, while Consulting represents only **~2%**, indicating a highly specialized revenue structure.

The company is heavily dependent on a single core service line.


### 2. Clear Pareto Effect (ABC Analysis)

Segment A (top 80% cumulative revenue) consists of a limited number of contracts generating the majority of income.

The cumulative revenue curve rises steeply at the top, confirming strong revenue concentration.

A small group of contracts carries the primary financial weight of the business.


### 3. Portfolio Imbalance

Segment C includes numerous low-value contracts with minimal contribution to total revenue.

Their aggregate financial impact is small relative to potential operational costs.

This may indicate:

- inefficient portfolio structure  
- absence of minimum profitability thresholds  
- pricing misalignment  


### 4. Revenue Concentration Risk

Total revenue equals **21,804**, with a significant share concentrated in Segment A.

Loss of even one major contract could materially impact financial performance.

The current model reflects high dependency on a limited client base.


### 5. Strategic Implications

The company demonstrates:

- strong specialization  
- high revenue concentration  
- portfolio stability risk  

Potential risk mitigation strategies include:

- diversification of the client base  
- expansion of consulting services  
- cross-selling initiatives  
- strengthening Segment B contracts  

---

## Technology Stack & Demonstrated Skills

Tools
- Tableau Public
- Tableau Calculated Fields
- Table Calculations
- Aggregated metric analysis

Analytical Skills  
Tableau Technical Skills  
BI & Management Analytics Competencies  

This project demonstrates the ability to transform structured data into a management decision-support tool.

---

## How to Use

1. Download the `.twbx` file 
2. Open it in Tableau Desktop or Tableau Public
3. Use filters to explore the data interactively

---
