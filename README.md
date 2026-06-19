# ApexPlanet Internship - Task 1

## 📌 Project Title
Foundational Setup & Exploratory Data Analysis (EDA)

## 🎯 Objective
The objective of this project is to set up the Python environment, clean the dataset, and perform Exploratory Data Analysis (EDA) to understand the data through statistics and visualizations.

## 🛠️ Tools & Technologies
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 📂 Dataset
- Sample - Superstore Dataset

## 📋 Task Completed

### Data Cleaning
- Loaded the dataset into a Pandas DataFrame.
- Checked for missing values.
- Removed duplicate records.
- Converted date columns to datetime format.
- Detected outliers using the IQR method.
- Saved the cleaned dataset.

### Exploratory Data Analysis (EDA)
- Generated statistical summary using `describe()` and `info()`.
- Created a Histogram to analyze Sales distribution.
- Created a Boxplot to identify outliers.
- Created a Bar Chart for category comparison.
- Created a Correlation Heatmap.
- Created a Line Chart to visualize sales trends over time.

## 📊 Key Insights
- Technology category generated high sales.
- Some transactions resulted in negative profit.
- Sales distribution is right-skewed.
- Strong correlations exist among some numerical features.
- Sales varied over different time periods.

## 📁 Project Structure

```text
apexplanet-data-analytics/
│
├── data/
│   ├── Sample - Superstore.csv
│   └── Cleaned_Superstore.csv
│
├── notebooks/
│   └── Task1_EDA.ipynb
│
├── scripts/
├── reports/
├── dashboards/
└── README.md
```

## 🚀 Outcome
Successfully completed Task 1 by performing data cleaning and exploratory data analysis using Python and Jupyter Notebook.

# ApexPlanet Data Analytics - Task 2

## Project Overview
This project demonstrates SQL fundamentals, advanced SQL concepts, and Python-SQL integration using SQLite. The dataset was imported into SQLite, queried using SQL, and accessed through Python using SQLAlchemy and Pandas.

## Tasks Completed
- Created SQLite database
- Imported Superstore dataset into SQLite
- Executed SQL queries using:
  - SELECT
  - WHERE
  - ORDER BY
  - GROUP BY
  - HAVING
  - UPDATE
  - DELETE
  - ALTER TABLE
  - CREATE VIEW
- Connected Python with SQLite using SQLAlchemy
- Executed SQL queries in Python using Pandas
- Answered business questions using SQL queries
- Created a reusable database connection script (`db_utils.py`)

## Tools Used
- Python
- SQLite
- SQLAlchemy
- Pandas
- Jupyter Notebook
- GitHub

## Project Structure

```
apexplanet-data-analytics/
│
├── data/
├── notebooks/
├── scripts/
├── reports/
├── dashboards/
└── README.md
```

## Author
Shree Vathy
