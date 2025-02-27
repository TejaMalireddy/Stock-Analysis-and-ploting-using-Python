# Stock Analysis and Plotting using Python

## Project Overview
This stock analysis tool is built using Django and Django REST Framework (DRF). It fetches historical stock index data from the past 10 years with a 1-day time frame. The project utilizes data visualization techniques with Matplotlib to analyze stock trends. Stock data is retrieved from Yahoo Finance using the `yfinance` library. The tool processes the data to identify key market patterns such as peaks, valleys, support, and resistance levels and provides REST API endpoints for data retrieval.

## Technologies Used
1. **Django** – Backend framework for API development.
2. **Django REST Framework (DRF)** – Implements REST API endpoints.
3. **Yfinance** – Fetches historical stock/index data from Yahoo Finance.
4. **Pandas** – Used for data processing and analysis.
5. **Matplotlib** – Facilitates stock price trend visualization, including peaks and support/resistance levels.
6. **Scipy** – Detects peaks and valleys in stock price trends.

## Features
1. Fetches 10 years of historical stock/index data using `yfinance`.
2. Identifies peaks and valleys in stock prices using scientific computing techniques.
3. Determines support and resistance levels for market trend analysis.
4. Provides REST API endpoints to serve processed stock data for further analysis and visualization.
5. 5.Visualizes stock trends with Matplotlib plots.

This tool enables users to analyze stock trends effectively and make informed decisions based on historical data insights.







