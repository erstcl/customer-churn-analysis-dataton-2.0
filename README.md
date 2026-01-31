[🇷🇺 Русская версия](README.ru.md) | [🇬🇧 English version](README.md)

---

# JFood Customer Churn Analysis: Marketing Strategy Optimization

**Hackathon**: Dataton 2.0 (Central University)  
**Team**: aCUtone!  
**Timeline**: July 2024  
**Result**: Data-driven marketing strategy to reduce churn and attract family segment

---

## Challenge

JFood, a food delivery startup by entrepreneur Jacob, experienced a sharp decline in sales after just 2 months of operations. Despite running 5 marketing campaigns, customer retention dropped significantly in late June - early July 2024. The task was to:

- Identify the root cause of customer churn
- Analyze 3 months of data (3,000 customers)
- Develop an actionable strategy within $600K budget
- Prepare recommendations for investor pitch

---

## Solution Overview

Our team conducted comprehensive data analysis and discovered that **the marketing strategy failed to target the right audience** — specifically, educated adults aged 18-50 with families and children.

### Key Findings

**Customer churn pattern**:
- Peak churn occurred in weeks 26-27 (late June / early July 2024)
- Primary churn segment: adults 18-50 years old with higher education
- Both customers with and without children left the platform

**Marketing campaign effectiveness**:
- Campaigns resonated with single/widowed users
- **Campaigns completely missed married customers with families**
- People without children responded 3-4x better to ads than those with children
- Campaign #2 had the lowest success rate

**Data quality issues identified**:
- 8% outliers removed from order data (negative average checks)
- 11% outliers in online catalog interactions
- 3% outliers in mobile app data

### Root Cause

The marketing campaigns were designed for single individuals and failed to address the needs of family customers — the core demographic for a food delivery service. This misalignment caused educated, financially stable customers (prime target audience) to abandon the platform.

---

## Analysis Pipeline

### 1. Data Cleaning & Preprocessing
- Removed negative values and outliers (8-11% of data)
- Merged three datasets: user data, order data, interaction data
- Created age-based cohorts and segmentation

### 2. Exploratory Data Analysis
- **User complaints timeline**: identified complaint spike in June-July
- **Churn analysis**: tracked last order dates to identify churned users
- **Demographic segmentation**: analyzed by age, education, family status, children
- **Marketing effectiveness**: evaluated 5 campaigns across segments

### 3. Insights & Visualization
- Purchasing patterns by age and income
- Marketing campaign success rates by demographic
- Churn distribution across customer segments

---

## Key Results

**Overall Accuracy** | 83% marketing mismatch identified  
**Posts analyzed** | 3,000+ customer records  
**Outliers cleaned** | 8-11% of raw data  
**Churn peak** | Weeks 26-27 (late June 2024)  

### Business Impact

**Primary insight**: Marketing campaigns targeted singles while product serves families → 60%+ churn in target demographic

**Recommended budget reallocation**:
- Social media: 900K RUB (family-oriented content)
- Contextual ads: 700K RUB (parent-focused keywords)
- Outdoor advertising: 2.3M RUB (family lifestyle imagery)
- Targeting specialist: 85K RUB

---

## My Contribution

- **Exploratory data analysis**: cleaned dataset (removed 8-11% outliers), analyzed user complaints timeline
- **Customer segmentation**: grouped users by age, education, family status, and children presence
- **Churn analysis**: identified churn peak (weeks 26-27), visualized customer inflow/outflow patterns
- **Marketing campaign effectiveness**: evaluated 5 campaigns across demographic segments, discovered family segment gap
- **Strategic recommendations**: co-developed 4-pillar recovery strategy with budget allocation and risk assessment
- **Visualization**: created age-income distributions, campaign effectiveness charts, churn timelines

---

## Technical Stack

### Tools & Libraries
- **Python**: pandas, numpy, matplotlib, seaborn
- **Analysis**: Jupyter Notebook
- **Visualization**: matplotlib (scatter plots, histograms, time series)
- **Presentation**: MS PowerPoint

### Methods
- **Data cleaning**: outlier detection, negative value removal
- **Segmentation**: demographic, behavioral analysis
- **Cohort analysis**: time-based churn patterns
- **Statistical analysis**: correlation matrices, distribution analysis

---

## Dataset Description

### Raw Data (3 files, ~3,000 customers)

**[userdata.csv](/userdata.csv)**
- User demographics (age, gender, education, family status)
- Registration dates
- Children count

**[orderdata.csv](/orderdata.csv)**
- Order history (timestamps, amounts, categories)
- Average check values
- Purchase frequency

**[interactiondata.csv](/interactiondata.csv)**
- Marketing campaign interactions
- Website/app engagement
- Campaign outcomes (success/failure)

### Processed Data

**[cleaned_userdata.csv](/cleaned_userdata.csv)** — User data after outlier removal and validation

**[cleaned_orderdata.csv](/cleaned_orderdata.csv)** — Order data after cleaning negative values

**[cleaned_interactiondata.csv](/cleaned_interactiondata.csv)** — Interaction data after validation

**[age_interactiondata.csv](/age_interactiondata.csv)** — Segmented analysis combining user demographics with interaction patterns

---

## Documentation

- [Full analysis notebook](/dataton.ipynb) — complete EDA, segmentation, and insights
- [Final presentation](/dataton_presentation.pdf) — strategy and recommendations

---

## Frameworks & Methods

### Strategy
- 3C Analysis (Company, Customers, Competition)
- SWOT
- Customer segmentation

### Analytics
- Cohort analysis (time-based churn)
- Demographic segmentation
- Marketing attribution analysis
- Outlier detection and data cleaning

### Visualization
- Scatter plots (age vs income, payment ability)
- Histograms (order distributions by demographics)
- Time series (churn patterns, complaint trends)

---

## About the Competition

**Dataton 2.0** is a case-based data analytics competition organized by Central University and T-Education platform. Teams received real business datasets (3,000 customer records) and had one day to:
- Conduct exploratory data analysis
- Identify business problems through data
- Develop data-driven solutions
- Present findings in technical presentation + video pitch
