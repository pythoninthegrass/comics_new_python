## Top 10 Comic Book News from The Beat Website

Grabs the top news from the website The Beat https://www.comicsbeat.com/

## Setup

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install beautifulsoup4 reportlab requests
```

## Usage

Run the script:

```bash
./beatscraper.py
```

Generates PDF report: `headlines_report_datewillgohere.pdf`

## What it does

Collects data from https://www.comicsbeat.com/, saves to a SQLLite Database, and then generates a PDF report.

Generated PDF lists top 10 most recent news headlines and their URLs.
