

# Social Media Sentiment Analysis (Twitter Airline Dataset)

## Overview

This project explores customer sentiment in the **U.S. airline industry** using data from Twitter.
By building a PostgreSQL database and running SQL analysis, we uncover **what passengers feel**, **why they complain**, and **who influences the conversation**.

---

## Tech Stack

* **PostgreSQL** (pgAdmin for database management)
* **SQL** (data cleaning, aggregation, text analysis)
* **Python** (data preprocessing for import)

---

## Project Structure

```
├── data/                   # Cleaned dataset (CSV, deduplicated & UTF-8)
├── sql/
│   ├── schema.sql           # Database schema
│   ├── analysis_queries.sql # SQL queries for insights
└── README.md
```

---

## Key Analysis

* **Sentiment Distribution** → How many tweets are positive, negative, neutral?
* **Airline Comparison** → Which airlines get the most negative tweets?
* **Complaint Reasons** → Top negative categories (e.g., delays, cancellations).
* **Influencers** → Who are the top users driving engagement (retweets)?
* **Trends Over Time** → How sentiment changes day by day.

---

## Example Insights

* Over **60% of tweets are negative**, with delays and poor service being top complaints.
* **United and American Airlines** receive the most negative mentions.
* A handful of users with large followings amplify sentiment via retweets.

---

## Dataset

* Source: [Twitter US Airline Sentiment (Kaggle)](https://www.kaggle.com/crowdflower/twitter-airline-sentiment)
* Rows: 14,640
* Columns: 15

---

