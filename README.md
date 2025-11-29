⭐ WEEK 1 — High-LEVEL SUMMARY

In Week 1, my goal was to answer a practical business question:

“Does financial news sentiment influence daily stock price movements?”

To explore this, I went through four major steps.

1️⃣ I Collected and Prepared the Data

I gathered two types of information:

📌 Stock Market Data

Daily price information such as:

open, high, low, close

volume

📌 Financial News Headlines

Daily news related to the company or stock I was analyzing.

Why this matters:

Stock prices move based on investor reactions.
Investors react to news.
So understanding news helps me understand market behavior.

2️⃣ I Performed Sentiment Analysis on the News

Using NLP (Natural Language Processing), I converted each headline into a sentiment score:

Polarity Score (–1 to +1)

–1 → very negative news

0 → neutral

+1 → very positive news

Example:
“Company beats earnings expectations” → positive
“Company faces investigation” → negative

Why this matters:

This allowed me to turn qualitative, subjective headlines into numbers that I could analyze objectively.

3️⃣ I Calculated Daily Stock Returns

To measure how the stock reacted, I calculated daily returns:

Daily Return = Percentage change in stock price

Example:
Price from $100 → $102 → return = +2%

Why this matters:

Returns show whether the market responded positively or negatively after the news came out.

4️⃣ I Measured the Relationship Between Sentiment and Returns
Once I had: daily sentiment and daily stock returns

I aligned them by date and checked the correlation.

What I found:
There was usually a weak but positive correlation.
This means:
Positive news tends to be followed by slightly positive stock returns
Negative news tends to be followed by slight declines
But the effect is not very strong because markets react to many factors

Business meaning:
Sentiment gives an early signal of potential price direction, but it is not a full predictor.

5️⃣ I Visualized the Results
To communicate the insights clearly, I created:
Line charts for stock prices
Scatter plots of polarity vs returns
Correlation metrics to quantify the relationship

Why this matters:
These visuals make it easy for any decision-maker to quickly see:
- trends
- patterns
- how news sentiment affects market behavior

⭐ My Final Takeaway from Week 1
By the end of Week 1, I learned that:
✔ News sentiment does affect stock movement
✔ Positive headlines are usually followed by small price increases
✔ Negative headlines often lead to declines
✔ The relationship is real but not very strong
✔ Sentiment can help in short-term forecasting and risk assessment

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


