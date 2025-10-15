# Crypto API ETL Pipeline Project
This project develops an end-to-end data pipelione to collect and visualizes real-time cryptocurrency market data using the CoinGecko API, Python, MySQL, and Power BI.

## Overview

This project demonstrates a complete data analytics workflow that collects, processes, and visualizes real-time cryptocurrency market data using the CoinGecko API, Python, MySQL, and Power BI.

The goal of this project is to showcase technical skills in API integration, data transformation, SQL database management, and interactive dashboard design. It highlights how market data can be automated, structured, and visualized for decision-making and trend analysis.

## Technology

Python – API extraction, data processing (Pandas)

CoinGecko API – Real-time crypto market data

Power BI – Visualization and analytics

MySQL – Data storage and management

VS Code – Development environment

# ETL Workflow

## Extract

Used Python and the CoinGecko API to collect live cryptocurrency market data. This was done with the packages requests, os, and pandas.

## Transform

Used pandas to structure and clean the API data. Some timestamps and numeric fields required conversions for compatibility with MySQL.

## Load

Used the mysql.connector package to insert processed data into my local MySQL database for persistence and future querying.

## Visualize

Power BI was connected to MySQL to load data from python.

Allows users to slice between 1000 cryptocurrencies and view the symbol, logo, price, volume, price change in the past day, all-time-low, and all-time-high data.

Graphs show the top 10 cryptocurrency rise and loss in terms of percentage in the past 24 hours. The graphs are limited to the top 100 largest coins by market cap to avoid distortion from smaller volume coins with large percentage changes.

## Power BI Report:

<img width="1324" height="765" alt="image" src="https://github.com/user-attachments/assets/760b5454-33a6-43a7-a09c-fba992988792" />

This report can be viewed and interacted with [Here.](https://app.powerbi.com/view?r=eyJrIjoiZTNmZmJiM2ItOTIyNS00NTlmLTk0MmUtNzRmMDQ2MzUxZjdhIiwidCI6IjYyMDRjNjEwLTZmYjUtNGQwNi04YzA0LWEyMWJkMDFmMmU0NSIsImMiOjF9)
