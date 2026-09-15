# Bhutan Tourism: Data Science & Machine Learning Project

## Project Overview
This Streamlit application analyzes tourism data for Bhutan and uses machine 
learning to predict international tourist arrivals.

## Research Questions
1. How have international tourist arrivals to Bhutan changed over time?
2. What is the relationship between tourism receipts and tourist arrivals?
3. Can we predict future tourist arrivals using economic indicators?
4. What factors have the strongest influence on tourism in Bhutan?

## Data Source
World Bank API - Bhutan (country code: BTN)
- International tourism, number of arrivals (ST.INT.ARVL)
- International tourism, receipts (ST.INT.RCPT.CD)
- GDP (NY.GDP.MKTP.CD)
- Population (SP.POP.TOTL)
- Inflation (FP.CPI.TOTL.ZG)

## Tools Used
- Python 3
- Streamlit
- Pandas
- NumPy
- Matplotlib

## How to Run Locally
```bash
streamlit run app.py

## Project Context — Reflection Questions

### 1. Unit of analysis
Each row represents one destination region in Bhutan for a given year.

### 2. Outcome to predict
Annual visitor numbers (tourist arrivals).

### 3. Is prediction necessary?
Yes — for tourism planning, resource allocation, and policy-making.

### 4. Ideal data
Monthly arrivals, tourist demographics, economic indicators, 
infrastructure data, weather data, and policy changes.

### 5. Who is affected by incorrect predictions?
Tourism businesses, local communities, government agencies, 
the environment, and tourists themselves.
