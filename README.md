# 🏏 IPL 2025 Team & Performance Analysis

A data analysis project exploring the franchises and team statistics for the Indian Premier League (IPL) 2025 season. This repository contains structured datasets detailing franchise information alongside team performance summaries.

## 📊 Dataset Overview

This project includes data on all IPL franchises, structured for easy analysis and visualization. 

**Key Data Points Included:**
* **Franchise Details:** Team names, unique Team IDs, and ownership information.
* **Leadership & Coaching:** Current captains (e.g., Rohit Sharma, Ruturaj Gaikwad) and head coaches.
* **Venues:** Dedicated home grounds and base cities for each team.
* **Performance Summaries:** Aggregated statistics including total matches, total wins, total runs, and total wickets.

## 📁 File Structure

* `IPL 2025.xlsx - dim_team.csv`: A dimensional table containing core information for each IPL franchise (Captains, Coaches, Venues, Owners).
* `Project1.xlsx - Team Summary.csv`: An aggregated summary table tracking matches played, total wins, run aggregates, and wickets.
* `IPL 2025.xlsx` & `Project1.xlsx`: The original Excel workbooks containing raw data and formatted sheets.

## 🚀 Usage & Access

### Viewing the Data
For the best interactive experience and to view the formatted dashboards/pivot tables, view the live Google Sheets here:
* https://docs.google.com/spreadsheets/d/1Xo82NE7DYpXovfnyUhITvOoIejriOery/edit?usp=sharing&ouid=103595026846684469892&rtpof=true&sd=true
* https://docs.google.com/spreadsheets/d/1GQU06VjeuvkzE_Bd_CEc0DfTKo89H3xG/edit?usp=sharing&ouid=103595026846684469892&rtpof=true&sd=true

### Using the Data for Analysis (Python/Pandas)
If you want to use this data for your own machine learning or visualization projects, you can easily load the CSV files using pandas:

```python
import pandas as pd

# Load team details
teams_df = pd.read_csv('IPL 2025.xlsx - dim_team.csv')
print(teams_df.head())

# Load performance summaries
summary_df = pd.read_csv('Project1.xlsx - Team Summary.csv')
