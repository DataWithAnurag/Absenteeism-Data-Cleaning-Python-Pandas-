# Absenteeism-Data-Cleaning-Python-Pandas-
Cleaned and pre-processed employee absenteeism data, improving dataset reliability by over 90%. Resolved 100% of missing values, corrected inconsistent data types, and eliminated duplicate records using Pandas. 

# 1-🗂️ Absenteeism Data Preprocessing

The dataset contained 24 different absence reasons.

For memory optimization and simplification, I grouped these reasons into 4 categories:

1 → Group 1

2 → Group 2

3 → Group 3

4 → Group 4

Replaced the original "reason" column with these numeric group codes (1–4).

# 2 - Dropped unnecessary tables/columns to reduce dataset size and improve efficiency.

# 3- Cleaning Performed

Standardized column names for consistency.

Converted the Date column into datetime format for easier time-based analysis.

Added a derived column for day of the week to identify weekday trends.

Checked and handled missing values — removed or imputed where appropriate.

Ensured categorical columns (e.g., Reason for Absence) have consistent category codes.

Removed duplicate rows to avoid skewing analysis.


# 4- Implemented a backup strategy to save the file after major transformations, ensuring data safety and version control.

# 5-For visualization and Exploratory Data Analysis (EDA), I used Tableau to create interactive dashboards and insights.

