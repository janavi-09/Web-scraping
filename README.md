# 🕷️ Web Scraping Project: Company Perks

## 📝 Description

This project uses Python to scrape top company names and their employee perks from AmbitionBox, overcoming anti-scraping measures and saving the data for analysis.

## 🛠️ Tech Stack
```
Python Libraries: pandas, requests, beautifulsoup4, lxml
```

Target: AmbitionBox (Company Listing Page)

## ⚡ Key Features
Access Bypass: Implements a custom User-agent header to bypass HTTP 403 (Access Denied) errors.

Data Extraction: Parses HTML to extract Company Names and Perks (e.g., Job Security, Work-Life Balance).

Data Cleaning: Aligns data lists by truncating mismatched entries to create a structured dataset.

Output: Exports a clean dataset to Web_Scraping.csv and performs a frequency count of perks.

## 🚀 Quick Start

### Install dependencies:
```
pip install pandas requests beautifulsoup4 lxml
```
### Run the Notebook: 
Open Web_scrap.ipynb and execute all cells.
