# crime-demographic-trends-chicago
Analyzing violent crime trends by offender age, race, and crime severity using Python, R, SQL, and AWS tools.
Analyzing violent crime trends in Chicago by offender age, race, and crime severity (1991–2023) using Python, R, and AWS services. Overview This project explores the dynamics of violence in Chicago by analyzing violent crime data spanning from 1991 to 2023. The study focuses on victim demographics, offender age, racial disparities in victimization rates, and crime severity patterns. Through Python, R, AWS, and SQL-based analysis, the project provides insights that can guide violence reduction strategies.

Objectives Analyze if offender age influences the likelihood of domestic violence incidents.

Investigate racial disparities in victimization rates.

Identify correlations between offender age and the severity of crimes.

Technologies and Tools Python: Data preprocessing, visualization (matplotlib, seaborn), correlation analysis.

R: Statistical testing, bar plot visualizations (ggplot2).

SQL (AWS RDS): Data querying and aggregation.

AWS Glue DataBrew: Initial data exploration and profiling.

MySQL: Database schema creation and analysis.

AWS RDS: Cloud-hosted database operations.

Methodology Data Collection: Sourced from data.gov, including various demographic, crime type, and offender characteristics.

Data Processing: Used AWS Glue DataBrew for dataset summarization and cleansing; loaded data into AWS RDS (MySQL) for deeper SQL-based exploration.

Research Approach:

Question 1: Analyzed domestic violence trends across offender age groups (Python).

Question 2: Evaluated racial disparities in victimization rates with statistical testing (R).

Question 3: Assessed correlations between offender age and crime severity (Python heatmap analysis).

Key Findings Age & Domestic Violence: Offenders aged 20–39 had the highest association with domestic violence incidents.

Racial Disparities: The Black (BLK) racial group had the highest victimization rates, while the Indigenous (I) group had the lowest.

Crime Severity Patterns: Offenders aged 20–29 were associated with higher rates of violent crimes like assault, robbery, and sexual assault.

Visualizations Bar plots for age-wise domestic violence distribution.

Bar plots for victimization rates across racial groups.

Heatmaps illustrating offender age vs. crime severity correlations.

Results Interpretation Targeted interventions can be better designed for younger age groups (20–39).

Racial disparities highlight the need for community-specific violence reduction programs.

Understanding age-related crime severity trends can aid in early intervention strategies.

