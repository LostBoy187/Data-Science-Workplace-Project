# Data Science Workplace Project: Vegetable Price Analysis and Forecasting

This repository contains the work for the Data Science Workplace Project, focusing on the analysis and forecasting of vegetable prices.

## Project Overview

The goal of this project is to analyze a dataset of daily vegetable prices to identify trends, patterns, and volatility. A predictive model is then developed to forecast future prices for a selected vegetable (onion), providing a practical tool for business decision-making, such as inventory management and pricing strategies.

The project follows a standard data science lifecycle, encompassing:

* **Data Cleaning and Preprocessing:** Preparing the raw data for analysis.
* **Exploratory Data Analysis (EDA):** Visualizing the data to uncover insights.
* **Feature Engineering:** Creating new variables to improve model performance.
* **Modeling:** Building and evaluating both a baseline and a predictive model.
* **Conclusion:** Summarizing findings and suggesting future improvements.

## Repository Contents

* `QCTO---Workplace-Module-Notebook-Template-4571.ipynb`: The main Jupyter Notebook containing all the Python code, analysis, and findings.
* `prices.csv`: The raw dataset containing daily prices for various vegetables.
* `Data Visualisation and Reporting Processes.pbix`: Power BI dashboard visualizing price trends and key insights.
* `WP_Part1_01_-_Workplace-Introduction.pdf`: The project brief and requirements document.
* `README.md`: This file, summarizing the project.

## Key Findings

* **Exploratory Analysis:** **Garlic** was identified as the most expensive and volatile item, while **Tomato** prices were found to be suspiciously stable. A significant data outlier (a max price of 2000) was also noted in the **Methi** data. **Onion** was ultimately selected as the best candidate for forecasting.
* **Model Performance:** A Linear Regression model, using engineered features like price lags and rolling averages, was trained to predict the price of onions. It successfully outperformed a naive baseline forecast, achieving an **RMSE of 4.06** compared to the baseline's RMSE of 4.37.

## Dashboard & Reporting

A Power BI report (`Data Visualisation and Reporting Processes.pbix`) is included in this repository. This dashboard provides an interactive view of the data, allowing stakeholders to:
* Filter price trends by vegetable type.
* View the distribution of prices visually.
* Compare volatility across different items (e.g., Garlic vs. Tomato).

## How to Run

1.  Clone this repository to your local machine.
2.  Ensure you have Python and the following libraries installed:
    * `pandas`
    * `numpy`
    * `matplotlib`
    * `seaborn`
    * `scikit-learn`
3.  Open the `QCTO---Workplace-Module-Notebook-Template-4571.ipynb` file in a Jupyter environment (like Jupyter Lab or VS Code).
4.  Run the cells sequentially to reproduce the analysis and results.

## Project Management

The workflow for this project was managed using Trello. The board tracked the progress from data collection to final reporting.

* **Trello Board:** (https://trello.com/b/2hrFJnjJ/my-trello-board)