# currency_exchange_analysis
This repository contains Python code that retrieves and analyzes currency exchange rate data from the Frankfurter API using pandas and matplotlib.

### Code Overview
The main file, currency_exchange_analysis.py, performs the following tasks:

#### 1. Data Retrieval:
Utilizes the Frankfurter API to fetch currency exchange rate data within a specified date range.
#### 2. Data Processing:
Converts the API response into a pandas DataFrame and normalizes the rates column for further analysis.
Manipulates the DataFrame to prepare it for visualizations and analysis.
#### 3. Visualizations:
Plots the exchange rate of Euro (EUR) against US Dollar (USD) over time using a line plot.
Displays the distribution of exchange rates for Chinese Yuan (CNY) against EUR using a histogram.
Compares the average exchange rates of Great British Pound (GBP) and Japanese Yen (JPY) by year using a bar chart.
Analyzes the correlation between the exchange rates of Canadian Dollar (CAD) and US Dollar (USD) using a scatter plot.





### Note
Ensure that you have the necessary Python libraries (requests, pandas, matplotlib) installed to run the code (pip install requests pandas matplotlib).
Adjustments to date ranges, currencies, or visualization parameters can be made directly in the code for different analysis scenarios.