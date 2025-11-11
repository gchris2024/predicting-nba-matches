### (WORK IN PROGRESS)
<br>

Stage 1: Predictors include Venue, Opponent, Hour, and Day

Stage 2: Add predictors FGA, FGM, 3PM, 3P%, FTA, FTM, FT%

This project was inspired by a video by [Dataquest](https://www.youtube.com/@Dataquestio), but adapted to the NBA instead of the EPL.

### Data Source / Legal
Initially, I built a Python script to collect NBA schedules using Selenium and BeautifulSoup, which taught me about HTML parsing, rate limiting, and responsible automation. After learning more about data-use policies I stopped using live scraping, only using a combination of my local snapshot and [this dataset from Kaggle](https://www.kaggle.com/datasets/eoinamoore/historical-nba-data-and-player-box-scores?resource=download&select=TeamStatistics.csv).