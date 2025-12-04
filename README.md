# Predicting NBA Matches

This repository hosts experiments for predicting NBA match outcomes using match metadata and team statistics. The goal is to explore how well simple features (venue, opponent, time) and adding team box-score statistics (FGA, FGM, 3PM, 3P%, FTA, FTM, FT%) improve predictive performance.

### Project Stages
- Stage 1: Baseline predictors — `Venue`, `Opponent`, `Hour`, `Day`.
- Stage 2: Add team stat predictors — `FGA`, `FGM`, `3PM`, `3P%`, `FTA`, `FTM`, `FT%`.

### Inspiration
This project was inspired by a Dataquest walkthrough (adapted from EPL to NBA), and is intended as a learning/experiment repo.


### Data Source / Legal
Initially, I built a Python script to collect NBA schedules using Selenium and BeautifulSoup, which taught me about HTML parsing, rate limiting, and responsible automation. After learning more about data-use policies I stopped using live scraping, only using a combination of my local snapshot and [this dataset from Kaggle](https://www.kaggle.com/datasets/eoinamoore/historical-nba-data-and-player-box-scores?resource=download&select=TeamStatistics.csv).

Be mindful of the terms of service for any external data source and avoid scraping sites without permission.

