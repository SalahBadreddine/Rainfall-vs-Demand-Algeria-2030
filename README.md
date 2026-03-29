# Time Series Analysis of Algeria Water Security 

## Project Objective
This project addresses a critical subject-matter question: **"Will Algeria's water demand exceed its natural rainfall supply by 2030?"** The analysis utilizes a dual-series approach to compare environmental supply against socio-economic demand, providing a data-driven outlook on regional water stress.

## 📂 Data & Environment Setup
This project is built using **R**. To ensure the analysis runs correctly, please follow these steps:

### How to Run:
1. **Upload Data:** Open the `.ipynb` notebook and upload the following two CSV files to the **Files** sidebar in Colab:
   - `algeria-rainfall-timeseries.csv` (1st Series)
   - `algeria-water-demand-annual.csv` (2ns Series)
2. **Execute:** Select **Runtime > Run All**. 
3. **Libraries:** The notebook automatically handles the installation of required packages (`tseries`, `forecast`, `ggplot2`, `randtests`, etc.).

## 📊 Methodology
* **Primary Analysis (Rainfall):** Detailed ARIMA/SARIMA modeling including Box-Jenkins specification, stationarity testing (ADF), and rigorous residual diagnostics (Shapiro-Wilk, Runs Test).
* **Secondary Analysis (Demand):** Trend-based modeling of historical water withdrawal data.
* **Synthesis:** Integration of both forecasts to identify the "Intersection Point" where demand risks outstripping natural supply.

## 📈 Key Visuals
The report prioritizes visual evidence, featuring:
* Time Series Decomposition (Trend/Seasonality/Remainder).
* ACF/PACF plots for model identification.
* Residual distribution and normality plots for model validation.
* A final Comparison Forecast (Supply vs. Demand).