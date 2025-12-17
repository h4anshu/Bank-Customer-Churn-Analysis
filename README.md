# Bank-Customer-Churn-Analysis

## 🎯 Project Overview
This project analyzes customer churn patterns in a banking dataset to identify key drivers of customer attrition and quantify the financial impact. Using Microsoft Excel, I performed comprehensive data analysis, created interactive dashboards, and generated actionable insights for stakeholder decision-making.

## 💼 Business Problem
Customer churn is a critical metric for banks as acquiring new customers is significantly more expensive than retaining existing ones. This analysis aims to:

*1.* Identify which customer segments have the highest churn rates
*2.* Quantify the financial impact of customer attrition
*3.* Analyze the relationship between customer complaints, satisfaction, and churn
*4.* Segment customers by geography, engagement level, and product holdings
*5.* Document patterns and insights for stakeholder communication


## 📊 Dataset Information
*datasetRecords:* 10,000 
*customersAttributes:* 18 variables
*Target Variable:* Exited (1 = Churned, 0 = Retained)

### Key Variables Analyzed:

**Demographics:** Age, Gender, Geography (France, Spain, Germany)
**Financial Metrics:** Balance, Credit Score, Estimated Salary
**Behavioral Indicators:** Tenure, Number of Products, Active Member Status
**Satisfaction Data:** Complaint Status, Satisfaction Score (1-5)
**Product Information:** Card Type (Diamond, Gold, Silver, Platinum), Points Earned

## Data Characteristics:

*⚠️ Note: This dataset exhibits characteristics of a synthetic/educational dataset with complaint status showing extremely strong correlation with churn (99.51% vs 0.05%). While this simplified pattern differs from typical real-world banking data with diverse churn drivers, it enabled focused analysis of service quality dynamics and demonstrates analytical methodology applicable to production environments.*


## 🔍 Methodology
**1. Data Preparation**

Validated data quality (no duplicates, consistent formats)
Created calculated fields for analysis:
**a.Age Group:** Young (<30), Middle (30-49), Senior (50+)
**b.Balance Category:** Zero, Low (<$50K), Medium ($50-100K), High (>$100K)
**c.Churn Status:** Text conversion of binary field for readability

**2. Analytical Framework**
### Descriptive Statistics

*Calculated overall churn rate:* 20.38%
*Total churned customers:* 2,038 out of 10,000
*Revenue at risk:* $186.3 million
*Average balance per churned customer:* $91,478

### Segmentation Analysis

*Geographic:* Compared France, Spain, and Germany markets
*Demographic:* Analyzed age groups and gender patterns
*Behavioral:* Examined activity status, product holdings, complaint history
*Value-based:* Assessed balance categories and card types

### Multi-dimensional Analysis

*1.*Created 6+ pivot tables for cross-dimensional insights
*2.*Performed comparative analysis (churned vs retained) across all segments
*3.*Identified interaction effects between variables

### 3. Data Visualization

*1.*Built interactive dashboard with 15+ KPIs
*2.*Created 6 different chart types to communicate findings
*3.*Designed executive summary for stakeholder presentation


## 🔑 Key Findings
### 1. 📢 Complaint-Churn Correlation
**Finding:** Customers who complained showed 99.51% churn rate vs 0.05% for non-complainers

**Impact:** 99.8% of all churned customers (2,034 of 2,038) had filed complaints
**Revenue Impact:** $186.3M in lost balances directly attributable to complaint-related churn
**Insight:** Complaint status is the strongest predictor of churn in this dataset

### 2. 🌍 Geographic Disparity
**Finding:** Germany market shows 32.4% churn rate vs France (16.2%) and Spain (16.7%)

*Impact:* Germany's churn rate is nearly 2x the baseline
*Customer Loss:* 814 customers churned in Germany (out of 2,509 total)
*Revenue Exposure:* $94.8M at risk in German market
*Insight:* Geographic-specific factors require market investigation

### 3. 📱 Engagement Impact
Finding: Inactive members demonstrate 26.9% churn rate vs 10.4% for active members

*Multiplier Effect:* 2.6x higher churn risk for inactive customers
*Volume Impact:* Inactive segment represents 68% of all churned customers
*Revenue at Risk:* $127.8M from inactive member churn
*Insight:* Customer engagement is the second-strongest retention predictor

### 4. 🏦 Product Holdings Effect
Finding: Single-product customers show 27.7% churn vs 7.6% for two-product holders

*Difference:* 20.1 percentage point gap (73% relative reduction)
*High-Risk Segment:* 5,084 single-product customers
*Opportunity:* Cross-selling from 1 to 2 products significantly improves retention
*Insight:* Product diversification creates switching costs and deeper relationships

### 5. 👥 Age & Tenure Patterns
*Finding:* Churned customers are older (44.8 years avg) vs retained (36.9 years avg)

*Age Gap:* 7.9 years difference
*Tenure Pattern:* Shorter tenure among churned (4.9 vs 5.0 years)
*Risk Profile:* Middle-aged customers with <5 years tenure show highest vulnerability
*Insight:* Early relationship building (first 3 years) is critical for retention

# 💡 Key Learnings
## Technical Skills Developed

✅ Advanced Excel formula writing (nested functions, multi-criteria logic)
✅ Pivot table mastery (calculated fields, custom grouping, % calculations)
✅ Data visualization best practices (color theory, chart selection, storytelling)
✅ Dashboard design principles (KPI hierarchy, visual layout, interactivity)

## Analytical Skills Enhanced

✅ Multi-dimensional segmentation techniques
✅ Comparative analysis methodology (churned vs retained)
✅ Pattern recognition in large datasets
✅ Financial impact quantification
✅ Risk scoring model development

## Business Acumen Gained

✅ Understanding of customer retention metrics
✅ Service quality impact on business outcomes
✅ Geographic market analysis frameworks
✅ Customer lifecycle value concepts
✅ Stakeholder communication strategies

## Project Management

✅ Structured analytical approach (preparation → analysis → visualization → documentation)
✅ Documentation best practices for reproducibility
✅ Executive summary creation for non-technical audiences
✅ Data quality validation and limitation acknowledgment

