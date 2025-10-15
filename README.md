# Crypto-API-Project
This project collects and visualizes real-time cryptocurrency market data using the CoinGecko API, Python, MySQL, and Power BI.

CoinGecko Cryptocurrency Data Analytics Dashboard

📘 Overview

This project demonstrates a complete data analytics workflow that collects, processes, and visualizes real-time cryptocurrency market data using the CoinGecko API, Python, MySQL, and Power BI.

The goal of this project is to showcase technical skills in API integration, data transformation, SQL database management, and interactive dashboard design. It highlights how market data can be automated, structured, and visualized for decision-making and trend analysis.

⚙️ Technology

Python – API extraction, data processing (Pandas)

CoinGecko API – Real-time crypto market data

Power BI – Visualization and analytics

MySQL – Data storage and management

VS Code – Development environment

🧠 Workflow

Extract

Used Python and the CoinGecko API to collect live cryptocurrency market data. This was done with the packages requests, os, and pandas.

Transform

Used pandas to structure and clean the API data. Some timestamps and numeric fields required conversions for compatibility with MySQL.

Load

Used the package mysql.connector to insert processed data into my local MySQL database for persistence and future querying.

Visualize

Connected Power BI to MySQL and created interactive visuals:

Top 10 gainers and losers (24h)

Market cap and trading volume distribution

24-hour percentage change comparisons

📊 Dashboard Preview

<img width="1518" height="843" alt="image" src="https://github.com/user-attachments/assets/b3e808f5-d5c9-4c31-b2bb-8ae7460d9680" />


