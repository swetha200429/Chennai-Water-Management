# Chennai-Water-Management
📌 Project Overview

This project analyzes rainfall and water storage levels of Chennai’s major reservoirs using Python, Pandas, and NumPy. The goal is to understand rainfall patterns, reservoir storage trends, and identify potential drought years using data analysis and visualization techniques.

🎯 Objectives

Merge and clean rainfall and reservoir level datasets
Perform feature engineering using NumPy and Pandas
Analyze rainfall vs water storage relationships
Identify heavy rainfall days using statistical methods
Generate yearly summaries and insights
Visualize trends using Matplotlib and Seaborn

📂 Dataset Description

The project uses two datasets:

chennai_reservoir_rainfall.csv
chennai_reservoir_levels.csv

Each dataset contains:

Date-wise records
Rainfall values for multiple reservoirs
Water storage levels for the same reservoirs

⚙️ Technologies Used

Python 🐍
Pandas
NumPy
Matplotlib
Seaborn

🧠 Key Features / Workflow

Data loading and merging using Pandas
Column renaming for clarity
Date parsing and time-series handling

Feature engineering:

Total Rainfall
Total Water Level
Rolling average computation (30-day smoothing)
Detection of heavy rainfall days using statistical thresholds
Grouping data by year for trend analysis
Visualization of rainfall vs reservoir storage
Extraction of insights such as peak storage and drought years

📊 Analysis Performed

Daily rainfall vs total reservoir storage comparison
30-day rolling rainfall trends
Year-wise rainfall and storage aggregation
Identification of extreme rainfall events
Detection of low storage (potential drought) years

📈 Visualizations

Time series plot of rainfall and reservoir levels
Dual-axis chart comparing rainfall vs storage levels
Trend visualization across multiple years

Output example:

chennai_water_trend.png

🔍 Key Insights

Peak reservoir storage date and value
Years with significantly low water storage
Correlation between rainfall and storage levels
Identification of heavy rainfall days

📁 Project Structure

project/
│── chennai_reservoir_rainfall.csv
│── chennai_reservoir_levels.csv
│── analysis.py
│── chennai_water_trend.png
│── README.md
🚀 How to Run the Project

Clone the repository:

git clone <repo-link>

Install dependencies:

pip install pandas numpy matplotlib seaborn

Run the script:

python analysis.py

📌 Future Improvements

Integrate machine learning models for rainfall prediction
Build interactive dashboards using Plotly or Streamlit
Include real-time data updates via APIs
Perform deeper correlation and regression analysis

👤 Author

Name: Swetha R
