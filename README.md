# Los Angeles Crime Data Analysis (2020 - 2023)

This project provides a comprehensive Exploratory Data Analysis (EDA) of crime trends in Los Angeles from **2020 to 2024**. Using real-world data from the LA City Open Data portal, this analysis uncovers patterns in crime types, geographical distribution, and reporting delays.

## 📊 Project Overview

The primary goal of this analysis is to answer key questions regarding public safety and crime patterns:
* **Temporal Trends:** How have crime rates evolved annually and monthly between 2020 and 2024?
* **Reporting Efficiency:** What is the average time gap (`reported_after`) between the occurrence of a crime and its official report?
* **Geographical Hotspots:** Which areas (AREA) in Los Angeles experience the highest density of specific crime types?
* **Victim Demographics:** How do crime types correlate with the age, descent, and gender of victims?

## 🛠️ Tech Stack

The analysis was performed using the standard Python data science ecosystem:
* **Pandas:** Data cleaning, feature engineering, and datetime manipulation.
* **Matplotlib & Seaborn:** Advanced data visualization and specialized themes.
* **NumPy:** Numerical operations and statistical summaries.

## 🚀 Key Analysis Steps

1. **Data Preprocessing:** Standardizing date formats and filtering data for the 2020-2024 timeframe.
2. **Feature Engineering:** Creating a `reported_after` column to measure reporting efficiency.
3. **Statistical Visualization:** Comparing crime categories across different districts using subplots.
4. **Insights Generation:** Identifying peak hours and common premises for criminal activity.

## 📂 Project Structure

* **LA Crime Stats Project.ipynb:** Main Jupyter Notebook with analysis and plots.
* **README.md:** Project documentation.

## 📋 How to Run

To explore the analysis locally:

1. **Clone the repository:** `git clone https://github.com/isasebib/LA-Crimes-Data-Analysis-Project.git`

2. **Install dependencies:** `pip install pandas matplotlib seaborn numpy`

3. **Run the Notebook:** Open `LA Crime Stats Project.ipynb` in Jupyter Notebook or VS Code and run the cells.

---
**Data Source:** [LA City Open Data Portal](https://data.lacity.org/) - Crime Data from 2020 to Present.
