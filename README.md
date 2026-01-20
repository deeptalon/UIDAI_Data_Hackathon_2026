📊 Aadhaar Enrollment Data Analysis: Spatio-Temporal Insights & Campaign Impact
📌 Project Overview
This project provides a comprehensive spatio-temporal analysis of Aadhaar enrollment across India, using data sourced from the UIDAI Data Hackathon – 2026. By integrating multiple large-scale datasets, the analysis uncovers critical patterns in enrollment volumes, demographic shifts, and the efficacy of government awareness campaigns across different geographic and administrative classifications.

🚀 Key Features
Unified Data Pipeline: Integrated three major enrollment datasets comprising over 1,006,029 records.

Geographic Granularity: Advanced mapping of states into 7 strategic regions (North, South, East, West, Central, North-East, Island) for comparative analysis.

Campaign Efficacy Modeling: Quantified the impact of "Awareness Campaigns" vs. "Non-Campaign" periods across urbanization levels.

Statistical Validation: Applied independent t-tests to validate the significance of seasonal enrollment spikes during festival periods.

Demographic Profiling: Segmented enrollment by three core age groups: 0-5, 5-17, and 18+.

🛠️ Tech Stack
Data Processing: Pandas, NumPy

Visualization: Seaborn, Matplotlib, Plotly (Geospatial Analysis)

Statistical Analysis: SciPy.stats (T-Tests)

📈 Vital Insights
The analysis yielded high-impact findings regarding the current state of Aadhaar adoption in late 2025:

Child-Centric Growth: Enrollment is heavily dominated by the 0-5 age group, accounting for 62.56% of total volume, followed by the 5-17 group at 36.52%. This highlights the shift from adult saturation to new-born enrollment.

Rural Dominance: Over 91.2% of enrollment activity occurred in Rural areas, compared to just 0.29% in Urban centers.

Campaign Dynamics: While awareness campaigns drive volume, their effectiveness declines significantly as urbanization increases.

Festival Seasonality: There is a statistically significant surge in enrollment during festival months (p < 0.001), indicating a correlation between seasonal travel/holidays and administrative activity.

State Leaders: Uttar Pradesh and Tamil Nadu emerged as the highest volume states, with districts like Azamgarh showing peak local engagement.

📋 Data Processing Highlights
The project utilized a robust cleaning and feature engineering workflow:

State Name Standardizing: Resolved inconsistencies in state naming conventions (e.g., "Puducherry" vs. "Pondicherry").

Location Classification: Programmatically assigned location types (Rural, Tribal, Semi-Rural, Urban) based on administrative density.

Time-Series Decomposition: Extracted Month, Day_of_Week, and Week_Number to identify temporal bottlenecks.

📂 Dataset Information

This is the link of cleaned dataset after merging all three enrollment dataset.(You can check cleaned dataset also.)
https://drive.google.com/file/d/1juc-PMyi9ZGMs7Bqy4mcTDsuA5c5gW18/view?usp=sharing


The analysis utilizes datasets covering the period up to December 31, 2025.

Total Records Analyzed: 1,006,029

Columns: date, state, district, pincode, age_0_5, age_5_17, age_18_greater.

🏁 Conclusion & Future Work
This analysis confirms that Aadhaar has reached near-total saturation among adults, transitioning into a service primarily for the enrollment of children and rural residents.

Future directions include:

Predictive modeling for future enrollment surges.

Integration with socioeconomic data to identify underserved tribal clusters.
