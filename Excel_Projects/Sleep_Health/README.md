# Sleep and Lifestyle Analysis

An Excel-based data analysis project exploring relationships between occupation, BMI, sleep quality, stress levels, and physical activity using a health dataset.

## Description
This project analyzes a health and lifestyle dataset in Microsoft Excel, focusing on metrics like sleep duration, quality of sleep, stress levels, physical activity, daily steps, BMI category, and occupation. Using Excel’s pivot tables and data tools, it uncovers patterns such as how BMI and occupation influence sleep quality and stress, with breakdowns by gender and profession.

- **Purpose**: To demonstrate data summarization and analysis skills in Excel, providing insights into health and lifestyle trends.
- **Tech Stack**: Microsoft Excel (pivot tables, data filtering).
- **Dataset**: `sleep_lifestyle_data.csv` (imported into Excel), with 374 entries and 13 features.
- **Status**: Completed with summarized results as of March 2025.

## Features
- **Data Summarization**:
  - Pivot tables by gender: Stress levels, sleep quality, physical activity, and daily steps.
  - Pivot tables by occupation and BMI: Person IDs and sleep quality totals.
- **Key Metrics Analyzed**:
  - Sleep Quality (1-10 scale)
  - Stress Level (1-10 scale)
  - Physical Activity Level (arbitrary units)
  - Daily Steps (count)
  - BMI Categories: Normal, Overweight, Obese
- **Outputs**:
  - Excel pivot tables summarizing metrics.
  - Raw data sample for 374 individuals.

## Dataset Overview
- **Source**: `sleep_lifestyle_data.csv` (from Kaggle, e.g., [Sleep Health and Lifestyle Dataset](https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset)), imported into Excel.
- **Columns**: 13, including:
  - `Person ID`: Unique identifier.
  - `Gender`: Male/Female.
  - `Age`: Age in years.
  - `Occupation`: Job type (e.g., Doctor, Engineer, Nurse).
  - `Sleep Duration`: Hours slept.
  - `Quality of Sleep`: Rating (1-10).
  - `Physical Activity Level`: Activity score.
  - `Stress Level`: Rating (1-10).
  - `BMI Category`: Normal, Overweight, Obese.
  - `Blood Pressure`: Systolic/Diastolic (mmHg).
  - `Heart Rate`: Beats per minute.
  - `Daily Steps`: Steps taken daily.
  - `Sleep Disorder`: None, Sleep Apnea, Insomnia.
- **Size**: 374 rows.

## Prerequisites
- **Microsoft Excel**: Version supporting pivot tables (e.g., Excel 2016 or later, Microsoft 365 recommended).

## Dataset:
- Download sleep_lifestyle_data.csv (not included; reconstruct from raw data if needed).
- Open Excel and import the CSV:
- Go to Data > Get Data > From Text/CSV (or File > Open in older versions).
- Load sleep_lifestyle_data.csv.

### Open the Workbook:
- Launch sleep_lifestyle_analysis.xlsx in Excel (or your recreated file).
- Explore Pivot Tables:
        Sheet 1 (Gender Summary): View sums of stress level, sleep quality, physical activity, and daily steps by gender.
        Sheet 2 (Occupation & BMI): Check Person ID and sleep quality totals by occupation and BMI category.
- Adjust filters or fields in the pivot tables to explore further.
- Raw Data:
        Refer to the "Data" sheet (or equivalent) for the full 374-row dataset.
