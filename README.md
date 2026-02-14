# City Planning Analysis: Weather, Activity, and Resource Usage

## Project Overview
This project analyzes the interaction between daily climate conditions, human physical activity, and urban resource consumption (electricity). It utilizes a multi-source dataset to provide data-driven insights for infrastructure and policy decisions.

## Datasets
- **Climate Data**: Temperature, humidity, and weather conditions (Delhi, India).
- **Fitness Data**: Steps, calories burned, distance, and BPM.
- **Synthetic Data**: Departmental salaries (Sales, IT, HR, Marketing), media consumption hours (Drama, Comedy, etc.), and electricity usage (kWh).

## Key Features
- **Data Merging**: Integration of disparate sources by Date and Location.
- **Quality Assessment**: Validation of completeness, accuracy, and uniqueness (deduplication).
- **Visual Analytics**:
  - Time-series analysis of Temperature vs. Electricity usage.
  - Activity vs. Health correlation (Steps vs. BPM).
  - Distribution analysis of departmental salaries.
  - Content consumption ranking and percentage contribution.

## Core Insights
1. **Energy Demand**: Positive correlation between higher temperatures and electricity consumption.
2. **Media Trends**: Drama and Comedy dominate viewing habits, accounting for ~54% of total hours.
3. **Economic Distribution**: IT and Sales departments show significantly higher salary medians and ranges compared to HR and Marketing.

## Technologies Used
- **Python** (Pandas, NumPy)
- **Plotly / Plotly Express** (Interactive Visualizations)
- **Matplotlib**
