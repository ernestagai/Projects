# Project: Meta Ads Performance Analysis
A real-time Power BI analytics project designed to transform Meta Ads data into actionable insights and maximize Return on Ad Spend (ROAS) across Facebook and Instagram campaigns.
The project demonstrates end-to-end expertise — from data cleaning in Excel to data modeling and advanced DAX analytics in Power BI




Facebook Dashboard
Project Summary
The Meta Ads Campaign Performance Dashboard provides a holistic visualization of advertising performance across Meta platforms.
It integrates data analytics, business intelligence, and marketing optimization to reveal how audience demographics, ad formats, and campaign timing affect engagement and conversion.

Built in Power BI, this dashboard leverages advanced DAX functions, interactive filters, and clean data modeling to deliver clear, decision-ready insights that improve ad targeting and budget allocation.

Project Objectives
Analyze multi-platform ad performance across Facebook & Instagram
Understand audience engagement and behavior by demographics and region
Compare performance across ad formats (Image, Carousel, Stories, Video)
Generate insights to optimize ad ROI and guide strategic decision-making
Project Workflow
This project followed a structured ETL (Extract, Transform, Load) process:

Data Extraction:

Collected raw datasets exported from Meta Ads Manager covering user engagement, ad events, and campaign metadata.
Data Cleaning (Excel):

Cleaned and standardized data in Microsoft Excel, including:
Removing duplicates and inconsistencies
Normalizing date/time formats
Handling missing values
Creating calculated columns for engagement and cost metrics
Finalized four clean datasets used in Power BI:
ad_events_cleaned.csv
ads_campaigns_cleaned.csv
ads_cleaned.csv
users_cleaned.csv
Data Loading & Modeling (Power BI):

Imported cleaned Excel files into Power BI
Established data model relationships across the four datasets
ads_campaigns → ad_events (Campaign_ID)
ads → ad_events (Ad_ID)
users → ad_events (User_ID)
Built a star-schema data model with measures and calculated columns.
Data Analysis (DAX):

Implemented advanced DAX measures for performance calculations:
CTR (Click-Through Rate)
Engagement Rate
Conversion Rate
Purchase Rate
ROAS (Return on Ad Spend)
Created dynamic KPI cards and calculated tables.
Visualization & Insight Design:

Developed two interactive report pages:
Facebook Performance Dashboard
Instagram Performance Dashboard
Facebook Dashboard
Figure 2: Facebook Dashboard — key KPIs, demographics, and engagement trends.

Instagram Dashboard
Figure 3: Instagram Dashboard — performance summary and audience insights.

Key Features
Feature	Description
Cross-Platform Integration	Unified data model combining both Facebook and Instagram performance
Interactive Filters	Dynamic slicers for platform, gender, region, and age segments
Advanced DAX Analytics	Custom KPIs such as CTR, Engagement, Conversion, ROAS, and Purchase Rate
Demographic Insights	Visualization of user engagement by Age, Gender, and Country
Temporal Trends	Hourly, Daily, and Weekly performance metrics
Ad Format Comparison	CTR, Engagement, and Conversion rates across Carousel, Image, Stories, and Video ads
Actionable Recommendations	Data-driven strategies to optimize creative, targeting, and scheduling
Performance Overview
Cross-Platform Highlights
Impressions: 339K+
Clicks: 40K+
Engagement Rate: 13.6%
CTR: 11.8%
Conversion Rate: 5.0%
Total Ad Budget: $2.5M
Average Campaign Budget: $50.7K
Top-Performing Demographics
Age Range: 18–30 years
Gender: Female
Regions: India, United States, Germany, United Kingdom, Brazil
Peak Activity Periods
Days: Wednesday – Friday
Time: 5 PM – 9 PM (local time)
Analytical Insights
Audience Behavior
Female audiences dominate engagement, especially on Facebook.
Instagram shows more balanced gender engagement.
Young adults (18–30) exhibit the strongest response and conversion rates.
Geographic Distribution
India and the U.S. generate the highest impressions and engagement volume.
Germany and the U.K. demonstrate stronger purchase conversion performance.
Ad Format Effectiveness
Ad Format	CTR	Engagement Rate	Conversion Rate
Video Ads	12.0%	13.7%	5.05%
Stories Ads	11.85%	13.6%	5.0%
Carousel Ads	11.75%	13.4%	4.9%
Image Ads	11.7%	13.5%	4.75%
Strategic Recommendations
Focus on video and story-based creatives for higher engagement.
Simplify checkout and landing pages to lift conversion rates.
Use Meta Advantage+ and Custom Audiences for precision retargeting.
Schedule ads during 5–9 PM midweek when engagement peaks.
Reallocate budget dynamically:
Prioritize awareness campaigns in India and U.S.
Drive conversion campaigns in U.K. and Germany.
Localize creative messaging to align with cultural preferences.
Continuously A/B test creatives, CTAs, and ad copy.
Integrate AI-based alerts to detect performance drops early.
Tools & Technologies
Category	Tools / Techniques
Data Cleaning	Microsoft Excel (Pivot Tables, Conditional Formatting, Data Validation)
Data Modeling	Power BI Data Model (Relationships, Hierarchies, Calculated Tables)
Analytics	Advanced DAX (CALCULATE, FILTER, ALL, RELATED, SWITCH, VAR)
Visualization	Power BI Interactive Dashboard (Cards, Charts, Maps, Matrix)
Data Source	Meta Ads Manager (Facebook & Instagram)
How to Explore
Review the datasetsin Data Folder:

ad_events_cleaned.csv
ads_campaigns_cleaned.csv
ads_cleaned.csv
users_cleaned.csv
Open the dashboard:

Load Meta_Ads_Performance_Dashboard.pbix in Power BI Desktop.
Explore key visuals:

Use filters to analyze by platform, region, or ad type.
View the KPI Summary, Audience Trends, and Ad Format Comparison pages.
View the report summary:

Open Meta_Ads_Performance_Report.pdf for a static insight overview.
ects
