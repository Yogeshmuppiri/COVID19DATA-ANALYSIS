
📊 COVID-19 Public Health Impact Analysis — New York State
A comprehensive data visualization and analytics project aimed at understanding the impact of the COVID-19 pandemic on public health in New York State, based on hospitalizations, fatalities, and vaccinations data.

📌 Objective
To assess and visualize the relationship between hospitalization rates, age-specific fatalities, and the effectiveness of vaccination efforts using real-world public datasets from the New York State Health Department. This analysis provides evidence-based insights for healthcare professionals, policy makers, and researchers.

🚀 Features
📅 Daily and weekly COVID-19 data aggregated across multiple dimensions
📉 Trend and correlation analysis between hospital beds, deaths, vaccination, and age groups
🧪 6 hypotheses tested using real-time data and statistical transformations
📈 Visualizations built in Tableau and Python to support analysis
🧹 ETL pipelines developed for preparing datasets
📁 Final visualizations used in Tableau dashboards and project report

🔄 ETL Process (Extract → Transform → Load)
This project implemented structured ETL pipelines using Python, Excel, and Tableau, depending on the hypothesis.

✅ Extract
Data was sourced from three official New York Health open data APIs:
Hospitalizations and Beds
Fatalities by Age Group
Vaccination Progress by County

All datasets were retrieved from:
https://health.data.ny.gov

🔁 Transform
Cleaned and filtered datasets to retain only relevant columns
Grouped and aggregated county-level data across date ranges
Joined datasets to perform cross-variable correlation (e.g., beds vs deaths, vaccine vs hospitalization)
Created custom columns (e.g., quarterly timeframes, age group splits, lagging columns)
Used Python (Pandas), Excel, and Tableau to clean and normalize data formats

📥 Load
Final datasets were visualized using:
Tableau Dashboards
Python visualizations
Interactive reports and animated timelines

📚 Hypotheses Tested
Patients aged 65+ are more likely to be hospitalized and experience fatalities
More COVID-19 vaccinations correlate with fewer ICU beds being occupied
A positive relationship exists between county-wise COVID-19 positive cases and fatalities
Quarterly vaccinations affect hospital admissions in the following quarter
Facilities with more acute care beds report fewer deaths
Facilities with more beds discharge more patients

📊 Tools & Tech Stack
Category	Tools Used
ETL	Python (Pandas), Excel, Tableau
Visualization	Tableau, Python (Matplotlib, Plotly)
Languages	Python, SQL (basic filtering)
Environments	Jupyter Notebook, Tableau Public
Data Sources	NY State Open Data Portal
