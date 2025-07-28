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

4  Sentiment Feature Engineering

We generated new sentiment-based features to capture behavioral signals:

- **Sentiment_Change**: Difference in sentiment score from previous time
- **Sentiment_MA_3**: 3-period moving average to smooth out noise
- **Sentiment_Std_7**: 7-period rolling standard deviation to capture volatility

These were later correlated with trading metrics like `Closed PnL`.

## 🧠 Insight Summary

Bar plots and EDA show that:

- **Low Sentiment**: Slightly positive average PnL (48.63)
- **Medium Sentiment**: Mostly flat, indicating neutral market (0.00)
- **High Sentiment**: Highest trader gains (Avg. PnL 79.89)

This shows **higher trader profits align with more positive market sentiment**.

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

4  Sentiment Feature Engineering

We generated new sentiment-based features to capture behavioral signals:

- **Sentiment_Change**: Difference in sentiment score from previous time
- **Sentiment_MA_3**: 3-period moving average to smooth out noise
- **Sentiment_Std_7**: 7-period rolling standard deviation to capture volatility

These were later correlated with trading metrics like `Closed PnL`.

## 🧠 Insight Summary

Bar plots and EDA show that:

- **Low Sentiment**: Slightly positive average PnL (48.63)
- **Medium Sentiment**: Mostly flat, indicating neutral market (0.00)
- **High Sentiment**: Highest trader gains (Avg. PnL 79.89)

This shows **higher trader profits align with more positive market sentiment**.

📌 For a detailed breakdown of the exploratory analysis and insights, please refer to analysis.md

## ⚠️ Disclaimer

- This project is part of a **data science internship assignment For Selection**.
- The dataset is **proprietary to the assignment** and is **not publicly shared**.
- All analysis is performed in an **academic/learning context** and should **not** be used for real financial decisions.
