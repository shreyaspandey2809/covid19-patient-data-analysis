# covid19-patient-data-analysis
End-to-end data analytics project exploring COVID-19 patient trends, recovery patterns, and regional outbreaks using Python.

# COVID-19 Early Case Trend Analysis & Recovery Insights

## Overview

This project analyzes patient-level COVID-19 data to understand:

- Infection demographics
- Recovery trends
- Regional spread
- Transmission clusters
- Correlation between patient characteristics and recovery time

The project follows a complete analytics workflow including data cleaning, exploratory data analysis, statistical testing, and responsible machine learning evaluation.

---

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- Jupyter Notebook

---

## Dataset

patient.csv

Contains patient-level COVID-19 records from an early South Korea outbreak snapshot.

---

## Key Findings

- Missing data exceeded 90% for most investigation fields.
- Gender distribution among known cases was nearly balanced.
- Shincheonji Church was the largest identified transmission cluster.
- Median recovery time was 16 days.
- Linear Regression was intentionally not trained because only 24 complete observations were available.

---

## Future Improvements

- Use a later dataset with more complete records.
- Build predictive recovery models.
- Create an interactive dashboard using Plotly or Streamlit.
