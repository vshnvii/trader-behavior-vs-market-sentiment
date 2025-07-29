#  Trader Behavior vs Market Sentiment

A data analysis project to explore how **trader actions (buy/sell, size, PnL)** correlate with **market sentiment (Fear/Greed)** using real on-chain crypto data and sentiment indices.

---

## Project Structure

ds_vaishnavi_baghel/
├── notebook_1.ipynb ← Main Google Colab notebook for analysis
├── csv_files/ ← Raw and cleaned CSVs
│ ├── trader_data.csv
│ └── sentiment_data.csv
├── outputs/ ← All plots (.png)
│ ├── trade_side_by_sentiment.png
│ ├── trade_size_by_sentiment.png
├── ds_report.pdf ← Summary of insights
└── README.md ← You are here

---

##  Objective

To analyze the relationship between:
- Trade direction and sentiment (buy/sell vs fear/greed)
- Trade size under varying market emotions
- Overall profitability trends in different sentiment phases

---

## 📈 Key Visuals

-  **Boxplot**: Trade Size vs Sentiment  
-  **Countplot**: Number of Trades under Fear/Greed  
-  **Histogram**: Trade Size Distribution by Sentiment  
-  *(Optional)* Sentiment vs PnL trends (line chart)

---

##  Tech Stack

- **Python (pandas, seaborn, matplotlib)**
- **Google Colab** for analysis
- **GitHub** for version control

---

##  How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/trader-sentiment-analysis.git
   cd trader-sentiment-analysis
