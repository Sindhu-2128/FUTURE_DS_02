# Social Media Ad Campaign Performance Analysis 📊
## 📌 Project Overview
This project analyzes Facebook, Instagram, Google, LinkedIn, and YouTube ad campaign data to evaluate overall campaign performance, engagement, CTR, ROI, and conversion efficiency. An interactive Power BI dashboard was developed to help identify high-performing campaigns, optimize ad spend, and support data-driven marketing decisions.

---

## 🎯 Objectives
- Evaluate campaign performance using conversions, CTR, and ROI  
- Analyze ad spend vs revenue efficiency across campaigns  
- Compare platform-wise performance  
- Understand audience behavior by age and gender  
- Provide actionable insights for campaign optimization  

---

## 🛠 Tools & Technologies
- **Power BI** – Dashboard development & DAX
- **Power Query** – Data cleaning and transformation
- **Excel / CSV** – Data source
- **GitHub** – Project documentation

---

## 📂 Dataset Details
The dataset includes the following key attributes:
- Campaign_ID
- Budget, Spend, Revenue
- Impressions, Clicks, CTR
- Conversions, Conversion Rate
- CPC, CPA, ROAS
- Platform, Content Type
- Target Age, Target Gender
- Region
- Date, Duration

---
## Key Insights
Certain campaigns deliver high conversions with relatively lower spend, indicating better efficiency
Higher ad spend does not always guarantee higher ROI
Platform performance varies significantly, highlighting the importance of channel optimization
Specific age groups and genders show higher conversion potential

## Demo 


## Conclusion
This project demonstrates practical marketing analytics skills using Power BI, including KPI creation, DAX calculations, campaign performance evaluation, and interactive dashboard storytelling.
The insights generated can help marketers optimize budget allocation and improve campaign outcomes.

## 📐 Key DAX Measures
```DAX
Total Spend = SUM(Campaigns[Spend])
Total Revenue = SUM(Campaigns[Revenue])
Total Impressions = SUM(Campaigns[Impressions])
Total Clicks = SUM(Campaigns[Clicks])
Total Conversions = SUM(Campaigns[Conversions])

CTR (%) = DIVIDE([Total Clicks], [Total Impressions]) * 100
ROI (%) = DIVIDE([Total Revenue] - [Total Spend], [Total Spend]) * 100


