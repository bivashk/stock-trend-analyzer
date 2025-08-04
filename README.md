# 📈 Stock Market Trend Analyzer

Analyze and visualize stock price trends effortlessly with this Python tool. Leveraging real-time data, technical indicators, and interactive charts, it helps traders and investors make informed decisions.

---

## 🚀 Features

- **Fetch Historical Stock Data**  
  Retrieve daily price data for any ticker from Yahoo Finance.
- **Technical Indicators**  
  - 50-day & 200-day Simple Moving Averages (SMA)  
  - Rolling Standard Deviation (Volatility)
- **Interactive Visualization**  
  Plot price charts and indicators using Plotly for intuitive exploration.
- **Easy-to-Use CLI**  
  Input the stock ticker and timeframe via command line.

---

## 📊 Example Output

![Sample Chart](docs/sample_chart.png)  
*Example: Price chart with 50/200-day SMA and rolling volatility.*

---

## 🧰 Tech Stack

- Python 3.x
- [yfinance](https://github.com/ranaroussi/yfinance)
- [pandas](https://pandas.pydata.org/)
- [plotly](https://plotly.com/python/)
- [matplotlib](https://matplotlib.org/)

---

## ⚡ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/bivashk/stock-trend-analyzer.git
cd stock-trend-analyzer
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the analyzer

```bash
python main.py --ticker AAPL --start 2022-01-01 --end 2023-01-01
```
Replace `AAPL` and dates with your desired stock and range.

---

## 📂 Project Structure

```
.
├── main.py
├── analyzer/             # Core analysis logic
├── data/                 # Example datasets
├── docs/                 # Documentation & sample outputs
└── README.md
```

---

## 📝 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙏 Acknowledgements

- [Yahoo Finance](https://finance.yahoo.com/) for stock data
- Open-source contributors to yfinance, pandas, plotly, and matplotlib
