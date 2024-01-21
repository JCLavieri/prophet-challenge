# prophet-challenge
# MercadoLibre Search Traffic Analysis

## Project Overview
This project involves analyzing the search traffic data for [MercadoLibre](http://investor.mercadolibre.com/about-us), the most popular e-commerce site in Latin America. The goal is to uncover insights into the company's search traffic patterns and correlate these patterns with stock price movements. This analysis could reveal if search traffic data can be used to predict stock market performance.

## Steps in the Analysis
The analysis is divided into four key steps:

1. **Unusual Patterns in Hourly Google Search Traffic**
2. **Seasonality in Search Traffic Data**
3. **Correlation Between Search Traffic and Stock Price**
4. **Time Series Forecasting with Prophet**

### 1. Unusual Patterns in Hourly Google Search Traffic
We analyzed the hourly Google search data for MercadoLibre, focusing on identifying any unusual search patterns, particularly in May 2020, when the company released its quarterly financial results.

**Findings:**
- A noticeable increase in search traffic was observed during this period, suggesting heightened public interest possibly linked to the financial results release.

### 2. Seasonality in Search Traffic Data
This step involved mining the search traffic data to uncover predictable seasonal patterns, analyzing traffic by the hour of the day, day of the week, and week of the year.

**Key Observations:**
- Peak times during the day.
- Busiest days of the week.
- Seasonal variations throughout the year.

### 3. Correlation Between Search Traffic and Stock Price
We examined the relationship between search traffic data and MercadoLibre's stock price, especially during the first half of 2020.

**Analysis Results:**
- A limited but notable correlation between search activity and stock price movements.
- Specific trends around significant corporate events, like earnings releases.

### 4. Time Series Forecasting with Prophet
Using the Prophet library, we created a time series model to forecast future search traffic trends.

**Forecast Insights:**
- Predicted peaks and troughs in search traffic.
- Daily and weekly patterns.
- Seasonal fluctuations across the year.

## Technologies Used
- Python
- Pandas
- Prophet for time series analysis
- Matplotlib for data visualization

## Data Sources
- MercadoLibre Google hourly search trends data.
- MercadoLibre stock price data.

## How to Run the Project
Provide instructions on how to set up and run the analysis, including installing required libraries, setting up the environment, and executing the scripts.


## Acknowledgments
- MercadoLibre for providing the data.


