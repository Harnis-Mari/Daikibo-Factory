# Daikibo Telemetry Factory Analysis [Deloitte Job Simulation]
![](Factory.jpg)

## Introduction 
The project is a job simulation data from Forage website sponsored by Deloitte Australia. The project focused on analyzes of nine (9) machine downtime across four factories located in Japan, China, and Germany. 

## Problem Statement
Through the dataset, we aim to gain insight into the following;
- Factory with the highest machine downtown.
- Machine that has the most downtown.
-  Country with the highest machine downtown.
The overall goal is to identify key areas of inefficiency and potential improvement based on machine and location-specific downtime data.

  ## Skills and Expertise
* Understanding Data: Understanding the data set, the data types, in order to identify errors, and the problems.
* Data Cleaning & Transformation: With the use of Power Query editor in powerbi, the dataset was transformed from json to table format abd cleaner by changing to appriprate data types, and changing the fonts to ensure consistency in values.
* Data Analysis: Using statistical methods, and business intelligence techniques to calculate for the downtown using DAX functions, identify key KPIs, trends, and pattern.
* Data Visualization: Using appropriate charts and cards to visualize the analysis for clear insight through the use of PowerBI.
* Insight Analysis: Understanding the findings and visuals to evaluate...
Report Writing & Presentation: Summarizing findings, explaining insights and providing recommendations in a structured professional format. The skills and expertise ensured a thorough and insightful analysis ...

## Data Modelling 
![](D-jobsim.JPG)

## Analysis & Insights
#### Factory Level Summary
* Seiko Factory (Osaka, Japan)
Records the highest total downtime among all factories. Downtime is solely attributed to the Laser Welder machine, with approximately 480 minutes.
* Shenzhen Factory (China) recorded the Second-highest overall downtime. The Laser Cutter experiences significant downtime.
Other machines (CNC, conveyobject, SpotWelder) show equal and very low downtime.
* Meiyo Factory (Japan) Exhibits low overall downtime. Two machines (Laser Cutter and HeavyDuty Drill) are affected, with the drill having slightly higher downtime.
* Berlin Factory (Germany)
Records the lowest total downtime at just 20 minutes.
Only the Furnace machine is affected.

#### Machine Level Summary
* Laser Welder: Highest downtime overall, driven by Seiko Factory in Japan.
* Laser Cutter: Second-highest downtown with issues observed in both Shenzhen and Meiyo factories.
* HeavyDuty Drill: Minor downtime reported only in Meiyo.
* Furnace: Minimal impact, only in Berlin.
Air Wrench & Metal Press: Show no significant downtime across all factories.

#### Downtime by Country
* Japan: Highest cumulative downtime, primarily due to the Laser Welder at Seiko Factory at ....
* China: Second highest downtime, led by the Laser Cutter at Shenzhen Factory.
* Germany: Lowest downtime, limited to a single instance at the Berlin Factory at 20 minutes. 

##### Summary
The Seiko Factory is located exclusively in Osaka, Japan, and has the most critical machine issue (Laser Welder).
Laser Welder is the only machine contributing the most downtime.
Air Wrench and Metal Press machines performed optimally across all factories, with no recorded downtime.
