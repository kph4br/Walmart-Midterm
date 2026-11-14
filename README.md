# Walmart Hurricane Analytics (DS2002 Midterm)
Team Walmart Warriors: Claire (@kph4br), Marlise (@MLuc123), Nate (@NBushey26)

Cleans messy Walmart POS data from Florida (Sept 2024), joins it to Open-Meteo weather data, and answers five questions about pre-Hurricane Helene demand.

## Final notebook
   `notebooks/FINAL - Midterm Project Brief.ipynb` contains the cleaning pipeline, decision log, weather API join, Q1–Q5, charts and reflection.
   Slides: `notebooks/Walmart Midterm Slides Final.pptx`.

## How to run
1. Open the notebook in Google Colab (badge at the top).
2. Runtime → Run all. The first cell clones this repo to `/content/Walmart-Midterm` and reads from `data/`.
3. Weather comes live from Open-Meteo (`https://archive-api.open-meteo.com/v1/archive`); no API key is needed.

## Data
`data/` holds the five supplied files: transactions, store locations, product catalog, distribution centers, and the SQLite inventory/sales database.
