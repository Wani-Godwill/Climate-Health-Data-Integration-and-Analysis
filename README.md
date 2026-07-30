# Data Management: Climate–Health Data Integration and Analysis

## Overview

This project investigates the relationship between **air pollution, weather conditions, and health outcomes** across European countries. It integrates environmental and health datasets, performs data cleaning and enrichment, stores the integrated data in PostgreSQL, and applies exploratory and statistical analyses to generate insights for public health policy. :contentReference[oaicite:0]{index=0}

## Objectives

- Integrate weather, air quality, and health datasets.
- Assess and improve data quality.
- Store the integrated data in PostgreSQL.
- Perform exploratory data analysis (EDA) and correlation analysis.
- Visualize pollution trends and health impacts across Europe.
- Provide evidence-based policy recommendations. :contentReference[oaicite:1]{index=1}

## Data Sources

- **OpenWeatherMap API** – Weather and air quality data.
- **European Environment Agency (EEA)** – Air pollution and health statistics.
- **World Bank & Eurostat** – GDP, life expectancy, urban population, and regional information. :contentReference[oaicite:2]{index=2} :contentReference[oaicite:3]{index=3}

## Project Workflow

- Data acquisition (API & web scraping)
- Data cleaning and quality assessment
- Data integration and storage (PostgreSQL)
- Data enrichment with socio-economic indicators
- Exploratory Data Analysis (EDA)
- Correlation and statistical analysis
- Data visualization
- Policy recommendations :contentReference[oaicite:4]{index=4}

## Technologies Used

- Python
- Pandas
- NumPy
- PostgreSQL
- Matplotlib
- Seaborn
- OpenWeatherMap API

## Repository Structure

```text
Data-Management-Project/
│
├── README.md
├── Data Management developed codes.ipynb
├── Data Management project Report.pdf
└── datasets/
```

## Key Findings

- Higher pollution levels are associated with poorer health outcomes.
- Weather conditions influence pollutant concentration and dispersion.
- Strong correlations exist between PM2.5, NO₂, O₃, and pollution-related mortality.
- Economic and regional factors contribute to differences in life expectancy across Europe. :contentReference[oaicite:5]{index=5} :contentReference[oaicite:6]{index=6}

## How to Run

1. Clone the repository.
2. Install the required Python libraries.
3. Open `Data Management developed codes.ipynb`.
4. Configure the PostgreSQL database if required.
5. Run the notebook sequentially.
