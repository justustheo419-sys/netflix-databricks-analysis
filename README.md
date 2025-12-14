# Netflix Data Analysis using Databricks

## 📌 Project Overview
This project analyzes Netflix content data using Databricks and Apache Spark. 
The objective is to explore content distribution, trends across years, 
popular genres, and country-wise availability.

## 🛠 Tools & Technologies
- Databricks
- Apache Spark (PySpark)
- Python
- SQL
- Delta Lake
- GitHub

## 📂 Dataset
- Dataset Name: Netflix Movies and TV Shows
- Format: CSV
- Source: Public Netflix dataset
- Key Columns:
  - show_id
  - type
  - title
  - director
  - cast
  - country
  - date_added
  - release_year
  - rating
  - duration
  - listed_in
  - description

## 🔄 Project Workflow
1. Loaded Netflix CSV into Databricks
2. Cleaned missing values and standardized columns
3. Converted date fields into proper format
4. Performed exploratory data analysis
5. Generated insights using Spark SQL and PySpark
6. Stored processed data using Delta tables

## 📊 Key Insights
- Movies dominate Netflix content compared to TV Shows
- Significant growth in content after 2015
- United States contributes the highest number of titles
- Drama and International Movies are the most common genres

## ▶ How to Run the Project
1. Upload the notebook to Databricks
2. Upload `netflix_titles.csv` to DBFS
3. Attach a Spark cluster
4. Run cells sequentially

## ✅ Conclusion
This project demonstrates scalable data analysis on a real-world dataset 
using Databricks and Spark, enabling efficient processing and insights generation.
