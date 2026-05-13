# Crime Data Analysis in India using Python

This project analyzes state-wise crime statistics in :contentReference[oaicite:0]{index=0} for the years 2020, 2021, and 2022 using Python.  
The goal is to understand crime patterns across different states, compare yearly trends, and extract meaningful insights through data cleaning and visualization.

The analysis is performed in Jupyter Notebook using NumPy, Pandas, and Matplotlib.

---

## Project Overview

The dataset contains crime-related information for multiple states of India, including:

- State/UT names
- IPC crime cases for 2020
- IPC crime cases for 2021
- IPC crime cases for 2022
- Population estimate (2022)
- Crime rate
- Chargesheeting rate

This project focuses on transforming raw data into useful insights through exploratory data analysis.

---

## Tools and Technologies

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib

---

## Project Workflow

### 1. Data Collection

The dataset is collected in CSV format and loaded into a Pandas dataframe for analysis.

### 2. Data Cleaning

The dataset is cleaned before analysis:

- Checked for missing values
- Checked duplicate rows
- Removed duplicates
- Removed unnecessary columns
- Renamed columns for readability
- Verified data types

### 3. Feature Engineering

Additional columns were created:

- Total Crime (2020–2022)
- Average Crime

This improves analysis and comparison.

### 4. Exploratory Data Analysis

Performed analysis to identify:

- Highest crime states
- Lowest crime states
- Year-wise trends
- Population and crime relationship
- Chargesheeting performance

### 5. Data Visualization

Visualizations were created to understand patterns clearly.

---

## Visualizations Included

The project contains the following visualizations:

### 1. Bar Chart

Top states comparison based on total crime.

### 2. Line Chart

Year-wise crime trend from 2020 to 2022.

### 3. Scatter Plot

Relationship between population and crime.

### 4. Pie Chart

Crime share among selected top states.

### 5. Box Plot

Detection of outliers in crime data.

### 6. Multi-Line Chart

Comparison of crime values across all three years.


## Key Insights

Some major findings from the analysis:

- Certain states consistently show high crime values across multiple years.
- Crime distribution varies across states.
- A few states act as outliers due to significantly high crime numbers.
- Population shows partial relationship with crime levels.
- Year-wise comparison helps identify increasing or decreasing trends.

## Folder Structure

```text
crime-data-analysis-python/
│
├── Crime_Data_Analysis.ipynb
├── Crime_dataset.csv
├── README.md
└── images/
