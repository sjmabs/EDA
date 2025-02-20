# UK House Prices EDA Portfolio Project

## Overview

This project is an **Exploratory Data Analysis (EDA)** of UK house prices using historical data. The goal is to analyse trends, regional variations, and economic influences affecting property values.

## Dataset

- **Source**: [UK House Price Index (HPI) - December 2024](https://www.gov.uk/government/statistical-data-sets/uk-house-price-index-data-downloads-december-2024)
- **Key Fields**:
  - Transaction Date (Year, Month)
  - Price Paid (£)
  - Property Type (Detached, Semi-Detached, Flat, Terraced)
  - Old/New (Newly built or existing property)
  - Tenure Type (Leasehold/Freehold)
  - County, Region
  - Postcode

## Objectives

- **Identify house price trends over time and across regions/countries.**
- **Explore affordability and investment potential.** **To do
- **Understand the impact of economic factors such as interest rates and inflation.** **To do
- **Provide business insights for investors and home buyers.** **To do

## Project Steps

The following steps were taken to ensure a thorough and professional workflow.

### 1. Data Collection

- The housing dataset listed above from the UK Government website.
- Identifying any missing values and inconsistencies within the dataset.

### 2. Data Cleaning & Preprocessing

- Converted date columns to proper datetime format.
- Handled missing values and standardised categorical variables.

### 3. Exploratory Data Analysis (EDA) **TO DO

- **Overall Trends:** Line charts showing house price growth over time for property types and First-Time buyers.
- **Regional Variations:** Bar charts comparing prices across different UK regions/countries.
- **Price Distribution:** Histograms, boxplots, and violin plots to visualise variations in property prices.
- **Economic Impact:** Correlation between inflation, interest rates, and house prices.

### 4. Insights & Conclusions **TO DO

- Highlight key trends in house price growth.
- Identify regions with the highest and lowest price changes.
- Provide actionable insights for buyers and investors.

## Tools & Libraries

- **Python**: Pandas, NumPy
- **Visualisation**: Matplotlib, Seaborn, (Folium - investigate this)
- **Notebook**: Jupyter Notebook
- **Version Control**: GitHub

## Repository Structure

```
/uk-house-prices-eda
│── data/                    # Raw and cleaned datasets
│── notebooks/               # Jupyter notebooks for analysis
│── visualisations/          # Saved graphs and charts
│── README.md                # Project documentation
│── requirements.txt         # Dependencies
```

## How to Use

1. Clone the repository:
   ```sh
   git clone https://github.com/sjmabs/eda.git
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Open and run the Jupyter Notebook:
   ```sh
   jupyter notebook notebooks/eda.ipynb
   ```

## Future Work

- Incorporate external datasets (e.g., income levels, employment rates) to enhance insights.
- Use **machine learning models** to predict future house price trends.
- Develop an interactive dashboard using **Streamlit or Tableau**.

## Contact

If you have any questions or suggestions, feel free to reach out!

---

**Author:** Shaun Mabin\
**LinkedIn:** https://www.linkedin.com/in/shaun-mabin-862bb5104 \
**GitHub:** sjmabs

