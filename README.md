# Hospital Readmission Analysis (Advanced Data Acquisition & Tableau Dashboard)
## Overview
This project integrates SQL‑based data acquisition with Tableau visualization to analyze hospital readmission trends across multiple facilities. By combining the WGU medical dataset with an external hospital admissions dataset, the project demonstrates end‑to‑end data handling, from database creation and data loading to dashboard development and insight generation.
## Datasets
- WGU Dataset: Provided medical and readmission data
- External Dataset: Riyadh Hospital Admissions Dataset (2020–2024)

Both datasets were loaded into PostgreSQL, cleaned, standardized, and combined for analysis.

## Dashboard Navigation
- Total Readmissions: Compare readmission percentages across hospitals. Select one or multiple hospitals and toggle Yes/No to isolate readmitted vs. non‑readmitted patients.
- Readmission Details – Gender: Explore gender‑specific readmission trends. Filter by hospital or toggle Male/Female to focus on demographic differences.
- Readmission Details – Age Group: Analyze readmission rates across age groups using an interactive bubble chart. Select specific hospitals or age ranges for deeper insight.
## SQL Code Used
The project includes:
- Table creation for the external dataset
- Data loading using COPY
- Adding a primary key
- Creating a calculated readmission field

These steps prepare the data for integration with the WGU dataset and Tableau.
## Key Insights
- WGU Hospital’s overall readmission rate (36.69%) is lower than competing hospitals.
- Female patients at WGU have a significantly higher readmission rate (50.18%) compared to other hospitals.
- Readmission rates increase across all age groups, with the 66+ age group showing the largest disparity.
- These insights highlight opportunities for targeted interventions in older and female patient populations.
## Data Preparation
- Created a new SQL table for the external dataset
- Loaded and standardized the data
- Added a calculated readmission indicator
- Standardized fields (age group, gender, hospital name) in Tableau
- Unified datasets using Tableau’s data model
## Dashboard Development
- Connected Tableau to PostgreSQL
- Joined/unioned datasets
- Built visualizations for total readmissions, gender trends, and age‑group patterns
- Designed dashboards with colorblind‑friendly palettes
- Created a Tableau Story to present insights in a clear, structured sequence
## Limitations
- Differences in hospital size, patient populations, and regional factors may influence readmission rates
- External dataset structure may not perfectly align with WGU’s dataset
- Comparisons across hospitals should be interpreted with these limitations in mind
## Conclusion
This project demonstrates advanced data acquisition, SQL data preparation, and Tableau visualization skills. By integrating multiple datasets and building an interactive dashboard, the analysis provides actionable insights into hospital readmission trends and highlights key demographic groups for targeted improvement.
## Technologies Used
- PostgreSQL
- SQL
- Tableau
- Data modeling & ETL
- Data visualization & storytelling
