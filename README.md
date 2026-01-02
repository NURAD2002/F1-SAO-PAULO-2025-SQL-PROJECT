# 🏎️ F1 2025 Season — SQL Data Analysis

This project presents a SQL-based analysis of the **Formula 1**, designed to showcase practical data analytics and SQL skills using a realistic sports dataset.

The goal of the project is to simulate how SQL can be used to analyze race performance, compare teams, evaluate pit stop strategy, and extract meaningful insights from structured data.

---

## 📌 Project Overview

The dataset represents final race results for the São Paulo Grand Prix, including:
- Driver finishing positions
- Teams
- Total race times
- Pit stop counts
- Non-finishers (DNFs)

All data was manually created to mirror a real-world motorsport scenario and to enable analytical querying rather than simple data entry.

---

## 🗂️ Project Structure

f1-season-sql/
│
├── README.md
│
├── schema/
│   ├── drivers.sql
│   ├── teams.sql
│   ├── races.sql
│   ├── circuits.sql
│   ├── results.sql
│   ├── lap_times.sql
│   ├── pit_stops.sql
│   └── standings.sql
│
├── data/
│   ├── drivers.csv
│   ├── teams.csv
│   ├── races.csv
│   ├── results.csv
│   ├── lap_times.csv
│   └── pit_stops.csv
│
├── inserts/
│   ├── insert_drivers.sql
│   ├── insert_teams.sql
│   ├── insert_races.sql
│   ├── insert_results.sql
│   ├── insert_lap_times.sql
│   └── insert_pit_stops.sql
│
├── queries/
│   ├── race_results.sql
│   ├── driver_standings.sql
│   ├── team_standings.sql
│   ├── fastest_laps.sql
│   ├── pit_stop_counts.sql
│   ├── average_lap_times.sql
│   └── consistency_analysis.sql
│
├── views/
│   ├── v_race_results.sql
│   ├── v_driver_standings.sql
│   └── v_team_standings.sql
│
└── docs/
    ├── data_dictionary.md
    ├── assumptions.md
    └── known_issues.md


---

## 🛠️ SQL Skills Demonstrated

This project demonstrates the following SQL concepts:

- Database schema design (`CREATE TABLE`)
- Data insertion and updates (`INSERT`, `UPDATE`)
- Schema evolution (`ALTER TABLE`)
- Aggregation and grouping (`GROUP BY`, `AVG`, `COUNT`)
- Window functions for analytical calculations
- Derived metrics and safe division using `NULLIF`
- Filtering and ordering for insight generation

---

## 📊 Key Analyses

### 🔹 Team Performance Summary
- Average race time by team
- Average number of pit stops per team
- Team-level comparisons using aggregated metrics

### 🔹 Time Gap Analysis
- Time difference between each driver and the race winner
- Calculated using SQL window functions

### 🔹 Pit Stop Efficiency
- Evaluation of race time relative to pit stop count
- Identification of potential strategy advantages

### 🔹 DNFs (Did Not Finish)
- Identification of drivers who did not complete the race
- Separate handling to avoid skewing performance metrics

---

## 🚀 How to Use This Project

1. Run the SQL script in `data/f1_results.sql` to create and populate the table.
2. Execute any of the queries in the `queries/` folder to explore the analysis.
3. (Optional) Connect the dataset to Power BI or another BI tool for visualization.

---

## 📈 Optional Visualization

This dataset and its queries are compatible with **Power BI** and other BI tools, enabling:
- Team performance bar charts
- Time gap visualizations
- Pit stop vs race time comparisons
- Summary KPI dashboards

---

## 🎯 Purpose

This project is intended as a **portfolio example** to demonstrate how SQL can be used to analyze real-world scenarios, apply analytical thinking, and communicate insights clearly.

---

## 📬 Contact

If you have questions about this project or suggestions for improvement, feel free to reach out.

