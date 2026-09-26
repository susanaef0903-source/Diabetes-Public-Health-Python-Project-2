# Python Project 2 — An Exploration of Public Health Data (Diabetes)

Python Analytics Class (LaGuardia) — Project 2, Option 1: public health data.

I analyze 101,766 hospital stays by diabetes patients at 130 US hospitals (1999–2008) with pandas and matplotlib.

**My group:** patients aged 70 to 80 (the largest age group)
**My measure:** time in hospital (days per stay)
**Comparison group:** patients aged 30 to 40

What's in the notebook:

- **Cleaning** — replaced "?" placeholders with real missing values, dropped three mostly-empty columns (weight, payer code, medical specialty), removed rows with unknown gender, and made the age labels readable
- **Descriptive statistics** — `describe()` for each group, a side-by-side comparison table (days in hospital, medications, diagnoses, 30-day readmissions), and a summary across all ten age groups
- **Visualizations** — bar chart of average days by age group, a side-by-side histogram of stay length for the two groups, and a two-panel chart of medications and readmission rates
- **Conclusion** — patients aged 70 to 80 average 4.6 days per stay vs. 3.8 for ages 30 to 40, take more medications (16.4 vs. 14.1), and are slightly more likely to be readmitted within 30 days (11.8% vs. 11.2%); hospital stays get longer with every age group

📓 Notebook: [diabetes_public_health_analysis.ipynb](diabetes_public_health_analysis.ipynb)
