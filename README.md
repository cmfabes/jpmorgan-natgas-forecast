Natural Gas Price Forecast – JPM Quant Simulation

This project replicates a simplified quant-style workflow for forecasting natural gas storage and forward prices. It uses historical EIA storage data and spot prices to estimate seasonal patterns, evaluate deviations from normal behavior, and generate a forward-looking storage distribution similar to what real quant research teams produce.

What the Project Does

* Loads and cleans natural gas storage and price data

* Calculates year-over-year seasonal patterns

* Flags storage deviations relative to historical norms

* Models next-12-month storage levels using Monte Carlo-style sampling

* Generates a forecast curve for expected prices based on simulated storage

* Provides clear visualizations inside the notebook

How It Helps With Analysis

* Translates messy EIA storage data into interpretable signals

* Shows how storage shocks cascade into pricing expectations

* Gives a structured example of a quant research workflow

* Demonstrates time-series thinking, scenario modeling, and forecast evaluation

Files Included

```
jpmorgan-natgas-forecast/
│
├── JPM_NatGas_Storage_Model.ipynb   # Main simulation + visualizations
└── Nat_Gas.csv                      # Historical sample data
```

Skills Demonstrated

* Python

* Time Series Analysis

* Forecasting & Modeling

* Data Cleaning

* Quantitative Research
