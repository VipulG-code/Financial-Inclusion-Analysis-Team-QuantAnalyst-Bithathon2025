# Financial Inclusion Analysis

## Overview
This project analyzes financial inclusion trends using **machine learning, Power BI visualizations, and data analysis**. It focuses on **identifying financial behavior patterns, predicting financial accessibility, and proposing strategies to bridge financial access gaps**.

## Features
- **Data Cleaning & Preprocessing**: Handling missing values, normalizing features, and feature engineering.
- **Exploratory Data Analysis (EDA)**: Visualizing financial trends using Power BI and Python.
- **Machine Learning Models**: Predicting financial inclusion using Logistic Regression, Random Forest, and XGBoost.
- **Clustering Analysis**: Segmenting financial behavior using K-Means clustering and hierarchical clustering.
- **Time-Series Analysis**: Tracking financial inclusion trends over time using statistical and ML models.
- **Power BI Dashboards**: Interactive visualizations for policymakers and financial institutions.
- **Automated Reporting**: Generating insights and reports automatically for financial decision-making.

## Project Structure
```
financial-inclusion-analysis/
│── data/                  # Raw and processed datasets
│   ├── raw/               # Original datasets (CSV, XLSX)
│   ├── processed/         # Cleaned datasets, feature-engineered data
│── notebooks/             # Jupyter notebooks for EDA, modeling
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda_visualization.ipynb
│   ├── 03_feature_engineering.ipynb
│   ├── 04_machine_learning.ipynb
│   ├── 05_clustering_analysis.ipynb
│   ├── 06_time_series_analysis.ipynb
│── models/                # Saved machine learning models
│   ├── logistic_regression.pkl
│   ├── random_forest.pkl
│   ├── xgboost.pkl
│── reports/               # Project reports and documentation
│   ├── Quant_Analyst_Report.pdf
│   ├── GlobalFindex2021_MicrodataCodebook.pdf
│   ├── Little_Data_Book_Financial_Inclusion.pdf
│   ├── README.md
│── visualizations/        # Graphs, charts, dashboards
│── src/                   # Python scripts for automation
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── model_training.py
│   ├── clustering.py
│   ├── time_series_analysis.py
│   ├── dashboard.py
│── requirements.txt       # List of dependencies
│── .gitignore             # Ignoring unnecessary files
```

## Datasets Used
- **Global Findex Database 2021** (World Bank)
- **Country-Level Financial Data**
- **Microdata on Financial Inclusion**
- **Custom Processed Financial Data**

## Dependencies
To install all necessary dependencies, use:
```bash
pip install -r requirements.txt
```
If additional libraries are required, manually install them using:
```bash
pip install package_name
```

## License
MIT License

## Contributors
- **Vipul Ghodake** 
- **Samarth Bolaj**
-  **ganesh Shinde** 


## Contact
For inquiries, contact: `vipulghodake1452@gmail.com`

## Acknowledgements
- **World Bank** for Global Findex Data
- **Machine Learning & Data Science Communities** for open-source tools

