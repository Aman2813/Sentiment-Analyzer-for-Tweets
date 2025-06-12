# Sentiment Analyzer for Tweets

This project analyzes the sentiment of tweets and classifies them as Positive, Negative, or Neutral using TextBlob.

## Project Description

- The app reads tweets from a CSV file (`tweets.csv`).
- Each tweet is analyzed using TextBlob's sentiment analysis.
- A neutral threshold is applied:  
  - Polarity >= 0.05 → Positive  
  - Polarity <= -0.05 → Negative  
  - Otherwise → Neutral
- Results are displayed in terminal.
- Summary of sentiment counts is also shown.


## Tools & Libraries Used

- Python 3.x
- pandas
- textblob

## File Structure

- `sentiment_analyzer.py` — Main Python script to run the sentiment analysis.
- `tweets.csv` — Input CSV file containing tweets.
- `requirements.txt` — Dependencies list.

---

## Setup Instructions

- Dowload Zip File
- Install dependencies from Requirements.txt
- open the folder in vscode
- run python sentiment_analyzer.py in terminal of vscode
