# 🎶 Grammys Web Analytics Project

Welcome to the **Grammys Web Analytics Project**, developed as part of a data analysis exercise using real-world data from **The Recording Academy**, the organization behind the prestigious **Grammy Awards**.

![Grammys Logo](https://www.moviedebuts.com/wp-content/uploads/2021/05/ra_ga_logo.png)

## 📌 Project Overview

This project explores the impact of The Recording Academy's decision to split its digital presence between two websites:
- **grammy.com**
- **recordingacademy.com**

You’ll dive into web analytics data to analyze user behavior, compare trends, and evaluate engagement metrics across both sites — especially around key marketing events such as **Awards Week** and **Awards Night**.

---

## 📂 Datasets Used

The analysis is based on two CSV files:
- `grammys_live_web_analytics.csv`
- `ra_live_web_analytics.csv`

### Data Dictionary
- `date`: Date of data recording (`YYYY-MM-DD`)
- `visitors`: Number of unique visitors
- `pageviews`: Total number of page views
- `sessions`: Total website sessions
- `bounced_sessions`: Number of sessions where users exited without interaction
- `avg_session_duration_secs`: Average session duration (in seconds)
- `awards_week`: Binary flag indicating if the date is during Awards Week
- `awards_night`: Binary flag indicating if the date is Awards Night

---

## 📊 Project Structure

The notebook includes:
- Exploratory Data Analysis (EDA)
- Trend Analysis & Data Visualization
- Metrics Comparison between the two sites
- Event Impact Assessment (Awards Week/Night)

---

## 🛠 Tools & Technologies

- **Python**
- **Pandas** for data manipulation
- **NumPy** for numerical operations
- **Plotly Express** for interactive visualizations

---

## ▶️ Getting Started

1. Clone this repository or download the `.ipynb` file.
2. Install dependencies:
   ```bash
   pip install pandas numpy plotly
