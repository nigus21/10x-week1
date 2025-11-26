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


