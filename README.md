[🇬🇧 English version](README.md) | [🇷🇺 Русская версия](README.ru.md) 

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

## Proposed Solution

### 4-Pillar Recovery Strategy

**1. Analysis & Optimization**
- Deep-dive into customer data and competitor benchmarking
- Segment-specific analysis (age, family status, education)
- Identify high-value customer personas

**2. Customer Win-Back**
- Launch retention campaigns with family-oriented promotions
- Collect structured feedback from churned users
- Implement loyalty programs for returning customers

**3. Service Improvement**
- Redesign menu with family-friendly options (meal kits, kids' meals, family bundles)
- Optimize delivery logistics for larger orders
- Improve UX for family segment

**4. Targeted Promotion**
- Reallocate ad budget to family-focused channels
- Create compelling content for parents and families
- Test messaging across demographic segments

### Budget Allocation

**Total budget**: ~4M RUB

- **Social media advertising**: 900K RUB
- **Contextual advertising (Yandex, Google)**: 700K RUB  
- **Outdoor/city advertising**: 2.3M RUB
- **Targeting specialist services**: 85K RUB

---

## My Contribution

- **Exploratory data analysis**: cleaned dataset (removed 8-11% outliers), analyzed user complaints timeline
- **Customer segmentation**: grouped users by age, education, family status, and children presence
- **Churn analysis**: identified churn peak (weeks 26-27), visualized customer inflow/outflow patterns
- **Marketing campaign effectiveness**: evaluated 5 campaigns across demographic segments, discovered family segment gap
- **Strategic recommendations**: co-developed 4-pillar recovery strategy with budget allocation and risk assessment

---

## Tools & Methods

### Analytics
- **Data cleaning**: outlier detection, negative value removal
- **Visualization**: time-series analysis, cohort analysis, segmentation charts
- **Correlation analysis**: feature correlation matrix

### Business Strategy
- **Segmentation**: demographic, behavioral, and psychographic
- **Hypothesis testing**: marketing effectiveness by segment
- **Risk management**: identified 3 major risks (creative quality, channel selection, budget constraints)

### Tools
- **Python**: pandas, matplotlib, seaborn (for data analysis and visualization)
- **Presentation**: MS PowerPoint

---

## Key Insights

1. **Marketing-product mismatch**: Single-focused campaigns for a family-oriented product
2. **Educated customers churn fastest**: Higher education segment expects better service quality
3. **Campaign #2 was critically flawed**: Lowest engagement across all segments
4. **Family segment = highest LTV potential**: But completely ignored in current strategy

---

## Risks Identified

- **Low creative quality**: Boring ads repel potential customers
- **Wrong channel selection**: Wasted budget on platforms where target audience isn't present
- **Insufficient budget**: Limited reach and frequency for brand awareness

---

## Documentation

- [Team presentation](/dataton_presentation.pdf) — full analysis deck with visualizations

---

## About the Competition

**Dataton 2.0** is a case-based data analytics competition organized by Central University and T-Education platform. Teams received real business datasets (3,000 customer records) and had one day to:
- Conduct exploratory data analysis
- Identify business problems through data
- Develop data-driven solutions
- Present findings in technical presentation + video pitch

---

## Team

**aCUtone!** — Central University student team specializing in data analytics and business strategy
