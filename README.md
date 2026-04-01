# analytics-dashboard-powerbi
Analytics Platform Dashboard (Power BI Project)
Project Overview-
This project focuses on analyzing user behavior on an analytics platform using Power BI.
The goal is to understand:
How users interact with different features
Where users drop off in the workflow
How engagement varies across user segments

The dashboard provides insights that can help improve user experience and product adoption.

Dashboard Pages-
1. Platform Overview
Total Users, Total Events, Daily Active Users
Feature usage across different stages
Event distribution
User activity trends over time

Purpose: To get a high-level understanding of platform usage.

2. User Funnel Analysis-
User journey from Upload → EDA → Model → Export
Conversion rates between stages
Drop-off analysis

Key Insight: The largest drop-off occurs after the upload stage, indicating early-stage friction.

3. User Segmentation Analysis
Comparison across Free, Pro, and Enterprise users
Feature usage by plan type
Conversion rates by segment
Active user trends

Key Insight: Enterprise users show higher engagement and better conversion rates compared to free users.

Data Model: The dataset includes three main tables:

-Users – user details (country, plan type, signup date)
-Sessions – session-level activity
-Events – user actions (upload, EDA, model, export)

Relationships:
One user → many sessions
One session → many events
(A date table is used for time-based analysis.)

Documentation-
Theme 1: Dashboard explanation
Theme 2: Secure document access solution
ER Diagram included

Tools Used-
Power BI, DAX (Data Analysis Expressions), Notion (for documentation), Mockaroo (data generation)

Insights-
Significant drop-off occurs after the upload stage
Users who reach EDA are more likely to continue
Enterprise users have higher engagement and conversion rates
Free users show lower progression across stages

Future Improvements
-Add real-time data integration
-Improve onboarding experience for new users
-Enhance dashboard interactivity
👤 Author

[Your Name]
