# Data Science Workplace Project: Vegetable Price Analysis and Forecasting

This repository contains the work for the Data Science Workplace Project, focusing on the analysis and forecasting of vegetable prices.

## Project Overview

The goal of this project is to analyze a dataset of daily vegetable prices to identify trends, patterns, and volatility. A predictive model is then developed to forecast future prices for a selected vegetable (`onion`), providing a practical tool for business decision-making, such as inventory management and pricing strategies.

The project follows a standard data science lifecycle, encompassing:
1.  **Data Cleaning and Preprocessing:** Preparing the raw data for analysis.
2.  **Exploratory Data Analysis (EDA):** Visualizing the data to uncover insights.
3.  **Feature Engineering:** Creating new variables to improve model performance.
4.  **Modeling:** Building and evaluating both a baseline and a predictive model.
5.  **Conclusion:** Summarizing findings and suggesting future improvements.

## Repository Contents

*   `QCTO-Workplace-Module-Notebook-Template-4571.ipynb`: The main Jupyter Notebook containing all the Python code, analysis, and findings.
*   `prices.csv`: The raw dataset containing daily prices for various vegetables.
*   `WP_Part1_01_-_Workplace-Introduction.pdf`: The project brief and requirements document.

## Key Findings

*   **Exploratory Analysis:** The vegetable `onion` was identified as having significant price volatility, making it an ideal candidate for forecasting. Other items, like `tomato`, were found to be exceptionally stable.
*   **Model Performance:** A Linear Regression model was trained to predict the price of onions. It successfully outperformed a naive baseline forecast, achieving a lower Root Mean Squared Error (RMSE), which indicates better predictive accuracy.

## How to Run

1.  Clone this repository to your local machine.
2.  Ensure you have Python and the following libraries installed:
    *   `pandas`
    *   `numpy`
    *   `matplotlib`
    *   `seaborn`
    *   `scikit-learn`
3.  Open the `QCTO-Workplace-Module-Notebook-Template-4571.ipynb` file in a Jupyter environment (like Jupyter Lab or VS Code).
4.  Run the cells sequentially to reproduce the analysis and results.
