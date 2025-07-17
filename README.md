# USGS Hydropower Estimator for Washington Rivers

This Python code pulls daily streamflow data from the USGS API for  Washington State river sites, estimates hydropower generation using physics, and creates an interactive Plotly chart showing power output (in MW) over time.

---

## What It Does

- Fetches streamflow data from the USGS National Water Information System
- Estimates hydropower output using turbine efficiency, physics, and dam head heights
- Visualizes the results with an interactive Plotly line chart

---

## Requirements

- Python 
- `pandas`
- `requests`
- `plotly`

You can install the packages with:

```bash
pip install pandas requests plotly
