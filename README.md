# Comprehensive Analysis of EUR/USD Hourly Data

## Description

This repository contains a comprehensive analysis of hourly EUR/USD exchange rate data. The dataset includes various financial indicators for bid and ask prices, spanning several years. The goal is to explore the data, visualize trends, and apply statistical and machine learning techniques to uncover insights.

## Repository Contents

- **Data Loading and Preprocessing**
  - Load the dataset
  - Convert date and time columns to a single datetime column
  - Set the datetime column as the index
  - Drop unnecessary columns

- **Basic Descriptive Analysis**
  - Display summary statistics for the dataset
  - Visualize trends in bid and ask closing prices over time

- **Percentage Change Analysis**
  - Calculate and plot the daily percentage change in bid and ask closing prices

- **Moving Average Analysis**
  - Compute and visualize 24-hour moving averages for bid and ask closing prices

- **Correlation Analysis**
  - Calculate and display the correlation between bid and ask closing prices

- **Distribution Analysis**
  - Plot the distributions of bid and ask closing prices using histograms and KDE

- **Bollinger Bands Analysis**
  - Calculate and plot Bollinger Bands for bid closing prices

- **Volume Analysis (if applicable)**
  - Visualize trading volumes over time (if volume data is available)

- **Pattern Identification with Machine Learning**
  - Apply K-means clustering to identify patterns in the bid and ask closing prices


## Notebooks and Scripts

- `Euro-Usd.ipynb`: Jupyter notebook containing step-by-step data analysis and visualizations

## Dataset

The dataset `eurusd_hour.csv` should be placed in the root directory. It includes the following columns:

- `Date`: Date of the data point
- `Time`: Time of the data point
- `BO`, `BH`, `BL`, `BC`, `BCh`: Bid open, high, low, close prices, and bid change
- `AO`, `AH`, `AL`, `AC`, `ACh`: Ask open, high, low, close prices, and ask change

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Contributions

Contributions are welcome! Feel free to open issues or submit pull requests.

## Acknowledgements

This analysis was made possible by using various Python libraries including Pandas, Matplotlib, Seaborn, and Scikit-learn.
