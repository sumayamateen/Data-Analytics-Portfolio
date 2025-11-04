# Statistics of Digital Campaigns Performance

![Excel](https://img.shields.io/badge/Microsoft_Excel-Statistical_Analysis-217346)
![Tableau](https://img.shields.io/badge/Tableau-Data_Visualization-005570)
![Statistics](https://img.shields.io/badge/Statistics-Hypothesis_Testing-orange)
![Regression](https://img.shields.io/badge/Model-Linear_Regression-green)
![Analysis](https://img.shields.io/badge/Business-Performance_Insights-blueviolet)

---

## Overview  
This project compares **Facebook** and **AdWords** digital campaigns using **Excel-based statistical techniques** and **Tableau visualization**.  
The goal is to identify which platform delivers **higher conversions**, test the **statistical significance** of performance differences, and model **conversion predictability** using **simple linear regression**.

**Tools Used:**  
- **Microsoft Excel** – Data cleaning, descriptive statistics, hypothesis testing  
- **Tableau** – Regression analysis and data visualization  

**Dataset:** Digital campaign data with impressions, clicks, conversions, and cost metrics for Facebook and AdWords.  
**File:** `2_Statistics_of_Digital_Campaigns_Performance.pdf`

---

## Business Objective  
The marketing team aims to optimize ad budget allocation across platforms by determining:
1. Which platform generates **more conversions per click**  
2. Whether this difference is **statistically significant**  
3. Which platform has **stronger correlation** between clicks and conversions  

---

## Statistical Analysis  

### 1. Descriptive Statistics  
| Metric | Facebook | AdWords | Insight |
|--------|-----------|---------|----------|
| **Mean Clicks** | 44.05 | 60.38 | AdWords gets more clicks |
| **Mean Conversions** | 11.74 | 5.98 | Facebook nearly doubles conversions |
| **Std. Deviation (Conversions)** | 2.92 | 1.63 | Facebook shows higher variability (growth potential) |

---

### 2. Correlation Analysis (Excel Scatter Plot)  
- **Facebook:** r = **0.87** → Strong positive correlation between clicks and conversions  
- **AdWords:** r = **0.45** → Moderate correlation  

**Interpretation:** Facebook conversions are more strongly and predictably linked to clicks.

---

### 3. Hypothesis Testing (Two-Sample t-Test)  
**H₀ (Null Hypothesis):** No significant difference in mean conversions between platforms.  
**H₁ (Alternative):** There is a significant difference in mean conversions.  

- **p-value:** < 0.05 → Reject H₀  
**Result:** Facebook’s conversion performance is **significantly higher**.

---

### 4. Simple Linear Regression (Tableau)  
**Model:**  
\[
Conversions = 0.204 \times Clicks + 2.77
\]

- Built in **Tableau** using trend line and regression summary.  
- Suggests every **+1 click** leads to **~0.2 conversions** on average.  
- Regression line shows **strong model fit (consistent with r = 0.87).**

---

##  Key Findings  

| Finding | Observation |
|----------|--------------|
| Facebook produces **more conversions per click** | ✅ |
| AdWords drives **traffic but low conversion efficiency** | ✅ |
| Facebook’s click-to-conversion relationship is **predictable** | ✅ |
| Statistical testing confirms **significant performance gap** | ✅ |
| Regression supports Facebook as the **optimal platform** | ✅ |

---

## Strategic Recommendations  
1. **Reallocate Budget:** Shift ad spend toward **Facebook** for higher ROI.  
2. **Optimize AdWords Funnel:** Improve ad targeting and landing pages to lift conversions.  
3. **Scale Facebook Campaigns:** Utilize predictive regression insights for better forecasting.  
4. **Monitor AdWords Correlation:** Set KPI target of **r ≥ 0.6** for performance improvement.  
5. **Use Regression Outcomes:** Apply linear model to predict conversion growth scenarios.

---

## Business Impact  
| Impact Area | Outcome |
|--------------|----------|
| **ROI Improvement** | Facebook reallocations could yield ~96% higher conversions |
| **Operational Efficiency** | Predictive insights enable data-driven media planning |
| **Decision Support** | Clear, statistically validated evidence for budget strategy |

---

## Tools & Techniques  
- **Excel:** Descriptive Statistics, Histogram, Scatter Plot, Correlation, Two-Sample t-Test  
- **Tableau:** Simple Linear Regression, Visual Storytelling  
- **Statistical Methods:** Correlation (r), p-value testing, regression coefficient estimation  

---



