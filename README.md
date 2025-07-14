# Stock Analysis: Tesla (TSLA) & GameStop (GME)

This project analyzes the historical stock prices and quarterly revenues of **Tesla (TSLA)** and **GameStop (GME)** using Python. Data is fetched from Yahoo Finance and macrotrends.net, cleaned, and visualized using interactive graphs.

---

## Features

- Extract historical stock data using `yfinance`
- Scrape quarterly revenue data from macrotrends using `BeautifulSoup` or `pandas.read_html()`
- Clean and format revenue and stock datasets
- Visualize stock price and revenue trends using interactive Plotly graphs
- Dual subplot graph: Share Price (top), Revenue (bottom)

---

## Requirements

Install all required dependencies:

```bash
pip install yfinance pandas plotly beautifulsoup4 lxml
```

---

## How to Use

1. Clone this repository or open `Stock_analysis.ipynb` in Jupyter Notebook.
2. Run all cells step-by-step.
3. Use the following function to generate visualizations:

```python
make_graph(tesla_data, tesla_revenue, 'Tesla')
make_graph(gme_data, gme_revenue, 'GameStop')
```

---

## Visualizations

Each company has a graph with:
- **Top Plot:** Historical Share Price
- **Bottom Plot:** Quarterly Revenue  
> Data is limited up to mid-2021 to align with available macrotrends data.

---

## Data Sources

- Stock Prices: [Yahoo Finance](https://finance.yahoo.com/)
- Revenue Data: [Macrotrends](https://www.macrotrends.net/)

---

## Notebook Structure

1. **Import libraries**
2. **Extract stock data (TSLA, GME)**
3. **Scrape revenue data**
4. **Clean and preprocess datasets**
5. **Visualize using `make_graph()`**

---
