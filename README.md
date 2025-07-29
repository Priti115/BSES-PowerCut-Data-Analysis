# Power Cut and Energy Analysis Dashboard

## 📊 Objective
To explore trends, causes, and infrastructure gaps in power supply using historical outage and consumption data.

## 📁 Dataset Details
- Records: 9684 rows after cleaning
- Key columns: Month, Meter Type, Circle, Division, Power Cut Hours, Energy Consumption (KWH), ESO Count

## 🔍 Key Insights
- Clear seasonality in power cuts (high in summer, low in winter)
- Division and circle-based discrepancies in performance
- Weak correlation between manpower and power reliability
- Meter type impacts both consumption and outage duration

## 📈 Recommended Graphs to Include

1. **Monthly Average Power Cut Trend** – Line Plot
   - ![alt text](image.png)

2. **Total Power Cut Duration by Month** – Bar Plot
   - ![alt text](image-1.png)

3. **Seasonal Power Cut Duration Comparison** – Box or Bar Plot
   - ![alt text](image-2.png)

4. **Circle-wise Average Power Cuts** – Horizontal Bar
   - ![alt text](image-3.png)

5. **PER_CHANGE by Division** – Colored Bar (green/red)
   -![alt text](image-4.png)

6. **KWH Usage by Circle and Division** – Bar Plot
   - ![alt text](image-5.png)
   - ![alt text](image-6.png)

7. **Average Power Cut by Meter Type** – Bar Chart
   - ![alt text](image-7.png)

8. **Correlation Heatmaps ** – POWEROFF_CURR vs KWH_CURR / ESO_CURR
   - ![alt text](image-8.png)

📥 [Download Power BI Dashboard (PBIX)](https://drive.google.com/uc?export=download&id=1XrIpqIMj2-1fJAw337wHmjHkWAIYN5mD)

## 📁 Files Included
- main_analysis.ipynb
- powercut_summary_report.md
- images/
   - monthly_trend.png
   - division_change.png
   - meter_type_cut.png

## 🧠 Final Thoughts
Use these insights to build a robust outage forecasting tool or power reliability index per division.
