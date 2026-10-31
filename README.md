# Varna Schools Performance Analysis (8-Year Study)

## 📌 Project Overview
This project performs an analytical investigation into the National External Assessment (NVO) exam results for 7th-grade students across schools in Varna, Bulgaria over an 8-year historical period. 

The primary goal is to analyze academic performance trends, compare subjects (Mathematics vs. Bulgarian Language & Literature - BEL), evaluate school stability over time, and apply fundamental mathematical and data analysis concepts using Python.

## 🧹 Data Preparation & Cleaning
- **Timeframe Consistency:** To ensure a fair and objective long-term comparison, institutions (primarily private schools) with missing data or sporadic attendance over the last 5-6 years were filtered out from the dataset.
- **Standardization:** School names were manually cleaned and standardized directly in the source files to ensure clean and readable labels for data visualization and reporting.

## 🎯 Key Questions & Objectives
1. **School Comparison:** Which top 15 schools in Varna perform consistently higher on 7th-grade national exams?
2. **Subject Dominance:** Do top schools lean more heavily towards Mathematics or Bulgarian Language & Literature (BEL)?
3. **Trends Over Time:** Are exam performance scores improving, plateauing, or declining over the 8-year dataset?
4. **Statistical Distributions:** How are school scores distributed, and what are their variance and standard deviations?

## 🧮 Mathematical & Statistical Concepts Applied
- **Descriptive Statistics:** Mean, Median, Variance, Standard Deviation, and Quartiles.
- **Linear Functions & Trendlines:** Slope analysis (rate of change over time) as an intuition for derivatives.
- **Correlation & Covariance:** Examining relationships between Mathematics and BEL scores.
- **Normal Distribution & Random Variables:** Analyzing school performance score distributions.

## 🛠️ Tech Stack & Libraries
- **Language:** Python 3.x
- **Environment:** JupyterLab
- **Libraries:**
  - `pandas`: Data manipulation and aggregation
  - `numpy`: Numerical calculations and statistical operations
  - `matplotlib`: Data visualization and charting
  - `openpyxl`: Reading Excel formatted datasets

## 📂 Project Structure
```text
├── data/
│   └── data.xlsx                 # Historical NVO score dataset (2018-2026)
├── varna_schools_analysis.ipynb   # Main analytical Jupyter Notebook
└── README.md                     # Project documentation
```

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone <your-repository-url>
   ```
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib openpyxl
   ```
3. Launch JupyterLab:
   ```bash
   jupyter lab
   ```
4. Open `varna_schools_analysis.ipynb` and run all cells.
