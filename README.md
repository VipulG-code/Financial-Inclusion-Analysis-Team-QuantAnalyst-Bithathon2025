Financial Inclusion Analysis
Overview
This project analyzes financial inclusion trends using machine learning, Power BI visualizations, and data analysis. It focuses on identifying financial behavior patterns, predicting financial accessibility, and proposing strategies to bridge financial access gaps.

Features
Data Cleaning & Preprocessing: Handling missing values, normalizing features.
Exploratory Data Analysis (EDA): Visualizing financial trends using Power BI and Python.
Machine Learning Models: Predicting financial inclusion using Logistic Regression, Random Forest, and XGBoost.
Clustering Analysis: Segmenting financial behavior using K-Means clustering.
Time-Series Analysis: Tracking financial inclusion trends over time.
Power BI Dashboards: Interactive visualizations for policymakers and financial institutions.


Project Structure

financial-inclusion-analysis/
│── data/                  # Raw and processed datasets
│   ├── raw/               # Original datasets (CSV, XLSX)
│   ├── processed/         # Cleaned datasets
│── notebooks/             # Jupyter notebooks for EDA, modeling
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda_visualization.ipynb
│   ├── 03_machine_learning.ipynb
│── models/                # Saved machine learning models
│── reports/               # Project reports and documentation
│   ├── Quant_Analyst_Report.pdf
│   ├── GlobalFindex2021_MicrodataCodebook.pdf
│   ├── Little_Data_Book_Financial_Inclusion.pdf
│── visualizations/        # Graphs, charts, dashboards
│── src/                   # Python scripts for automation
│   ├── data_preprocessing.py
│   ├── model_training.py
│   ├── dashboard.py
│── README.md              # Project overview and instructions
│── requirements.txt       # List of dependencies
│── .gitignore             # Ignoring unnecessary files
