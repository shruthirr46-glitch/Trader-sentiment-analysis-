# 📊 Trader Sentiment Analysis

## 📌 Project Overview
This project analyzes the relationship between *Bitcoin market sentiment (Fear & Greed Index)* and *trader performance* using historical trading data.

The goal is to determine whether market sentiment has any impact on trading profitability and to uncover patterns that can help improve trading strategies.

---

## 📂 Datasets

### 1. Fear & Greed Index
- Columns: date, classification, value
- Represents market sentiment categories such as *Fear, **Greed, and **Neutral*

### 2. Historical Trader Data
- Includes:
  - Account, Coin, Execution Price  
  - Size (Tokens & USD), Side (BUY/SELL)  
  - Timestamp, Closed PnL  
  - Transaction details  

---

## ⚙️ Methodology

1. *Data Loading*
   - Imported datasets using pandas

2. *Data Cleaning*
   - Converted timestamp columns to datetime format  
   - Removed null values  
   - Extracted date for merging  

3. *Data Merging*
   - Joined datasets on common date field  

4. *Analysis*
   - Calculated average, total, and count of PnL by sentiment  
   - Compared BUY vs SELL performance  
   - Computed correlation between sentiment and PnL  

5. *Visualization*
   - Scatter plot: PnL vs Fear & Greed Index  
   - Bar chart: Average PnL by sentiment  
   - Boxplot: Distribution of PnL  

---

## 📊 Key Insights

- The correlation between *market sentiment and trader PnL is very low (~0.02)*, indicating a weak relationship.

- *SELL trades show slightly higher average profits than BUY trades*, suggesting better performance in bearish conditions.

- PnL values are highly dispersed, showing *significant variability in trading outcomes*.

- Extreme profits and losses occur across all sentiment categories.

- Market sentiment alone is *not a strong predictor of trading success*.

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🚀 Future Improvements

- Analyze impact of leverage on performance  
- Perform coin-level profitability analysis  
- Time-series trend analysis  
- Build predictive models using machine learning  

---

## 📎 Conclusion

This analysis shows that while market sentiment provides useful context, it does not significantly determine trading performance. Successful trading depends more on strategy, execution, and risk management.

---

## 👩‍💻 Author
Shruthi R R# Trader-sentiment-analysis-
Analysis of trader performance vs Bitcoin  Market sentimentbusing Fear  and Green Index
