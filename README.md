# SAP Inventory Data Cleaning

A data analytics portfolio project focused on cleaning, standardizing, and analyzing synthetic SAP inventory data using Python.

## Project Overview

This project demonstrates a basic data analytics workflow using inventory data from two locations: Tallinn Plant and Tartu Plant.

The goal is to improve data quality, explore inventory distribution, analyze monthly stock quantity trends, and prepare the cleaned dataset for further analysis.

**Note:** The dataset is synthetic and does not represent real company inventory records.

## Dataset

The project uses two synthetic inventory datasets representing two locations:

- Tallinn Plant
- Tartu Plant

The datasets contain material identifiers, categories, stock quantities, posting dates, and plant locations.

## Tools and Technologies

- **Python** — data processing and analysis
- **Pandas** — data cleaning, transformation, and aggregation
- **NumPy** — numerical operations
- **Matplotlib and Seaborn** — data visualization
- **Jupyter Notebook** — interactive analysis
- **CSV, JSON, and Excel** — data export formats

## Project Workflow

### 1. Data Loading and Integration
Loaded two CSV files and combined them into a single DataFrame.

### 2. Data Quality Checks
Inspected data types, missing values, and duplicate records. Removed fully empty rows.

### 3. Data Cleaning
Standardized material categories and plant locations, cleaned stock quantities, and converted posting dates into a consistent datetime format.

### 4. Inventory Analysis
Identified the top 5 materials by total stock quantity and compared inventory levels between the two locations.

### 5. Data Visualization

Created visualizations to explore inventory distribution, identify materials with the highest stock quantities, and compare monthly stock trends across both locations.

**Stock Distribution by Location**

<img width="900" height="700" alt="stock_distribution_by_location" src="https://github.com/user-attachments/assets/94f87c8b-dd66-4ef8-af63-2bb5d196423a" />


**Top 5 Materials by Stock Quantity**

<img width="1100" height="600" alt="top_5_materials_by_stock" src="https://github.com/user-attachments/assets/cdf83fe2-1e20-4e31-ba52-3a539bf3805b" />


**Monthly Stock Trend by Location**

<img width="1200" height="600" alt="monthly_stock_trend_by_location" src="https://github.com/user-attachments/assets/901f2c18-034c-4cec-9bbe-8d24669d78de" />


### 6. Data Export
Exported the cleaned dataset to CSV, JSON, and Excel formats.

## Key Findings

- Tartu Plant accounted for approximately **63.1%** of the total recorded stock quantity.
- Tallinn Plant accounted for approximately **36.9%**.
- **25 records** had a stock quantity of zero.
- The top 5 materials by total stock quantity were identified.
- Monthly stock quantity trends were visualized for both locations.

These findings describe the synthetic dataset used in this project and should not be interpreted as real business performance.

## Project Structure

```text
sap-inventory-data-cleaning/
├── data/
│   ├── sap_export_plant1.csv
│   └── sap_export_plant2.csv
├── images/
├── notebooks/
│   └── app.ipynb
├── Output/
│   ├── cleaned_sap_inventory.csv
│   ├── cleaned_sap_inventory.json
│   └── cleaned_sap_inventory.xlsx
├── requirements.txt
└── README.md
```

## Skills Demonstrated

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Data aggregation with Pandas
- Date and text standardization
- Data visualization
- Exporting structured data
- Organizing a data analytics project

## Conclusion

This project demonstrates an end-to-end introductory data analytics workflow, from combining and cleaning raw data to analyzing inventory patterns, visualizing results, and exporting the final dataset.

The project uses synthetic data for educational and portfolio purposes.
