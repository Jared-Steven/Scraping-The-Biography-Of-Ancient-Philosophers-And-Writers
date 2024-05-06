# Scraping The Biography Of Ancient Philosophers And Writers

## Overview

This project involves scraping biographical information about ancient philosophers and writers from the Britannica website. The goal is to gather data such as the author's name, occupation, summary, birth date, date of demise, and image link.

## Code Details

The Python script `scrape_biographies.py` is used to perform the scraping. It utilizes the `requests` library to fetch web pages and `BeautifulSoup` for parsing HTML content.

### Instructions

1. Install the required libraries: `requests` and `beautifulsoup4`.
2. Run the Python script `scrape_biographies.py`.
3. The script iterates over a list of URLs corresponding to the biographies of various philosophers and writers.
4. For each URL, it extracts relevant information such as the author's name, occupation, summary, birth date, date of demise, and image link.
5. The information is printed to the console.

## Data Collection

The script scrapes biographical data for the following philosophers and writers:

- Voltaire
- Jean-Jacques Rousseau
- Saint Augustine
- Socrates
- John Stuart Mill
- Thomas Hobbes
- Karl Marx
- Benedict de Spinoza
- Adam Smith
- John Locke
- Noam Chomsky
- Immanuel Kant
- Rene Descartes
- Saint Thomas Aquinas
- Plato
- Francis Bacon, Viscount Saint Alban
- Aristotle
- Georg Wilhelm Friedrich Hegel
- David Hume
- Niccolo Machiavelli

## Output

The output of the script includes a list of dictionaries, with each dictionary containing the biographical information for a specific author. The information includes the author's name, occupation, summary, birth date, date of demise, and image link.

## Note

- This project is for educational and informational purposes only.
- Make sure to respect the terms of service and usage policies of the Britannica website.
- Web scraping may be subject to legal restrictions or limitations imposed by website owners.
