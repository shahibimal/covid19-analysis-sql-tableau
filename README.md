# COVID-19 Data Exploration 🌍

##  Project Overview
As a **Computer Engineering Student**, I built this project to demonstrate the full data pipeline—from raw data cleaning to advanced SQL analysis. 

## 🛠️ Tech Stack
* **Excel:** Initial data profiling and column reduction.
* **SQL Server (T-SQL):** Data transformation, Joins, CTEs, and Window Functions.

## 📈 Key Engineering Logic Used
* **Data Cleaning:** Manually processed the raw Excel dataset to remove irrelevant features and prepare for SQL import.
* **Error Handling:** Used `NULLIF` to prevent mathematical errors (division by zero) and `CAST/CONVERT` for data type consistency.
* **Rolling Aggregations:** Implemented Window Functions to calculate a running total of vaccinations per country.

## 📁 Files
* `Covid_Data_Exploration_Project.sql`: The full analytical script.
* `CovidDeaths.xlsx`: The cleaned dataset.
* `CovidVaccinations.xlsx`: The cleaned dataset.
