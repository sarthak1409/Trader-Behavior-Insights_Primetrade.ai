# 📊 Trader Behavior Insights – Sentiment vs PnL

This project explores the relationship between **market sentiment** and **trader performance** using provided Hyperliquid trading data. The goal is to derive insights that can inform smarter trading strategies.

## 📁 Project Structure

```
├── notebook/
│   └── main.ipynb     # Jupyter Notebook containing all EDA & visualizations
├── assets/
│   └── main_insight.png         # Bar plot of PnL vs Sentiment Category
├── analysis.md                      # Summary of the EDA and key findings
├── README.md                        # Project overview and setup guide
├── requirements.txt                 # Python libraries required to run the notebook
```

## 📌 Getting Started

1. Clone this repository
2. Install the dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```bash
jupyter notebook notebook/sentiment_analysis.ipynb
```

## 🧠 Insight Summary

Bar plots and EDA show that:

- **Low Sentiment**: Slightly positive average PnL (48.63)
- **Medium Sentiment**: Mostly flat, indicating neutral market (0.00)
- **High Sentiment**: Highest trader gains (Avg. PnL 79.89)

This shows **higher trader profits align with more positive market sentiment**.
