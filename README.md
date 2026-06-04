🌾 Agri Data Explorer
Agricultural Data Analysis using Python, SQL & Data Visualization
📌 Project Overview

Agri Data Explorer is an end-to-end agricultural data analytics project designed to explore, clean, analyze, and visualize crop production trends across different regions and years.

The project leverages Python, SQL, Pandas, Plotly, and SQLite to transform raw agricultural datasets into meaningful insights through data cleaning, exploratory analysis, SQL querying, and interactive visualizations.

This project demonstrates practical data analytics workflow skills, including:

✔️ Data Cleaning
✔️ Exploratory Data Analysis (EDA)
✔️ SQL-based Data Analysis
✔️ Data Visualization
✔️ Database Management using SQLite

🎯 Project Objectives

The main goals of this project are:

Clean and preprocess raw agricultural datasets
Analyze crop production, yield, and cultivation trends
Identify state-wise and district-wise agricultural patterns
Perform SQL-based analytical queries on agricultural data
Generate interactive visualizations for better understanding
🛠️ Tech Stack Used
Technology	Purpose
Python	Data Analysis & Processing
Pandas	Data Manipulation
NumPy	Numerical Operations
SQLite	Database Management
SQL	Querying Agricultural Data
Plotly	Interactive Data Visualization
Jupyter Notebook	Analysis Workflow
🔍 Project Workflow
1️⃣ Data Cleaning

The raw agricultural dataset was cleaned and transformed by:

Handling missing values
Renaming columns for readability
Standardizing agricultural metrics
Preparing the dataset for SQL and visualization
2️⃣ Exploratory Data Analysis (EDA)

Performed detailed analysis to identify:

Crop production trends
State-wise agricultural performance
Yield variations across crops
Oilseed and soybean production patterns
Agricultural productivity insights

Interactive visualizations were created using Plotly for better storytelling.

3️⃣ SQL Analysis

The cleaned dataset was stored in an SQLite database to perform analytical SQL queries such as:

Top producing districts
Crop-wise production comparisons
State-level agricultural insights
Year-based agricultural trend analysis

Example SQL Query:

SELECT dist_name,
       state_name,
       groundnut_production_1000_tons
FROM crop_data
WHERE year = 2017
ORDER BY groundnut_production_1000_tons DESC
LIMIT 10;
📊 Dataset Information

The dataset contains agricultural production data including:

Crop Area
Crop Production
Crop Yield
State Name
District Name
Year-wise Agricultural Records
Key Crops Included
Rice
Wheat
Maize
Soyabean
Groundnut
Sugarcane
Cotton
Oilseeds
Chickpea
Pearl Millet
Barley
Pulses and more
🚀 Key Features

✅ End-to-End Data Analytics Project
✅ Real-world Agricultural Dataset
✅ SQL + Python Integration
✅ Interactive Plotly Visualizations
✅ Structured Data Cleaning Pipeline
✅ Database-driven Analysis

📈 Sample Insights

Some insights explored in this project include:

Which states produce the highest oilseeds?
Districts with maximum groundnut production
Soybean yield trends across years
Agricultural production comparisons between crops
Regional farming productivity patterns
