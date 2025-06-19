# CPI Inflation Analysis: India (2013–2020)

This project presents a data-driven analysis of India’s **Consumer Price Index (CPI)** from 2013 to 2020. The goal is to evaluate inflation trends across key consumption categories and understand how prices evolved over time, using tools from R and data science.

## Overview

Using publicly available government CPI data, the project performs:

- Data cleaning and month/year parsing
- Long-format data transformation for plotting
- Time series visualization of Food, Fuel, and Housing prices
- Calculation of monthly percent change in fuel
- Identification of the most volatile CPI categories

## Technologies Used

- R (v4.5+)
- tidyverse: `dplyr`, `tidyr`, `ggplot2`, `lubridate`, `readr`
- R Markdown for reporting and PDF rendering

## Project Structure

```
📦 cpi-inflation-analysis
├── CPI_Analysis.Rmd                # Main RMarkdown report
├── CPI_India_Analysis_AashitaShukla.pdf   # Final rendered PDF report
├── outputs/
│   ├── cpi_trend_plot.png
│   ├── fuel_pct_change_plot.png
│   └── volatility_plot.png
```

## Key Insights

- **Fuel and Light** prices were the most volatile, especially during the 2020 pandemic
- **Food and Beverages** followed a steady, seasonal pattern driven by agricultural cycles
- **Housing** remained relatively stable across years

## Data Source

This project uses official CPI data from the **Government of India** available on [data.gov.in](https://data.gov.in).

## Report Access

You can view the full PDF report [here](CPI_India_Analysis_AashitaShukla.pdf) or explore the code in the `.Rmd` file.

---

## Future Work

- Add CPI comparison between Urban and Rural sectors
- Forecast inflation trends using ARIMA or Prophet models
- Deploy visual dashboard using R Shiny

---

## Connect

Made by [Aashita Shukla](mailto:ashukla32@wisc.edu)  
Open to feedback, suggestions, or collaboration!
