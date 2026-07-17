# Breast Cancer Data Analysis in Excel

## Project Overview
This project explores a comprehensive breast cancer dataset using Microsoft Excel to identify underlying medical patterns, summarize key statistics, and visualize critical insights. The analysis demonstrates end-to-end data processing, including rigorous data cleaning, exploratory data analysis (EDA), and interactive dashboard creation.

The primary goal was to transform raw clinical data into meaningful information that supports a clearer understanding of tumor characteristics through interactive visualizations and summary metrics.

## Objectives
* **Clean and prepare** the dataset for accurate statistical analysis.
* **Explore relationships** and correlations between different physical variables of tumor cells.
* **Compare clinical metrics** between Malignant and Benign diagnoses.
* **Design and build** an interactive Excel dashboard to communicate key findings dynamically.

## Dataset
The dataset contains structured clinical measurements collected from breast cancer patients, featuring key attributes such as:
* **Core Metrics:** Radius, Texture, Perimeter, Area
* **Structural Features:** Smoothness, Compactness, Concavity, Symmetry, Fractal Dimension
* **Target Variable:** Diagnosis (Malignant vs. Benign)

## Tools & Techniques Used
* **Software:** Microsoft Excel
* **Analysis:** Pivot Tables, Advanced Excel Formulas (`VLOOKUP`, `IF`, Logical Functions)
* **Visualization & Reporting:** Pivot Charts, Slicers, Conditional Formatting, KPI Cards
* **Methodology:** Data Cleaning, Exploratory Data Analysis (EDA), Dashboard Architecture

## Data Cleaning & Preprocessing
To ensure data integrity, the following preprocessing workflow was executed:
1. **Missing Value Audit:** Inspected the dataset for null values or missing data points to avoid skewed metrics.
2. **Deduplication:** Identified and eliminated duplicate records to maintain statistical accuracy.
3. **Type Standardisation:** Verified that continuous numerical features and categorical data types were uniformly formatted.

## Analysis & Key Insights
Through exploratory analysis, the following trends were uncovered:
* **Diagnosis Distribution:** Clear classification breakdown establishing the baseline ratio of malignant to benign cases within the cohort.
* **Tumor Characteristics:** Distinct numerical variances exist between benign and malignant cases—specifically, malignant tumors demonstrated noticeably higher mean values in features like `Area`, `Perimeter`, and `Concavity`.
* **Dynamic Exploration:** Integrating multi-variable slicers allowed for real-time comparative analysis across distinct patient segments.

## Dashboard Features
The interactive Excel dashboard contains:
* **Comparative Charts:** Visual distribution of diagnosis categories alongside feature-by-feature comparisons.
* **Interactive Slicers:** Cross-filtering functionality that lets users segment the data instantly by diagnosis types or custom metric ranges.

## Dashboard Preview
![Excel Dashboard Preview](https://github.com/Imani-hub-pixel/Excel-projects/blob/main/Breast%20cancer%20data%20analysis/1778838950952.jfif)

## Repository Structure
```
Breast-Cancer-Excel-Analysis/
│
├── Dataset/                  # Contains the raw/cleaned source data
├── Excel Dashboard.xlsx     # Main workbook featuring data, pivot sheets, and dashboard
├── Images/                   # Visual assets and documentation screenshots
│   └── dashboard.png
└── README.md                 # Project documentation
