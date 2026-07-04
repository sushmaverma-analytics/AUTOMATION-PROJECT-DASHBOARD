# AUTOMATION-PROJECT-DASHBOARD
The Automation Project Dashboard is an end-to-end Business Intelligence project built using Microsoft Fabric and Power BI. The dashboard provides insights into automation projects across different countries, industries, project statuses, and automation types. 
# 📸 Dashboard Preview
<img width="1240" height="683" alt="Screenshot 2026-07-05 031240" src="https://github.com/user-attachments/assets/3b27f6ec-ebb1-48cb-9f73-ad51f04ce89a" />



#  End-to-End Microsoft Fabric Workflow
Created a Microsoft Fabric Workspace.
Created a Lakehouse inside the workspace.
Imported three CSV files into the Lakehouse.
Used Dataflow Gen2 to perform ETL operations:
Data cleaning
Data type conversion
Handling null values
Text standardization
Loaded the transformed data into Lakehouse Tables.
Created a Semantic Model.
Built relationships between the tables using a Star Schema.
Created a Calendar (Date Dimension) for time intelligence.
Developed DAX measures for key business metrics.
Built an interactive Power BI report with KPIs, charts, slicers, AI visuals, and business insights.

# Microsoft Fabric Workspace
          │
          ▼
Create Lakehouse
          │
          ▼
Import CSV Files
(automation_projects.csv,
rpa_companies.csv,
software_bots.csv)
          │
          ▼
Dataflow Gen2
(ETL Process)
• Data Cleaning
• Data Type Changes
• Remove Null Values
• Trim & Replace Values
          │
          ▼
Load Cleaned Data
into Lakehouse Tables
          │
          ▼
Create Semantic Model
          │
          ▼
Data Modeling
• Relationships
• Star Schema
          │
          ▼
Create Calendar Table
(Date Dimension)
          │
          ▼
Create DAX Measures
• Total Budget
• Total Savings
• Total Projects
• Average Budget
          │
          ▼
Build Interactive Power BI Report
          │
          ▼
Dashboard & Business Insights

# 🛠 Tech Stack
Technology	                   Purpose
Microsoft Fabric	             End-to-end analytics platform
Lakehouse	                     Data Storage
Dataflow                       Gen2	ETL
Semantic Model	               Data Modeling
Power BI	                     Dashboard Development
DAX	                           Business Calculations
Calendar Table	               Time Intelligence

# 🎯 Business Problem

Organizations running multiple automation projects often struggle to answer questions such as:

Which automation types consume the highest budget?
Which projects generate the greatest savings?
Which countries execute the most automation projects?
What trends exist over time?
Which business factors influence automation savings?
Which project categories require more investment?

This dashboard provides a centralized view to answer these business questions.

# 🎯 Objectives
Analyze automation project performance.
Track total budget and annual savings.
Monitor project status.
Compare automation categories.
Identify influential factors affecting savings.
Analyze trends over time.
Enable interactive filtering.

# 📅 Calendar Table

A separate Date Dimension was created containing

Year
Quarter
Month
Month Number
Month Year
Week
Day
Day Name

This enables Time Intelligence calculations.

# 📊 KPIs

The dashboard contains

✅ Total Projects

✅ Total Budget

✅ Total Savings

✅ Average Budget

# 📈 Visualizations

The report includes

KPI Cards
Bar Chart
Column Chart
Line Chart
Matrix
Decomposition Tree
Key Influencers
Slicers
Date Filter
Automation Type Filter

# 🧮 DAX Measures

Examples

Total Budget =
SUM(automation_projects[budget_usd])
Total Savings =
SUM(automation_projects[annual_savings_usd])
Total Projects =
DISTINCTCOUNT(automation_projects[project_id])
Average Budget =
AVERAGE(automation_projects[budget_usd])

# 🏆 Skills Demonstrated
Microsoft Fabric Workspace
Lakehouse
Data Ingestion
Dataflow Gen2 (ETL)
Data Cleaning
Semantic Model
Star Schema
Relationships
Calendar Table
DAX
Power BI Report Development
Interactive Dashboard Design
Business Intelligence
Clear All Slicer & Q&A Search Button
Matrix
AI Visuals (Key Influencers & Decomposition Tree)

# 👩‍💻 About Me

Sushma Verma

📊 Aspiring Data Analyst | Microsoft Fabric | Power BI | SQL | Python | Excel & Fundamentals of AI

GitHub: https://github.com/sushmaverma-analytics
LinkedIn:(www.linkedin.com/in/sushma-verma-0a5bb5372)
