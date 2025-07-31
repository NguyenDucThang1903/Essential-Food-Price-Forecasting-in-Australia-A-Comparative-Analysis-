Winter Research Project: Tracking Inflation Trends in Australian Retail through Data Analytics

## Overview
This repository contains the data, code, and documentation for a winter research project conducted with Andrey Pototskyy focused on analyzing inflation trends in the Australian retail sector through data analytics techniques.

## Project Structure
- `neuro_prophet.R`: Time series forecasting using the Prophet algorithm adapted for neural networks
- `t.R`: Time series analysis script
- `dataset/`: Directory containing all datasets used in the research
  - `Australia_Grocery_2022Sep.csv.zip`: Australian grocery price data
  - `dataaus.csv.zip`: Australian economic indicators
  - `retail_sales_dataset.csv`: Retail sales information
  - `Table 3_ Prices - 1973 and 2023 (a).csv`: Historical price comparison
  - `supermarkets-inquiry_1.pdf`: Government inquiry report on supermarkets
- `Essential-retail-item-forecast/`: Models and code for forecasting essential retail items
- `gov_data_submission/`: Data prepared for government submission

## Research Documents
- `Winter_research_project_report.pdf`: Final research report
- `Tracking Inflation Trends in Australian Retail through Data Analytics.pdf`: Research paper
- `Pierce-R2MeasuresTime-1979.pdf`: Reference paper on R² measures for time series

## Getting Started

### Prerequisites
- R (version 4.0 or higher)
- Required R packages: prophet, dplyr, ggplot2, tidyr (specific versions in requirements file)

### Data Preparation
1. Unzip the dataset files in the `dataset/` directory
2. Run data preprocessing scripts (detailed in the report)

### Running Analysis
1. Execute `neuro_prophet.R` for time series forecasting
2. Use `t.R` for additional time series analysis

## Results
Key findings and visualizations are available in the research report. The analysis demonstrates patterns in Australian retail inflation over time and forecasts future trends based on historical data.

## Authors
- [Your Name]
- Andrey Pototskyy

## Acknowledgments
- Data sources: Australian Bureau of Statistics, government retail datasets
- Research supported by [University/Institution name]
