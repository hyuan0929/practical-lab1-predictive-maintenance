# Practical Lab 1 – Streaming Data for Predictive Maintenance

## Course Information
- **Course**: CSCN8010 – Foundations of Machine Learning Frameworks 
- **Lab**: Practical Lab 1

## Overview
This project implements a predictive maintenance pipeline using linear regression
and residual-based anomaly detection.

Historical sensor data from an industrial robot is used to train univariate
regression models for multiple axes. Synthetic test data is then generated to
simulate streaming behavior. Deviations from predicted trends are monitored in
real time, and alerts or errors are triggered when thresholds are exceeded for a
sustained duration. Detected events are persisted to a Neon PostgreSQL database
for analysis and visualization.

## Dataset
- **File**: `RMBR4-2_export_test.csv`  
- **Description**: Time-series sensor data for multiple robot axes.

## Repository Structure
```text
data/
  └─ RMBR4-2_export_test.csv
notebooks/
  └─ Lab1_Predictive_Maintenance.ipynb
requirements.txt
README.md
.gitignore
```

## Execution

The complete workflow can be executed end-to-end by running the notebook
Lab1_Predictive_Maintenance.ipynb after configuring the Neon PostgreSQL
connection string.

## Notes

The notebook was executed using a fresh kernel restart before submission.

All outputs from the final test run are preserved in the notebook.