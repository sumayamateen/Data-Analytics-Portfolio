# Learner Engagement & Campaign Analytics Dashboard 

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-Query_Optimization-4479A1)
![ETL](https://img.shields.io/badge/ETL-Pipeline-FF6B35)
![Looker Studio](https://img.shields.io/badge/Looker_Studio-Interactive_Dashboard-4285F4)
![Data Visualization](https://img.shields.io/badge/Data_Visualization-Insights-00C7B7)

---

## Project Overview
This project transforms **disparate educational datasets** into a **centralized analytics ecosystem** using comprehensive ETL processes and an interactive dashboard.  
It enables stakeholders to **monitor learner engagement, track campaign performance**, and make **data-driven decisions** to optimize educational impact.

- **Scope:** 5 integrated datasets, 52.1K learners across 146 countries  
- **Platform:** Interactive dashboard with real-time analytics capabilities  

**Tech Stack:** PostgreSQL, SQL, Looker Studio, Excel  

---

## Business Challenge
- **Data Fragmentation:** Multiple disconnected datasets (Cognito, User Data, Learner Opportunity, Cohort Data, Opportunity Data)  
- **Limited Visibility:** Difficulty tracking learner engagement trends and campaign effectiveness  
- **Manual Analysis:** Time-consuming extraction of insights from raw data  
- **Strategic Gap:** Lack of centralized platform for data-driven decision-making  

---

## Technical Implementation

### ETL Pipeline Architecture
- **Data Integration:** Consolidated five relational datasets into a unified Master Table  
- **Data Quality:** Comprehensive cleaning (trimming, standardization, null handling)  
- **Optimization:** Indexing implementation for enhanced query performance  
- **Validation:** Rigorous quality checks and sample verification processes  

### Dashboard Development
- **Interactive Features:** Date filters, category filters, drill-down capabilities  
- **Visual Storytelling:** Trend analysis, geographic distribution, performance metrics  
- **User Experience:** Responsive design with intuitive navigation  

---

## Project Files

| File | Description |
|------|-------------|
| `1.1_Master_Table_ETL.sql` | SQL scripts to build the Master Table from multiple raw datasets |
| `1.2_Marketing_Data_ETL.sql` | SQL scripts for cleaning, transforming, and analyzing the Marketing dataset separately |
| `2_Mapping_Table.xlsx` | Documented relationships and transformations across datasets |
| `3_Wireframe_Sketch.pdf` | Planned dashboard layout, design, and visualization flow |
| `Presentation.pdf` | Stakeholder-facing presentation summarizing workflow, key insights, and recommendations |

---

## Key Performance Indicators

### Learner Metrics
- **Total Learners:** 52,100  
- **Total Applications:** 99,200  
- **Average Age:** 25 years  
- **Countries Reached:** 146  
- **Institutions Represented:** 20,200  

### Campaign Performance
- **Total Amount Spent:** 338,400 DH  
- **Outbound Clicks:** 519,300  
- **Landing Page Views:** 298,100  
- **Total Results:** 182,500  

---

## Critical Insights

### Engagement Trends
- Explosive Growth: 49M (2022) → 79.2M (2023) cohort size  
- Recent Slowdown: Decline to 62.2M (2024) and 23.8M (2025)  
- Application Peaks: Highest engagement in 2024, followed by decline  

### Campaign Efficiency
- Significant Drop-offs: 38.3K clicks → 16.1K views (conversion gap)  
- High Performers: Campaigns with better engagement ratios identified  
- Cost Analysis: CPC vs. Cost Per Result optimization opportunities  

### Geographic Distribution
- Global Reach: Strong presence across 146 countries  
- Regional Focus: High engagement in developing regions  
- Expansion Potential: South America, Eastern Europe, Central Asia  

---

## Strategic Recommendations

### Immediate Actions
1. Analyze 2025 application drop-offs and align with academic calendars  
2. Optimize landing pages to reduce bounce rates from high-click, low-view campaigns  
3. Targeted regional outreach for underrepresented regions  

### Long-term Initiatives
1. Establish continuous campaign performance monitoring and optimization  
2. Ensure engagement equity across all regions  
3. Use insights to inform program restructuring and curriculum development  

---

## Business Impact
- **Operational Efficiency:** 90% reduction in manual data consolidation time  
- **Centralized Visibility:** Real-time monitoring of learner engagement and campaign KPIs  
- **Strategic Value:** Data-driven interventions for declining engagement and optimized resource allocation  
- **Expansion Strategy:** Insights guiding global outreach and content localization  

---

## Live Dashboard
[Access Interactive Excelerate Dashboard](https://lookerstudio.google.com/reporting/2f96741e-e9c4-4b02-8b94-6f8547626f7a)

---

**Team:** Souvik Roy, Sumaya Mateen, Sonam Sahu, Subhadip Samanta, Sonta Ramesh, Soumya Ranjan Sahoo, Sudip Deuja, Sukanta Nag Hirock  
