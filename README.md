# Stock Price Exploratory Data Analysis (EDA)
Performed exploratory data analysis on stock price data, including data cleaning, summary statistics, correlation analysis, and visualization using histograms, boxplots, and scatter plots to identify trends, patterns, and relationships.

## Project Overview
This project performs Exploratory Data Analysis (EDA) on a stock price dataset to understand the structure of the data, identify patterns, detect outliers, and analyze relationships between variables such as Open, High, Low, Close, and Volume.

## Objectives
- Clean and prepare the dataset
- Perform exploratory data analysis
- Calculate summary statistics
- Visualize data distributions
- Analyze relationships between variables
- Identify trends and patterns in stock prices

## Tools and Libraries Used
- Python
- Pandas
- Matplotlib
- Seaborn

## Dataset Description
The dataset contains historical stock price data with the following variables:
- Symbol - company name
- Date – Trading date
- Open – Opening price
- High – Highest price of the day
- Low – Lowest price of the day
- Close – Closing price
- Volume – Number of shares traded

Each row represents stock market data for a specific day.

## Steps Performed
1. Imported necessary libraries
2. Loaded the dataset using Pandas
3. Checked dataset structure using .info() and .describe()
4. Checked for missing values and duplicates
5. Cleaned and prepared the dataset
6. Performed summary statistics (mean, median, standard deviation)
7. Created histograms to analyze data distribution
8. Created boxplots to detect outliers
9. Created scatter plots to analyze relationships between variables
10. Performed correlation analysis between numerical variables

## Key Insights
- Stock prices showed an overall upward trend over time.
- The Close price is highly correlated with Open, High, and Low prices.
- Volume showed higher variability compared to price variables.
- Some outliers were observed in the Volume variable.
- Price variables showed similar distribution patterns.

## Conclusion
Exploratory Data Analysis helped in understanding the dataset, identifying relationships between variables, detecting outliers, and preparing the data for further analysis such as time series analysis.

## Author
Elijah Timi Elliot
