# Zomato_Analysis

A Python-based data analysis project exploring restaurant data from Zomato, focusing on ratings, cuisines, locations, and cost trends in Bangalore.

## Description
This project analyzes a Zomato dataset (`zomato.csv`) containing details of restaurants in Bangalore, India. It performs data cleaning, exploratory data analysis (EDA), and visualizations to uncover insights about restaurant ratings, cuisines, locations, costs, and online ordering impacts. Key analyses include identifying top-rated cuisines, locations, restaurant types, and affordable high-rated options, with a focus on practical insights for food enthusiasts or business owners.

- **Purpose**: To demonstrate data wrangling, visualization, and analysis skills using Python, applied to real-world restaurant data.
- **Tech Stack**: Python, Pandas, NumPy, Seaborn, Matplotlib, Pandasql.
- **Dataset**: `zomato.csv` (sourced from Kaggle), with 51,717 entries and 17 features.
- **Status**: Complete as of March 2025, with results saved in a report and visualization.

## Features
- **Data Cleaning**: Handles missing values, converts ratings to numeric, and standardizes data formats.
- **Exploratory Data Analysis (EDA)**:
  - Top cuisines, locations, and restaurant types by average rating.
  - Impact of online ordering on ratings.
  - Correlation between cost and rating.
- **Visualizations**: Bar plot of top restaurant types by rating (saved as `top_rest_types.png`).
- **Specific Insights**:
  - Top 5 restaurants in Koramangala 5th Block.
  - High-rated (4.5+) and affordable (< ₹500) restaurants.
  - High-rated Italian restaurants.
- **Output**: Summary report saved as `zomato_analysis_report.md`.

## Dataset Overview
- **Source**: `zomato.csv` ([Kaggle: Zomato Bangalore Restaurants](https://www.kaggle.com/himanshupoddar/zomato-bangalore-restaurants)).
- **Columns**: 17, including `name`, `rate`, `cuisines`, `approx_cost(for two people)`, `location`, `rest_type`, `online_order`, etc.
- **Size**: 51,717 rows.
- **Key Features**:
  - `rate`: Rating out of 5 (e.g., "4.1/5" cleaned to 4.1).
  - `approx_cost(for two people)`: Cost in INR (numeric after cleaning).
  - `location`: Bangalore neighborhoods.

## Prerequisites
- Python 3.x
- Required libraries: `pandas`, `numpy`, `seaborn`, `matplotlib`, `pandasql`

## Output:
Visualization: Bar plot saved as top_rest_types.png.
Console Output: Top restaurants, affordable options, and Italian cuisine highlights.
Report: Summary saved as zomato_analysis_report.md.

