Overview

This project analyzes Twitter data from major medical congresses (e.g., ASCO) to assess Healthcare Professional (HCP) perception, engagement, and discussion trends around clinical trials and drug-related topics for a Fortune 500 pharmaceutical company.

The solution applies Real-World Evidence (RWE) analytics to social media data to generate actionable insights for Field Medical and Business Insights & Analytics teams.

Objectives
Measure congress conversation coverage against pre-brief expectations
Identify key stakeholders such as HCPs, researchers, and advocacy groups
Evaluate engagement and influence of medical voices
Analyze trial and product-level discussion trends
Assess share of voice and priority study performance
Key Features
Exploratory Data Analysis (EDA) using Python
Tag-based mapping of tweets to studies, products, and indications
User classification (HCP, researcher, advocacy, etc.)
KPI-driven analytical framework (ADF and BRD)
Interactive Power BI dashboard with three analytical views
Dashboard Views
1. Overall Congress and Coverage
Total Tweet Volume
Tagged vs Not Tagged Analysis
Unique Authors
Image Data Attachment Rate
2. Audience and HCP Engagement
HCP Share of Voice
HCP Engagement and Reach
Advocacy Participation
Top Influencers
3. Priority Studies and Insights
Study-level Share of Voice
Priority Study Coverage
Therapy Area Trends (e.g., CAR-T)
Top Study by Engagement
Tech Stack
Category	Tools
Data Analysis	Python (Pandas, NumPy)
Visualization	Power BI
Documentation	ADF, BRD
Data Source	Twitter API
Data Workflow
Twitter API → Data Cleaning and EDA (Python) → Tag Mapping → KPI Computation → Power BI Dashboard
Key Insights Delivered
Identified HCP-driven conversation patterns and influence
Measured gaps between actual conversation and pre-brief coverage
Highlighted high-impact trials and discussion topics
Evaluated competitive positioning through share of voice
Repository Structure
data/          # Processed or sample datasets  
notebooks/     # Python EDA notebooks  
dashboard/     # Power BI files or screenshots  
docs/          # ADF, BRD, KPI definitions  
README.md  
Disclaimer

This project is based on a real-world use case from a Fortune 500 pharmaceutical company. All sensitive information has been anonymized.
