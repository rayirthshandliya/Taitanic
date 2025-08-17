
# Decision Log

1. Exploratory Data Analysis (EDA):
   - Ran .info() and .describe() for dataset overview.
   - Generated NA Heatmap to visualize missing data patterns (saved as na_heatmap.png).
   - Plotted Fare distribution against Passenger Class (saved as fare_vs_pclass.png).

2. Missing Values:
   - Applied impute & flag technique for selected columns.
   - Columns with excessive missingness were dropped.

3. Outliers:
   - Treated 'Fare' column outliers using chosen method (e.g., IQR/boxplot).

4. Dataset:
   - Final cleaned dataset saved as clean_v1.csv
