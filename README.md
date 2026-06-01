# PrimetradeAI Internship Assignment

## Objective

Analyze the relationship between Bitcoin market sentiment and trader performance using:

- Bitcoin Fear & Greed Index dataset
- Hyperliquid historical trader dataset

The goal was to identify patterns between market sentiment and trading outcomes and explore whether trader behavior can help predict sentiment.

---

## Files

## Dataset Links

Historical Trader Data:
https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view

Fear & Greed Index:
https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view

## Notebook

Main analysis notebook: `notebooks/analysis.ipynb`

Note: GitHub preview may occasionally fail for large notebooks. If preview doesn’t load, click **Raw** or download and open in Jupyter/VS Code.

### notebooks/analysis.ipynb

Contains:

- data cleaning
- merging datasets
- exploratory analysis
- visualizations
- machine learning experiment

---

## Key Insights

### 1. Highest profitability during Extreme Greed

Average Closed PnL was highest during Extreme Greed.

---

### 2. Win rate strongest in Extreme Greed

Winning trade percentage peaked during bullish sentiment.

---

### 3. Most trades happened during Fear

Trading activity increased during uncertain market conditions.

---

### 4. Sell trades outperformed in most sentiment conditions

Especially during Extreme Greed.

---

### 5. ML experiment

A Random Forest classifier was trained using trader activity features.

Accuracy achieved:
**39.6%**

This was significantly above random baseline (~20%), showing trader behavior contains predictive sentiment signals.

---

## Tools used

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- VS Code
