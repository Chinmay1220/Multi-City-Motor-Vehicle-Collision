# Multi-City-Motor-Vehicle-Collision

Overview: This project focuses on building a dimensional model to analyze motor vehicle collision data from three major cities: New York, Chicago, and Austin. The goal is to derive insights that can enhance traffic safety measures.

1. Data Staging and ETL Process
Staging Tables:

Created staging tables to temporarily hold raw data from various sources, facilitating data cleansing and preparation. These tables served as an intermediary step before transforming the data into a structured format for analysis.
ETL Jobs using Talend:

Developed Extract, Transform, Load (ETL) jobs using Talend, a robust data integration tool. The ETL process included:
Extracting data from multiple sources (e.g., city traffic databases).
Transforming the data to ensure consistency and accuracy, including data type conversions and cleaning invalid entries.
Loading the transformed data into the dimensional model, allowing for efficient querying and analysis.
Mapping Document:

Created a detailed mapping document that outlines how raw data fields correspond to the dimensions and facts in the dimensional model. This document serves as a reference for data transformations and ensures that stakeholders understand the data lineage.
Data Profiling with Alteryx and Python:

Utilized Alteryx and Python to profile the data, assessing its quality and completeness. This involved identifying missing values, outliers, and inconsistencies, ensuring that only high-quality data is used for analysis.
2. Interactive Dashboards Development
Tableau and Power BI:
Designed and developed interactive dashboards using Tableau and Power BI, which provide visual representations of the traffic accident data. Key features of the dashboards include:
Accident Frequency: Visualizations that show the number of accidents over time, helping identify trends and peak accident periods.
Severity Analysis: Charts and graphs that categorize accidents by severity, allowing stakeholders to understand the impact of collisions.
Pedestrian Involvement: Insights into the frequency and severity of accidents involving pedestrians, highlighting areas needing safety improvements.
Temporal Patterns: Analysis of accident occurrences based on time of day and day of the week, aiding in understanding when accidents are most likely to happen.
3. Actionable Insights for Traffic Safety
Accident Hotspots:

Analyzed the data to identify geographic locations with a high concentration of accidents. This information can guide city planners and traffic authorities in implementing targeted interventions.
Injury Statistics:

Compiled statistics on injuries resulting from accidents, allowing for a deeper understanding of the types of injuries sustained and the circumstances surrounding them.
Fatality Analysis:

Conducted a thorough analysis of fatal accidents to uncover patterns and contributing factors. This information is crucial for developing safety policies aimed at reducing fatalities.
Enhancing Decision-Making:

The insights generated from the analysis are intended to inform city officials and transportation agencies, helping them make data-driven decisions to improve traffic safety and reduce the incidence of accidents.
Conclusion
This project not only builds a strong analytical foundation for understanding motor vehicle collisions but also creates a toolkit for stakeholders to visualize and act on critical traffic safety data. The integration of advanced tools like Talend, Alteryx, Tableau, and Power BI demonstrates a comprehensive approach to data management and visualization, ultimately contributing to enhanced urban safety initiatives.
