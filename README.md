## Twitter Sentiment Analysis 
![Twitter Sentiment Analysis](https://raw.githubusercontent.com/you915/Sentiment-Analysis-of-Twitter-Data-for-predicting-Apple-stock-price/master/Images/twitter-stock-market.jpg)

# Stock Movement Analysis Based on Social Media Sentiment

This project predicts stock movements using sentiment analysis of social media data (Twitter) and stock price data. 

## Features
1. Data Scraping
   - Tweets: Scraped using `GetOldTweets3` (or simulated in the notebook).
   - Stock Prices: Fetched using `yfinance`.
2. Data Cleaning & Feature Engineering
   - Cleaning tweets (stopwords, punctuation, hyperlinks removed).
   - Sentiment analysis using `VADER` sentiment analyzer.
   - Feature extraction: Tweet volume, sentiment trends, etc.
3. Prediction Models
   - Random Forest Regressor
   - Support Vector Regressor (SVR)
4. Evaluation
   - Metrics: RMSE, MAE, R² Score
   - Visualization of actual vs. predicted prices and feature importance.

## Dependencies
- Python 3.x
- Libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `yfinance`, `nltk`, `scikit-learn`

## How to Run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Open the notebook `Stock_Analysis.ipynb` in Jupyter Notebook or Jupyter Lab.
3. Follow the steps in the notebook to execute the analysis.

---

## Folder Structure
- `Stock_Analysis.ipynb`: Main Jupyter Notebook.
- `requirements.txt`: Python dependencies.
- `README.md`: Project overview.
- `report.pdf`: Detailed explanation of the approach.

---

## Results
- RMSE: Random Forest (31.40), SVR (24.60)
- Feature Importance: Sentiment trends and tweet volume are highly significant.
