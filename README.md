# Data-Driven Marketing Campaign Optimization & ROI Analysis

A data-driven analysis of Facebook ad campaigns aimed at optimizing marketing ROI through KPI benchmarking, performance scoring, and interactive dashboards using **Python** and **Power BI**.

---

## 📌 Project Overview
This project evaluates the performance of multiple Facebook advertising campaigns run under the **GlobalShala – Superhero U initiative**.  
The objective is to **identify underperforming campaigns**, recommend **discontinuation or optimization actions**, and suggest **budget reallocation** to maximize return on investment (ROI).

The analysis combines **Python-based data processing** with **Power BI visual analytics** to support evidence-based marketing decisions.

---

## 🎯 Business Problem
Marketing teams often invest heavily across campaigns without clear visibility into:
- Which campaigns generate **high cost but low engagement**
- Which campaigns deliver **strong ROI**
- Where budget should be **cut, optimized, or scaled**

This project answers:
- ❓ Which campaigns are underperforming?
- ❓ Why are they underperforming?
- ❓ Where should the budget be reallocated?

---

## 🧾 Dataset Description
**Source:** Internal Facebook Ads campaign data provided by the GlobalShala Marketing Team  

**Granularity:** Campaign-level performance segmented by:
- Audience type
- Geography
- Age group

### Key Metrics
- Click-Through Rate (CTR)
- Engagement Rate
- Cost Per Click (CPC)
- Cost Per Result (CPR)
- Amount Spent
- Unique Link Clicks (ULC)

An additional **Performance Score** was engineered to enable objective comparison across campaigns.

---

## 🛠 Tools & Technologies
- **Python**: Pandas, Matplotlib  
- **Power BI**: Interactive dashboards and KPI analysis  
- **Jupyter Notebook**: End-to-end analysis workflow  
- **CSV / Excel**: Data storage and preprocessing  

---

## 🔍 Methodology
1. **Data Cleaning & Validation**
   - Ensured correct data types for all KPIs
   - Handled inconsistencies in categorical fields
   - Validated campaign-level aggregates

2. **Feature Engineering**
   - Built a composite **Performance Score** using:
     - CTR
     - Engagement Rate
     - CPC
   - Enabled fair comparison across campaigns with different spend levels

3. **KPI Benchmarking**
   - Used percentile-based thresholds:
     - High CPC (75th percentile)
     - Low engagement (25th percentile)
     - Median CTR
   - Objectively flagged inefficient campaigns

4. **Visualization & Decision Support**
   - Built Power BI dashboards to:
     - Compare campaign performance
     - Identify inefficiencies
     - Support data-backed decisions

---

## 📊 Power BI Dashboard (3 Pages)

### 1️⃣ Executive KPI Overview
High-level snapshot of campaign performance including CPC, CTR, engagement, spend, and ULC.

![Executive KPI Overview](visuals/dashboard_kpi_overview.png)

---

### 2️⃣ Campaign Performance Comparison
Side-by-side comparison of campaigns highlighting cost inefficiencies and engagement gaps.

![Campaign Performance Comparison](visuals/dashboard_campaign_comparison.png)

---

### 3️⃣ Root Cause & Efficiency Analysis
Deep-dive analysis linking cost, engagement, and conversion efficiency to explain *why* campaigns underperform.

![Root Cause Analysis](visuals/dashboard_root_cause_analysis.png)

---

## ✅ Key Findings
### ❌ Campaigns Recommended for Discontinuation
- **Campaign 3 – Australia (Students)**
- **Campaign 10 – UK (Students)**

These campaigns showed:
- High CPC
- Low engagement and CTR
- Poor overall performance scores

### ✅ High-Performing Campaigns
- Campaigns in regions like **Nigeria** demonstrated strong engagement and cost efficiency
- Recommended for **budget scaling**

---

## 📈 Recommendations
- Discontinue campaigns with sustained low ROI
- Reallocate budget toward high-performing regions
- Apply A/B testing and targeting refinements for mid-performing campaigns
- Use performance scoring as a repeatable evaluation framework
