## 🌍 Global Disaster Response Analytics Dashboard
## 📊 Project Overview

The Global Disaster Response Analytics Dashboard is an end-to-end data analytics project developed using Power BI.

The objective of this project is to analyze global disaster events from 2018 to 2024, focusing on disaster impact, response performance, aid distribution, and recovery trends to support data-driven decision-making.

This project demonstrates the complete Business Intelligence workflow including data cleaning, data modeling, DAX calculations, and professional dashboard design to transform raw disaster data into actionable insights.

🖼 Dashboard Preview

(Add your screenshots here)

## 📌 Key Insights

• Faster response time significantly reduces recovery duration
• Floods are the most frequent disasters, while earthquakes cause higher economic loss
• Certain countries experience high disaster impact but receive comparatively lower aid
• Response efficiency varies significantly across regions
• Higher aid allocation generally improves recovery performance
• Disaster frequency shows an increasing trend in recent years

## 📂 Step 1: Dataset Overview

The dataset contains global disaster event records between 2018 and 2024.

Key Fields

• EventID
• EventDate
• Country
• Region
• Disaster Type
• Casualties
• Economic Loss
• Aid Amount
• Response Time (Hours)
• Recovery Duration (Days)
• Efficiency Score

## 🧹 Step 2: Data Cleaning & Transformation (ETL)

Performed using Power Query in Power BI.

Key Transformations

• Removed null and duplicate records
• Standardized country and disaster type names
• Converted columns to appropriate data types
• Extracted Year, Month, and Quarter from EventDate
• Created calculated fields such as Severity Category
• Ensured consistency in economic and aid values

## 📊 Step 3: Data Modeling & DAX Calculations

A structured data model was created for analysis.

Data Model

• Fact Table: Disasters
• Date Table: Calendar (for time intelligence)
• Relationship: EventDate → Date

Key DAX Measures

• Total Disasters
• Total Casualties
• Total Economic Loss
• Total Aid
• Avg Response Time
• Avg Recovery Duration
• Efficiency Score
• % Responses within SLA

## 🎨 Step 4: Dashboard Design

• Clean and professional multi-page layout
• KPI cards for high-level summary
• Consistent color theme and formatting
• Interactive slicers for filtering data
• Focus on usability and storytelling

## 📄 Step 5: Dashboard Pages (Page-wise Description)
🔹 Page 1 — Executive Overview

<img width="904" height="475" alt="P1" src="https://github.com/user-attachments/assets/8a4c531e-54f5-497b-96b6-e8a5a2b4316d" />

Description

Provides a high-level summary of global disaster impact and trends.

Visuals Used

• KPI Cards: Total Disasters, Casualties, Economic Loss, Aid, Efficiency
• Line Chart: Disasters per Year
• Filled Map: Economic Loss by Country
• Bar Chart: Top Countries by Impact
• Table: Notable Events

Insights

• Identifies most affected countries
• Shows overall disaster trend over time
• Highlights global economic impact


<img width="907" height="480" alt="P2" src="https://github.com/user-attachments/assets/7651dfd4-de36-4587-847f-55887d7db004" />

🔹 Page 2 — Regional & Country Analysis
Description

Analyzes disaster patterns across different regions and countries.

Visuals Used

• Bubble Map: Casualties (size) and Efficiency (color)
• Stacked Bar Chart: Disaster Type distribution
• Matrix: Year vs Disaster Type

Insights

• Compares disaster impact across regions
• Identifies dominant disaster types
• Highlights high-risk countries



<img width="905" height="478" alt="P3" src="https://github.com/user-attachments/assets/4eb032ee-a1c2-4d69-8ac9-9f0066fb7e09" />

🔹 Page 3 — Response Performance
Description

Evaluates how effectively disasters are handled.

Visuals Used

• KPI Cards: Avg Response Time, Median Response Time, SLA %
• Scatter Plot: Response Time vs Recovery Duration
• Line Chart: Efficiency Trend

Insights

• Faster response leads to quicker recovery
• Identifies inefficient response regions
• Shows relationship between response and recovery


<img width="906" height="480" alt="P4" src="https://github.com/user-attachments/assets/fbbe884f-311b-46db-9d88-7463442a2d12" />

🔹 Page 4 — Aid & Funding
Description

Analyzes distribution and effectiveness of aid.

Visuals Used

• KPI Cards: Total Aid, Aid per Disaster, Aid per Casualty
• Waterfall Chart: Aid trend over years
• Treemap: Aid distribution by type/country
• Map: Aid per affected region

Insights

• Highlights imbalance in aid distribution
• Identifies underfunded regions
• Shows relationship between aid and impact


<img width="904" height="480" alt="P5" src="https://github.com/user-attachments/assets/2a763186-2cd8-4a32-935d-6e9fcf289f5d" />

🔹 Page 5 — Recovery & Forecasting
Description

Focuses on recovery performance and future trends.

Visuals Used

• KPI Cards: Avg Recovery Duration
• Decomposition Tree: Drivers of recovery duration
• Line Chart: Forecasting disaster trends

Insights

• Identifies key factors affecting recovery
• Predicts future disaster trends
• Helps in planning and preparedness

<img width="904" height="482" alt="P6" src="https://github.com/user-attachments/assets/c653d2aa-4a5d-413a-88bb-ab29afc082a0" />

🔹 Page 6 — Event Details (Drillthrough)
Description

Provides detailed analysis of individual disaster events.

Visuals Used

• Event-level data table
• Scatter Plot: Response vs Recovery
• KPI Cards: Loss, Aid, Casualties

Insights

• Enables deep analysis of specific events
• Helps understand event-level performance

🔹 Tooltip Page
Description

Displays quick insights on hover for better interactivity.

Visuals Used

• KPI Cards: Disasters, Casualties, Aid, Response Time

Insights

• Quick snapshot of selected data point
• Enhances user experience

## 🛠 Step 6: Tools & Technologies

• Power BI Desktop
• Power Query
• DAX
• Data Modeling
• CSV Dataset

## 🎯 Step 7: Project Outcome

This dashboard helps decision-makers to:

• Identify high-risk regions
• Improve disaster response strategies
• Optimize aid allocation
• Reduce recovery time
• Make data-driven decisions

## 💡 Key Skills Demonstrated

• Data cleaning and transformation
• DAX and KPI creation
• Data modeling (Star Schema)
• Dashboard design and storytelling
• Insight generation from real-world data

## 📌 Conclusion
This project demonstrates the complete Power BI analytics lifecycle—from raw data to actionable insights. It highlights how data analytics can improve disaster response, resource allocation, and recovery planning.











This project demonstrates the complete Power BI analytics lifecycle—from raw data to actionable insights. It highlights how data analytics can improve disaster response, resource allocation, and recovery planning.
