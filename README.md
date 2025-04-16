# Measurement Phase of Lean Six Sigma

This project demonstrates the Measurement Phase of the Lean Six Sigma methodology, focusing on data generation, control charting, and process capability analysis using Python. It includes two dataset sourcing options and applies key statistical tools used in quality improvement initiatives.

## Project Overview

The goal of this activity is to simulate data collection, evaluate process behavior, and assess capability through Python-powered visualizations and statistical insights.

## Contents

### 1. Dataset Preparation

You can either:  
    **Option 1:** Generate a random datasetby specifying column names and their value ranges.  
    **Option 2:** Load an external dataset from a CSV file.  

The dataset includes metrics such as:
- Delivery Time
- Sample Size
- Defective Units

Data manipulation features allow you to dynamically add or remove rows for simulation and training purposes.

### 2. Control Charts

#### Variable Chart (I-Chart)

Used for analyzing individual data points, this chart helps in:
- Identifying process shifts
- Detecting outliers
- Determining stability of the process

#### Attribute Chart (P-Chart)

This chart evaluates:
- Proportion of defective units
- Statistical control of categorical outcomes
- Control limits and stability remarks

### 3. Capability Analysis

#### Normal Distribution

A graphical report to:
- Assess normality
- Calculate Z-scores
- Identify sigma level (performance capability)

#### Binomial Distribution

Explores defect rates through:
- Cumulative defect percentages
- Rate of defectives per sample
- Histogram for distribution
- Process sigma evaluation based on target limits

### Key Outputs
- Individual and P-Charts
- Process Capability Reports
- Statistical remarks and sigma level assessments
- Exportable visual plots

### Tools & Libraries Used
- Python
- pandas
- matplotlib
- numpy
- scipy.stats


### How to Use

Clone the repository and run the notebook in a Jupyter or Colab environment. Choose the preferred data input method and explore how the control charts and capability analysis adapt to varying process behavior.
