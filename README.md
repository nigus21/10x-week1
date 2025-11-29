# 📊 Week 1 — Sentiment Analysis & Stock Movement Study

## 📌 Overview

In Week 1 of my project, I set out to answer a key question:

> **Does financial news sentiment influence daily stock price movements?**

To explore this, I combined financial news data with stock market data and performed sentiment analysis, return calculations, and correlation study.

---

## 🗂️ 1. Data Collection & Preparation

I worked with two main datasets:

### **📌 Stock Market Data**

* Open, High, Low, Close
* Volume
* Daily price movements

### **📌 Financial News Headlines**

* Daily headlines related to the target stock
* Cleaned and prepared for sentiment analysis

**Why:**
Stock prices move based on investor behavior, and investors react to news.
Understanding news provides insights into short-term market reaction.

---

## 💬 2. Sentiment Analysis (NLP)

I applied Natural Language Processing to convert each news headline into a numerical sentiment score.

### **Polarity Score (–1 to +1)**

* **–1** → very negative
* **0** → neutral
* **+1** → very positive

This transformed subjective text into measurable data.

---

## 📈 3. Stock Return Calculation

To understand how markets responded, I calculated daily stock returns using:

```
Daily Return = (Close - Previous Close) / Previous Close
```

This shows whether the stock moved up or down after the news.

---

## 🔗 4. Relationship Between Sentiment & Stock Returns

After aligning daily sentiment with daily stock returns, I analyzed the correlation.

### **Key Finding:**

There was a **weak but positive correlation** between news polarity and stock returns.

**Meaning:**

* Positive news tends to be followed by slightly positive returns
* Negative news tends to be followed by slightly negative returns
* Sentiment affects the market, but it’s only one of many factors

---

## 📊 5. Data Visualization

To make the results easy to understand, I created:

* 📈 **Line charts** for stock prices
* 🟢 **Scatter plots** of sentiment vs. returns
* 🔥 **Correlation metrics** for numerical insights

These visuals reveal patterns and help interpret how sentiment influences market behavior.

---

## ✅ Final Takeaways (Week 1)

* News sentiment **does influence** short-term stock movements
* Positive sentiment is usually followed by mild price increases
* Negative sentiment is associated with mild declines
* The relationship is **real but not strongly predictive**
* Sentiment analysis can assist in forecasting and risk assessment




# 10x Week-1 Project: Predicting Stock Movements with News Sentiment

## Project Overview
This project explores the relationship between financial news headlines and stock price movements. The goal is to perform **Exploratory Data Analysis (EDA)** on a large corpus of financial news and to compute **partial stock technical indicators** using Python. Insights from this analysis will form the foundation for later correlation and predictive analysis tasks.

**Key Objectives:**
- Analyze patterns in financial news headlines.
- Identify top publishers, publication trends, and common financial keywords.
- Prepare a small reproducible dataset for efficient analysis.
- Compute basic stock indicators such as Moving Average (MA), Relative Strength Index (RSI), and MACD for sample stocks.

---

## Dataset

The dataset used for Week-1 analysis is named:

`raw_analyst_ratings.csv` - https://drive.google.com/file/d/1kV1w6iOqdLBCdbeqg1V-3I1kJNKbmz30/view?usp=sharing

**Columns:**
| Column     | Description |
|-----------|-------------|
| headline  | Title of the news article |
| url       | Link to full article |
| publisher | Source of the article |
| date      | Publication date and time (UTC) |
| stock     | Stock ticker symbol associated with the news |

**Sample Dataset:**  
For reproducibility and easier notebook execution, a small sample (~2000 rows) is provided:  
`data_sample_for_repo.csv`


