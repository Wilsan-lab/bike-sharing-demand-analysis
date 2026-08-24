# 🚲 Bike Sharing Demand Analysis

## 📌 Project Overview

This project analyzes bike-sharing demand using the Bike Sharing dataset.

The main goal is to understand how different factors such as time, weather, season, temperature, and working days affect the number of bike rentals.

The project focuses on Exploratory Data Analysis (EDA) to identify important patterns and trends in bike-sharing demand.

## 🎯 Objectives

- Analyze bike rental demand over time.
- Explore rental demand by hour of the day.
- Analyze the relationship between weather conditions and bike rentals.
- Compare bike rental demand across different seasons.
- Investigate the relationship between temperature and rental demand.
- Compare demand on working days and non-working days.
- Identify the main patterns that influence bike-sharing demand.

## 📊 Dataset Overview

The dataset contains approximately 10,890 hourly observations of bike-sharing activity.

Key variables include:

- `datetime` – Date and time of the observation
- `season` – Season of the year
- `holiday` – Whether the day is a holiday
- `workingday` – Whether the day is a working day
- `weather` – Weather condition
- `temp` – Temperature
- `atemp` – Feeling temperature
- `humidity` – Humidity level
- `windspeed` – Wind speed
- `count` – Total number of bike rentals

## 🔍 Exploratory Data Analysis

The analysis investigates several important relationships:

### 1. Rental Demand Over Time

Bike rental demand generally increases over time, with higher and more variable rental levels in the later part of the dataset.

### 2. Demand by Hour

Rental demand varies significantly throughout the day.

The analysis shows higher demand during morning and evening commuting hours, while demand is generally lower during the night and early morning.

### 3. Demand by Season

Rental demand differs across seasons.

**Season 3 (Fall)** has the highest average rental demand, while **Season 1 (Spring)** has the lowest.

### 4. Demand by Weather

Weather conditions have a strong effect on bike rental demand.

Clear weather has the highest rental demand, while heavier rain and storm conditions are associated with much lower demand.

### 5. Temperature vs. Rental Demand

The analysis shows a generally positive relationship between temperature and bike rental demand.

As temperature increases, rental demand generally increases, although the relationship is not perfectly linear.

### 6. Working Day vs. Non-Working Day

Average rental demand is slightly higher on working days than on non-working days, suggesting that working-day status has a relatively small effect on overall demand.

## 📌 Key Findings

- Bike rental demand changes significantly throughout the day.
- Morning and evening commuting hours show strong rental activity.
- Fall (Season 3) has the highest average rental demand.
- Spring (Season 1) has the lowest average rental demand.
- Clear weather conditions are associated with higher rental demand.
- Rainy and stormy weather significantly reduces bike rentals.
- Temperature generally has a positive relationship with rental demand.
- Working days have only a small effect on overall average demand.

## 🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- Google Colab

## 📁 Project Structure

```text
bike-sharing-demand-analysis/
│
├── bike_sharing_demand_analysis.ipynb
├── train.csv
├── README.md
├── LICENSE
└── .gitignore
