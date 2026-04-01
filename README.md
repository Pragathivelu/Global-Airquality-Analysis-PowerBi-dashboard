📊Global Air Quality Powerbi Dashboard
🌍 Overview

This project presents an interactive Air Quality Analysis Dashboard built using Power BI, with data preprocessing and feature engineering performed using Python.

The solution focuses on analyzing pollution trends, identifying dominant pollutants, and delivering actionable insights through interactive visualizations.

🎯 Problem Statement

Analyze global air quality data to:

Identify high pollution regions
Understand pollutant contribution
Enable data-driven environmental insights

🧠 Type of Analysis
Descriptive Analytics
Diagnostic Analytics

🛠️ Tools & Technologies
Python (Data Preprocessing & Feature Engineering)
Pandas, NumPy
Power BI
DAX

⚙️ Data Processing Pipeline (IMPORTANT 🔥)
Step 1: Data Cleaning (Python)
Handled missing values:
Removed rows with missing City
Replaced missing Country with "Unknown"
Removed duplicates
Standardized column names
Step 2: Feature Engineering (Python)
Created Dominant Pollutant feature:
Identified the highest contributing pollutant (CO, NO2, Ozone, PM2.5)
Validated AQI categories using AQI values
Step 3: Data Visualization
Imported cleaned dataset into Power BI
Built interactive dashboards with advanced visuals

📊 Dashboard Structure
🔹 Page 1: Overview Dashboard
KPI Cards (Avg AQI, Max AQI, Total Cities)
Map Visualization (City-wise AQI)
Top Polluted Cities
AQI Distribution
Scatter Plot (Pollutant correlation)
🔹 Page 2: Deep Analysis
Pollutant Contribution Analysis
Country-Level Insights
Decomposition Tree
Heatmap
Dominant Pollutant Distribution

🔍 Key Insights
PM2.5 is the dominant pollutant in high AQI regions
Strong correlation exists between PM2.5 and AQI levels
Pollution is concentrated in specific cities and countries
Different regions show different pollutant dominance patterns

🎨 Features
End-to-end pipeline (Python → Power BI) 🔥
Interactive slicers and filters
Advanced analytics visuals
Clean and modern dashboard design
