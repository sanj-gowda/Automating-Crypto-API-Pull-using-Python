# Cryptocurrency Data Fetching and Analysis

This project sets up an API connection to CoinMarketCap to fetch the latest cryptocurrency listings, store the data in a CSV file, and perform basic data analysis. The project automates the process of data collection and provides a framework for analyzing cryptocurrency trends over different time periods.

## Features

- **API Integration**: Fetches real-time cryptocurrency data from the CoinMarketCap API.
- **Data Collection**: Automatically stores data in a CSV file for long-term analysis.
- **Data Analysis**: Calculates and analyzes average percentage changes over various time periods (1 hour, 24 hours, 7 days, etc.).
- **Automated Fetching**: Schedules recurring API requests at fixed intervals.

## Files

- `API_SetUp.ipynb`: Jupyter notebook that sets up the API, collects data, and performs analysis.
- `APIs.csv`: CSV file where the fetched data is stored.

## How It Works

- The API is called at regular intervals to gather cryptocurrency data.
- Data is stored in a CSV file for ongoing collection and analysis.
- The project includes basic pandas operations to analyze average percentage changes over different time frames.
