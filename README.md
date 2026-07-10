# Gold Price Analysis Dashboard

An interactive Tableau dashboard tracing 50 years of gold prices, from 1971 to 2021. It visualizes long-term trends, yearly returns, and annual volatility to give a clear, compact read on gold's performance as an investment across five decades.

![Tableau](https://img.shields.io/badge/Built%20with-Tableau-E97627?logo=tableau&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)

<!-- Optional: publish the workbook to Tableau Public (free) and add the live link here, e.g.
**Live dashboard:** [View on Tableau Public](https://public.tableau.com/app/profile/your-profile)
A live link lets recruiters interact with the dashboard without installing Tableau. -->

## Dashboard Preview

[![Dashboard Preview](https://github.com/dhruvdesai14/Gold-Price-Analysis-Dashboard/raw/main/images/gold_dashboard_preview.png)](https://github.com/dhruvdesai14/Gold-Price-Analysis-Dashboard/blob/main/images/gold_dashboard_preview.png)

> The image is a static preview. Open the workbook in Tableau Desktop for the full interactive version.

## What the Dashboard Covers

Four visualizations, each covering a different angle on gold's price history:

- **Gold Price Trends (Yearly Closing Price)**: a line chart of yearly closing prices showing the overall long-term trajectory.
- **Yearly % Change**: a bar chart of annual percentage change, highlighting the strongest years of growth and decline.
- **5-Year & 10-Year Returns**: a line chart comparing average 5- and 10-year returns to show longer-horizon performance.
- **Yearly Highs & Lows**: an area chart of annual high and low prices, illustrating how volatile each year was.

The view also surfaces four headline metrics: the most recent closing price, annual return, 5-year return, and 10-year return (as of the latest year in the dataset, 2021).

## Key Insights

- **Long-term growth:** yearly closing prices show a clear upward trajectory across the five decades.
- **Volatility:** the annual % change chart pinpoints the years with the sharpest swings, the periods carrying both the most risk and the most upside.
- **Investment performance:** the 5- and 10-year return comparison gives a longer-horizon read on gold as a hold.
- **Annual price range:** the highs-and-lows view surfaces the years with the widest trading ranges.

## Data Source

Historical gold prices from **Yahoo Finance**, covering **1971 to 2021**. The `data/` directory contains the raw dataset.

> Note: the headline metrics reflect the latest year in this dataset (2021), not live market prices.

## Tools

- **Tableau Desktop** 2021.1 or later.

## How to Open

1. **Download the workbook:** grab `Gold-Price-Analysis.twb` from this repository.
2. **Open in Tableau:** launch it in [Tableau Desktop](https://www.tableau.com/products/desktop) 2021.1 or later.
3. **Explore:** switch views using the tabs along the bottom, and hover over any data point for exact values.

## Repository Structure

- `Gold-Price-Analysis.twb`: the main Tableau workbook.
- `data/`: raw gold price dataset (Yahoo Finance).
- `docs/`: supporting documentation and notes.
- `images/`: dashboard screenshots used for the preview.
- `README.md`: project overview and instructions.
- `LICENSE`: license details.

## License

Released under the [MIT License](https://github.com/dhruvdesai14/Gold-Price-Analysis-Dashboard/blob/main/LICENSE) — free to use, modify, and share with attribution.

## Author

**Dhruv Desai** Data Analyst, Toronto, ON
[LinkedIn](https://www.linkedin.com/in/dhruvdesai14) · [GitHub](https://github.com/dhruvdesai14)
