# 📊 Cryptocurrency Data Analysis

## 📌 Project Overview

This project focuses on analyzing cryptocurrency market data using Python.

The dataset contains information about 4,150 cryptocurrencies, including price, percentage changes, trading volume, circulating supply, total supply, and market capitalization.

The project follows a complete data analysis workflow covering data loading, data cleaning, preprocessing, missing-value treatment, statistical analysis, exploratory data analysis, and data visualization.

---

## 🎯 Objectives

The main objectives of this project are:

- Understand the structure of cryptocurrency market data.
- Perform data cleaning and preprocessing.
- Identify and handle missing values.
- Convert data into appropriate numerical formats.
- Perform statistical analysis.
- Analyze cryptocurrency prices and market capitalization.
- Compare short-term and medium-term price changes.
- Explore relationships between cryptocurrency market features.
- Create meaningful visualizations.
- Extract useful insights from the dataset.

---

## 📊 Dataset

The dataset contains information about **4,150 cryptocurrencies** with **12 features**.

### Dataset Features

| Feature | Description |
|---|---|
| `Rank` | Cryptocurrency market ranking |
| `Coin Name` | Name of the cryptocurrency |
| `Symbol` | Cryptocurrency ticker symbol |
| `Price` | Current cryptocurrency price |
| `1h` | Percentage price change in the last 1 hour |
| `24h` | Percentage price change in the last 24 hours |
| `7d` | Percentage price change in the last 7 days |
| `30d` | Percentage price change in the last 30 days |
| `24h Volume` | Trading volume during the last 24 hours |
| `Circulating Supply` | Number of coins currently circulating |
| `Total Supply` | Total number of coins available |
| `Market Cap` | Total market capitalization |

---

## 🔍 Exploratory Data Analysis

The project performs exploratory analysis to understand cryptocurrency market characteristics.

The analysis includes:

- Dataset shape and structure
- Data types
- Descriptive statistics
- Unique values
- Missing-value analysis
- Distribution analysis
- Price analysis
- Market capitalization analysis
- Trading volume analysis
- Cryptocurrency ranking analysis
- Percentage-change analysis
- Correlation analysis

---

## 🧹 Data Cleaning and Preprocessing

Several data preprocessing techniques are applied to prepare the dataset for analysis.

### Missing Values

Missing values are identified and treated using appropriate techniques depending on the feature.

For example:

- Price values are estimated using available market-cap and circulating-supply information.
- Market-cap values are calculated using price and circulating supply where appropriate.
- Missing percentage-change values are replaced with `0`.
- Missing trading-volume values are handled using the median.

---

## 🔄 Data Type Conversion

Several columns contain values stored as strings because of:

- `$` symbols
- `%` symbols
- commas
- textual units such as Million and Billion

These values are cleaned and converted into appropriate numerical formats for analysis.

---

## 📈 Data Analysis

The project analyzes different aspects of the cryptocurrency market.

### Price Analysis

Cryptocurrency prices are analyzed to identify price distributions and differences between cryptocurrencies.

### Market Capitalization

Market capitalization is analyzed to understand the relative size of different cryptocurrencies.

### Trading Volume

24-hour trading volume is analyzed to understand market activity and liquidity.

### Percentage Change

Price changes across:

- 1 hour
- 24 hours
- 7 days
- 30 days

are analyzed to understand short-term and medium-term market movements.

---

## 📊 Data Visualization

The project uses Python visualization libraries to generate meaningful charts.

Visualizations include:

- Bar charts
- Histograms
- Distribution plots
- Box plots
- Scatter plots
- Correlation heatmaps
- Comparative charts

These visualizations help identify patterns, trends, relationships, and outliers within the cryptocurrency market.

---

## 📐 Statistical Analysis

Statistical techniques are used to understand the numerical characteristics of the dataset.

The project analyzes:

- Mean
- Median
- Standard deviation
- Minimum and maximum values
- Quartiles
- Correlations
- Feature relationships

---

## 🛠️ Technologies Used

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn

### Development Environment

- Google Colab
- Jupyter Notebook

---

## 📁 Project Structure

```text
Crypto-data-analysis/
│
├── Crypto_analysis_project.ipynb
├── CryptocurrencyData.csv
└── README.md
