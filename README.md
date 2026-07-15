# 📱 Meta Ad Performance Analysis - Power BI

## 📌 Project Overview

The **Meta Ad Performance Analysis Dashboard** is a Business Intelligence project developed to analyse paid advertising campaign performance across **Facebook and Instagram** platforms.

The dashboard provides insights into campaign reach, user engagement, conversions, and budget utilization. It helps marketing teams understand campaign effectiveness, optimize advertising spend, and make data-driven decisions.

---

# 🎯 Business Objective

The objective of this project is to develop an interactive performance tracking report for Meta advertising campaigns.

The dashboard enables the marketing team to:

- Identify the most effective advertising platform.
- Compare Facebook vs Instagram campaign performance.
- Monitor campaign ROI and conversion efficiency.
- Understand audience engagement behaviour.
- Optimize budget allocation.

---

# 📌 Project Scope

## ✅ In Scope

The analysis includes:

- Facebook paid advertisements.
- Instagram paid advertisements.
- Campaign performance tracking.
- Audience engagement analysis.
- Conversion analysis.
- Budget analysis.

---

## ❌ Out of Scope

The following are excluded:

- Messenger advertisements.
- Audience Network advertisements.
- Organic engagement data.

---

# 📊 Key Performance Indicators (KPIs)

## 👁️ Impressions

### Definition

The number of times advertisements were displayed to users.

### Calculation

```
COUNT(event_type = "Impression")
```

### Purpose

Measures advertisement reach.

---

# 🖱️ Clicks

### Definition

The number of times users clicked advertisements.

### Calculation

```
COUNT(event_type = "Click")
```

### Purpose

Measures user engagement intent.

---

# 🔄 Shares

### Definition

The number of times advertisements were shared.

### Calculation

```
COUNT(event_type = "Share")
```

### Purpose

Measures viral engagement.

---

# 💬 Comments

### Definition

The number of user comments received on advertisements.

### Calculation

```
COUNT(event_type = "Comment")
```

### Purpose

Analyses user feedback and sentiment.

---

# 🛒 Purchases

### Definition

The number of purchases generated after viewing advertisements.

### Calculation

```
COUNT(event_type = "Purchase")
```

### Purpose

Measures campaign conversions.

---

# 📈 Engagements

### Definition

Total user interactions with advertisements.

### Formula

```
Clicks + Shares + Comments
```

### Purpose

Measures overall engagement volume.

---

# 📊 CTR (Click Through Rate)

### Definition

Percentage of impressions resulting in clicks.

### Formula

```
(Clicks / Impressions) × 100
```

### Purpose

Measures advertisement effectiveness.

---

# 📊 Engagement Rate

### Definition

Percentage of impressions generating interactions.

### Formula

```
(Engagements / Impressions) × 100
```

### Purpose

Measures advertisement appeal.

---

# 🛍️ Conversion Rate

### Definition

Percentage of clicks resulting in purchases.

### Formula

```
(Purchases / Clicks) × 100
```

### Purpose

Measures funnel efficiency.

---

# 💰 Purchase Rate

### Definition

Percentage of impressions converted into purchases.

### Formula

```
(Purchases / Impressions) × 100
```

### Purpose

Measures conversion from advertisement reach.

---

# 💵 Budget Analysis KPIs

## Total Budget

Total advertising budget allocated across campaigns.

Formula:

```
SUM(campaigns.total_budget)
```

---

## Average Budget per Campaign

Average budget allocated per campaign.

Formula:

```
Total Budget / Number of Campaigns
```

---

# 📊 Dashboard Visualizations

## 1. Target Gender Analysis

### Visualization

**Donut Chart**

### Description

Displays advertising performance distribution by target gender.

The selected metric changes dynamically.

Metrics:

- Impressions
- Clicks
- Engagements
- Purchases

### Purpose

Identify which gender segment contributes most to campaign performance.

---

# 2. Target Age Group Analysis

### Visualization

**Bar Chart**

### Description

Displays campaign performance across different age groups.

### Purpose

Identify the most responsive audience segments.

---

# 3. Country Performance Analysis

### Visualization

**Map Chart**

### Description

Shows advertising performance geographically by country.

Bubble size or intensity represents the selected metric.

### Purpose

Understand:

- Campaign reach.
- Regional engagement.
- High-performing markets.

---

# 4. Monthly Performance Trend

### Visualization

**Calendar Heat Map**

### Description

Displays campaign activity by month using ad event timestamps.

Darker shades indicate higher activity.

### Purpose

Identify:

- Seasonal trends.
- Peak advertising periods.
- Low-performance periods.

---

# 5. Weekly Performance Trend by Ad Type

### Visualization

**Stacked Column Chart**

### Description

Displays weekly campaign performance separated by advertisement type.

### Structure:

X-axis:

```
Week Number
```

Stacks:

```
Ad Type
```

Y-axis:

```
Selected Metric
```

### Purpose

Compare advertisement format performance over time.

---

# 6. Hourly User Activity Trend

### Visualization

**Area Chart**

### Description

Shows campaign activity by hour of the day.

### Structure:

X-axis:

```
Hour (0-23)
```

Y-axis:

```
Selected Metric
```

### Purpose

Identify the best-performing times for advertising.

---

# 7. Ad Type Performance Matrix

### Visualization

**Matrix**

### Description

Compares selected metrics across different advertisement types and platforms.

Rows:

```
Ad Types
```

Columns:

```
Platforms (Facebook / Instagram)
```

Values:

```
Selected Metric
```

### Purpose

Compare ad formats and platform performance.

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Microsoft Power BI | Dashboard development |
| Power Query | Data cleaning and transformation |
| DAX | KPI calculations and dynamic measures |
| Excel / CSV | Dataset source |

---

# 📂 Repository Structure

```
Meta-Ad-Performance-Analysis/
│
├── Dataset/
│   ├── ads.csv
│   ├── ad_events.csv
│   ├── users.csv
│
├── Dashboard/
│   └── Meta_Ad_Performance_Dashboard.pbix
│
├── Screenshots/
│   └── dashboard_preview.png
│
├── Documentation/
│   └── Business_Requirements_Document.md
│
└── README.md
```

---

# 🔄 Data Processing Workflow

## Step 1: Data Preparation

Performed:

- Data cleaning.
- Missing value handling.
- Data type correction.
- Date/time transformation.
- Category standardization.

---

## Step 2: Data Modelling

Created relationships between:

- Campaign table.
- Ads table.
- Ad Events table.
- Users table.
- Date table.

---

## Step 3: DAX Development

Created dynamic measures for:

- Impressions.
- Clicks.
- Shares.
- Comments.
- Purchases.
- CTR.
- Engagement Rate.
- Conversion Rate.
- Purchase Rate.

---

# 📈 Business Insights Generated

The dashboard provides insights into:

✅ Best-performing advertising platforms  
✅ Highest converting campaigns  
✅ Most responsive audience groups  
✅ Geographic campaign performance  
✅ Peak advertising periods  
✅ Best-performing ad formats  
✅ Budget utilization efficiency  

---

# 🚀 Future Improvements

Possible enhancements:

- Add machine learning-based conversion prediction.
- Implement automated campaign recommendations.
- Integrate Meta Marketing API for real-time data.
- Add customer segmentation models.
- Build ROI forecasting models.

---

# 👨‍💻 Author

**Thurunu Gunarathna**

Computer Science Graduate

Skills:

- Power BI
- Data Analytics
- SQL
- Python
- Machine Learning

---

# 📄 License

This project is developed for educational and portfolio purposes.
