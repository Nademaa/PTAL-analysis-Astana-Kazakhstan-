# PTAL-analysis-Astana-Kazakhstan-
This is my dissertation for undergraduate Geography BSc degree at UCL 2025. The topic is Assessing Public Transport Accessibility in Astana, Kazakhstan


This project applied the Public Transport Accessibility Level (PTAL) methodology (originally developed by Transport for London) to assess spatial disparities in bus accessibility across Astana, Kazakhstan. The objective was to produce a citywide Accessibility Index (AI) and identify underserved areas, supporting more equitable transport planning. The final map reveals areas with lower access to public transport (blue, level 1) and areas with higher access to public transport (red, level 10). Relation of public transport accessibility to some socio-economic factors was explored as well. 

Tools: Excel, QGIS, R (ggplot2, r5r, tmap, tidyverse, sf, osmdata, etc.).

Methodology:  
-	Data cleaning using R (tidyr, dplyr, stringr) and Excel (lookups, pivot tables)
-	Routing & Accessibility Calculations: Used R (r5r package) to model walking access times and compute Scheduled and Average Waiting Times 
-	Adaptation of PTAL methodology: calculated AI for each location using walking time to nearest bus stops, service frequency, and a reliability factor.
-	Visualisations: The calculated AI values were classified into PTAL bands (Levels) using the quantile method to highlight areas with different levels of accessibility.

Key Findings:
- Central districts demonstrated high accessibility, benefiting from dense bus networks and frequent services.
- Peripheral areas, particularly on the Left Bank (in the south) of the Yesil River, showed limited connectivity.
- A visible divide in access mirrored Astana’s historical urban development.
- Population size modestly correlated with accessibility; however, income levels did not show a clear trend.
- The analysis also projected potential improvements from the future Light Rail Transit (LRT) system, especially in underserved zones.
