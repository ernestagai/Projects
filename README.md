# Meta Ads Performance Analysis

A real-time Power BI analytics project that transforms Meta Ads data (Facebook & Instagram) into actionable insights to maximize Return on Ad Spend (ROAS).

Summary
- End-to-end solution: data cleaning in Excel, ETL, data modeling and advanced DAX analytics in Power BI.
- Includes clean datasets, a Power BI (.pbix) dashboard, and a PDF report with static insights.

## Table of Contents
- [Project Summary](#project-summary)
- [Objectives](#objectives)
- [Workflow](#workflow)
  - [Data Extraction](#data-extraction)
  - [Data Cleaning (Excel)](#data-cleaning-excel)
  - [Data Loading & Modeling (Power BI)](#data-loading--modeling-power-bi)
  - [Data Analysis (DAX)](#data-analysis-dax)
  - [Visualization & Insights](#visualization--insights)
- [Key Features](#key-features)
- [Performance Overview](#performance-overview)
- [Analytical Insights](#analytical-insights)
- [Strategic Recommendations](#strategic-recommendations)
- [Tools & Technologies](#tools--technologies)
- [How to Explore](#how-to-explore)
- [Contributing & Contact](#contributing--contact)
- [Changelog](#changelog)

## Project Summary
Built in Power BI, the Meta Ads Campaign Performance Dashboard visualizes advertising performance across Meta platforms and surfaces insights about audience demographics, ad formats, and timing to optimize engagement and conversions.

## Objectives
- Analyze multi-platform ad performance across Facebook & Instagram
- Understand engagement by demographics and region
- Compare performance across ad formats (Image, Carousel, Stories, Video)
- Generate insights to optimize ROI and guide strategic decisions

## Workflow

### Data Extraction
- Export raw datasets from Meta Ads Manager covering user engagement, ad events, and campaign metadata.

### Data Cleaning (Excel)
- Cleaned and standardized data in Excel:
  - Removed duplicates and inconsistencies
  - Normalized date/time formats
  - Handled missing values
  - Created calculated columns for engagement and cost metrics
- Final cleaned datasets:
  - ad_events_cleaned.csv
  - ads_campaigns_cleaned.csv
  - ads_cleaned.csv
  - users_cleaned.csv

### Data Loading & Modeling (Power BI)
- Imported cleaned files into Power BI Desktop (.pbix)
- Established relationships:
  - ads_campaigns  ad_events (Campaign_ID)
  - ads  ad_events (Ad_ID)
  - users  ad_events (User_ID)
- Built a star-schema model with measures and calculated columns for performant analysis

### Data Analysis (DAX)
- Implemented advanced DAX measures:
  - CTR (Click-Through Rate)
  - Engagement Rate
  - Conversion Rate
  - Purchase Rate
  - ROAS (Return on Ad Spend)
- Created dynamic KPI cards and calculated tables to support slicers and drill-through

### Visualization & Insights
- Interactive dashboards with slicers for platform, gender, region, and age
- Pages include KPI Summary, Audience Trends, Ad Format Comparison, and Campaign Deep Dive

<!-- Images (kept from original repo) -->

![Dashboard overview](https://github.com/user-attachments/assets/eefe8ac9-758c-43c4-bbe7-a4681d166953)

![Audience & format comparison](https://github.com/user-attachments/assets/b00c270d-a7a5-4b8e-b21d-15b92d46669a)

![Additional visual](https://github.com/user-attachments/assets/55de102d-9842-4bf8-9f82-a796eb6c52bc)

## Key Features
- Cross-Platform Integration: Unified data model for Facebook & Instagram
- Interactive Filters: Platform, gender, region, age
- Advanced DAX Analytics: Custom KPIs (CTR, Engagement, Conversion, ROAS)
- Demographic Insights: Visuals by Age, Gender, Country
- Temporal Trends: Hourly, Daily, Weekly metrics
- Ad Format Comparison: CTR, Engagement, Conversion across formats
- Actionable Recommendations: Data-driven strategies for creative, targeting, and scheduling

## Performance Overview (sample metrics)

| Metric | Value |
|---|---:|
| Impressions | 339,000+ |
| Clicks | 40,000+ |
| Engagement Rate | 13.6% |
| CTR | 11.8% |
| Conversion Rate | 5.0% |
| Total Ad Budget | $2.5M |
| Avg Campaign Budget | $50.7K |

## Top-performing Demographics & Timing
- Age: 1830 years
- Gender: Female
- Regions: India, United States, Germany, United Kingdom, Brazil
- Peak activity: WednesdayFriday, 5 PM9 PM (local time)

## Analytical Insights
- Audience behavior
  - Female audiences drive higher engagement on Facebook
  - Instagram shows more balanced gender engagement
  - Young adults (1830) have highest response and conversion rates
- Geographic distribution
  - India and U.S. generate highest impressions and engagement
  - Germany and U.K. show stronger purchase conversion performance
- Ad format effectiveness (example metrics)
  - Video Ads  CTR 12.0% / Engagement 13.7% / Conversion 5.05%
  - Stories  CTR 11.85% / Engagement 13.6% / Conversion 5.0%
  - Carousel  CTR 11.75% / Engagement 13.4% / Conversion 4.9%
  - Image  CTR 11.7% / Engagement 13.5% / Conversion 4.75%

## Strategic Recommendations (Quick Wins)
- Prioritize video and story creatives for higher engagement.
- Simplify checkout and landing pages to improve conversions.
- Use Meta Advantage+ and Custom Audiences for precise retargeting.
- Schedule campaigns midweek 59 PM local time.
- Reallocate budget dynamically: awareness in India & US; conversion focus in UK & Germany.
- Localize creatives for cultural relevance.
- Continuously A/B test creatives, CTAs, and landing pages.
- Integrate AI-based alerts for early detection of performance drops.

## Tools & Technologies
- Data cleaning: Microsoft Excel (Pivot Tables, Conditional Formatting, Data Validation)
- Data modeling: Power BI (relationships, hierarchies, calculated tables)
- Analytics: Advanced DAX (CALCULATE, FILTER, ALL, RELATED, SWITCH, VAR)
- Visualization: Power BI interactive visuals (cards, charts, maps, matrix)
- Data source: Meta Ads Manager (Facebook & Instagram)

## How to Explore
1. Review datasets in the Data folder:
   - ad_events_cleaned.csv
   - ads_campaigns_cleaned.csv
   - ads_cleaned.csv
   - users_cleaned.csv
2. Open the dashboard:
   - Load Meta_Ads_Performance_Dashboard.pbix in Power BI Desktop
3. Use filters to analyze by platform, region, or ad type
4. Explore pages:
   - KPI Summary — overview of campaign health
   - Audience Trends — demographic performance
   - Ad Format Comparison — format-level effectiveness
5. Static report:
   - Open Meta_Ads_Performance_Report.pdf for a snapshot of insights

## Ernest Agai Appreciates your time here.
