# MLB-Baseball-Performance-Dashboard

A comprehensive Power BI analytics project exploring MLB batting, fielding, and team-level performance from 2015 to 2024.

📌 Project Overview
This project delivers an interactive MLB Performance Dashboard built in Power BI, designed to help users evaluate hitter efficiency, power output, fielding reliability, team KPIs, and long-term trends.

The dashboard is ideal for:
- Analysts looking for actionable insights
- Coaches reviewing player performance
- Fans interested in advanced baseball metrics
- Students building sports analytics portfolios

🎯 Project Objective
The primary objective is to transform raw MLB hitting and fielding data into a clear, interactive analytical tool that highlights:
This dashboard supports informed decision-making by revealing hidden patterns and performance gaps across the league.

⚙️ Process
1. Data Collection & Cleaning
Integrated multiple seasons (2015–2024) of batting and fielding datasets.
Cleaned data in Power Query (null removal, standardized team names, data type corrections).
Created calculated stats such as AVG, OBP, SLG, Barrel Rate, Rdrs/yr, Defensive Efficiency, etc.

2. Data Modeling
- Built a relationship model connecting:
- Player tables
- Team statistics
- Seasonal metrics

Engineered new measures using DAX for:
- KPI scoring
- Mendoza Line benchmarks
- OBP targets
- Error reductions
- Player efficiency ratios

3. Dashboard Development
Designed a multi-page interactive Power BI experience:
- Scatterplots
- Gauges
- Trend charts
- Treemaps
- Stacked bars

🖥️ Dashboard Preview

🔹 Power Hitters vs Efficient Hitters  
<img width="1280" alt="image" src="https://github.com/user-attachments/assets/c68e25df-bd86-4531-af2c-733b0910cc4e" />

🔹 Player Comparison (AVG vs Mendoza Line)  
<img width="1280" alt="image" src="https://github.com/user-attachments/assets/3a114cbd-9ac3-42a7-a05c-39e704cf1215" />

🔹 Team Fielding Overview  
<img width="1280" alt="image" src="https://github.com/user-attachments/assets/8348535c-0d01-41c6-91d2-9d2b9f253b7f" />

🔹 Team Efficiency – Errors by Position  
<img width="1280" alt="image" src="https://github.com/user-attachments/assets/8ae697a9-0fe0-41e0-b2f3-60593fc9fc40" />

🔹 Batting Trends Over Time  
<img width="1280" alt="image" src="https://github.com/user-attachments/assets/48b622eb-d152-4a09-b756-2001603f431e" />

🔹 Team-Oriented Performance (Astros Example)  
<img width="1280" alt="image" src="https://github.com/user-attachments/assets/a0d197ca-51a0-4acf-94d7-eeb0b00bc0ac" />

🔹 Team KPIs vs Goals  
<img width="1280" alt="image" src="https://github.com/user-attachments/assets/5cb353f0-fce5-4e96-8925-a891ebaae178" />

📊 Project Insights
- Power hitters display high HR output but show wide variance in barrel rate across seasons.
- Efficiency hitters show strong correlation between AVG and OBP, confirming consistency over volume.
- Fielding analysis reveals clear gaps in defensive performance, especially at infield positions such as SS and 3B.
- Team trends show fluctuations in batting metrics year over year, with league-wide OBP and SLG increasing post-2019.
- The Astros’ KPI dashboard (2024) highlights where offensive targets fell short and where defensive goals exceeded expectations.
- Errors cluster heavily by position, helping teams pinpoint where defensive improvement is needed.

🏁 Final Conclusion
This Power BI dashboard provides a complete analytical view of MLB performance by combining advanced metrics, visual storytelling, and interactive features.

📦 Technologies Used
- Power BI
- Power Query
- DAX
- Excel / CSV Data Sources
