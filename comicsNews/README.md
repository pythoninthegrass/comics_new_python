## Top 10 Comic Book News from The Beat Website

Grabs the top news from the website The Beat https://www.comicsbeat.com/

## Setup
INSTALL:
import requests
from bs4 import BeautifulSoup
import sqlite3
from datetime import datetime
from reportlab.lib.pagesizes import letter
from reportlab.lib.styles import getSampleStyleSheet
from reportlab.lib.units import inch
from reportlab.platypus import SimpleDocTemplate, Paragraph, Spacer
import logging

RUN:
beatscraper.py

REVIEW REPORT:
headlines_report_datewillgohere


## WHAT IT DOES
Collect Data from https://www.comicsbeat.com/

Saves to Database SQL Lite

Geneates PDF List with top 10 most recent news headlines and their URLs
