# Sports Analytics Engine (Advanced)

**Project**: SQL Advanced Project #5
**Dataset**: Players.csv, Seasons\_Stats\_cleaned.csv
**Core File**: `nba_analytics.sql`
**Helper**: `python_csv_fix.ipynb`

---

## Overview

This project is a **Sports Analytics Engine** built with SQL. It uses NBA player statistics to compute advanced performance metrics, identify patterns, and explore predictive insights.

---

## Files in Repo

* **`nba_analytics.sql`** → Database schema + advanced queries (metrics, ranking, pattern detection).
* **`Players.csv`** → Player details (height, weight, college, birthplace).
* **`Seasons_Stats_cleaned.csv`** → Season-level cleaned stats (PER, TS%, points, rebounds, etc.).
* **`python_csv_fix.ipynb`** → Notebook to clean and prepare CSVs before loading into SQL.

---

## Example Queries

* **Advanced Metrics (2017)**: Calculate PTS/game, REB/game, and PER ranking.
* **Top PER Players**: Find top 5 players with highest PER and their colleges.
* **Similarity Search**: Identify players with similar height/weight to LeBron James.
* **Team Rankings**: Rank players within their team by PER.
* **College Stats**: Find top career scorers from a specific college.

---

## How to Run

1. Run `nba_analytics.sql` to create tables and load data.
2. Import `Players.csv` and `Seasons_Stats_cleaned.csv` into their respective tables.
3. Execute example queries inside the SQL file to generate insights.

---

## Next Steps

* Expand metrics (usage %, on/off splits).
* Add rolling-window features with window functions.
* Build predictive features (win probability, player comparison).
* Automate ingestion + analysis pipeline.

---

**License**: MIT
