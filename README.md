# 📘 Maybank Dividend Trend Analysis

## 🎯 Objective
To analyze the historical dividend performance of **Malayan Banking Berhad (Maybank)** by evaluating its Earnings Per Share (EPS), Dividend Per Share (DPS), and Dividend Payout Ratio over time. This project provides insight into Maybank’s dividend policy stability, shareholder returns, and overall earnings quality.

## 📂 Project Structure
```
maybank-dividend-analysis/
├── data/
│   └── maybank_financials_cleaned.csv
├── notebooks/
│   └── Maybank_dividend_Analysis.ipynb
├── charts/
│   ├── eps_trend_over_time.json
│   ├── dps_trend_over_time.json
│   └── payout_ratio_trend_over_time.json
├── requirements.txt
└── README.md
```

## 🧠 Key Features
- Loads publicly scraped Maybank financial data
- Cleans and processes EPS & DPS data
- Calculates dividend payout ratios
- Visualizes time-based trends with interactive charts
- Saves output charts in Altair/Vega JSON format

## 📊 Sample Insights
- **DPS peaked in 2023**, aligned with strong earnings growth
- **Dividend payout ratio** has stayed within a stable 60%–85% range
- Notable dip in 2020 likely due to COVID-19-related profit impact

## 🛠 Tools & Libraries Used
- **Python**: `pandas`, `altair`
- **Octoparse**: No-code scraping from KLSE Screener
- **VSCode & Jupyter Notebooks** for analysis
- **Altair** for lightweight, interactive visualizations

## 🚀 How to Run This Project
1. Clone this repo:
```bash
git clone https://github.com/your-username/maybank-dividend-analysis.git
cd maybank-dividend-analysis
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the notebook:
```bash
jupyter lab notebooks/dividend_analysis.ipynb
```

## 📁 Outputs
- `eps_trend_over_time.json`
- `dps_trend_over_time.json`
- `payout_ratio_trend_over_time.json`

You can visualize them using [Vega Editor](https://vega.github.io/editor/).

## 💼 Use This In Interviews
- Shows you can clean, analyze, and visualize financial data
- Demonstrates real-world understanding of dividend mechanics
- Explains technical insights in a business-friendly way

## 📬 Contact
If you found this useful or want to collaborate, feel free to reach out via GitHub or [LinkedIn](https://linkedin.com).

---

📌 Built by a data-driven analyst passionate about combining finance & tech.
