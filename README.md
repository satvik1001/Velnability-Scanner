# Velnability-Scanner

Simple web-based vulnerability scanner (Flask) that runs a set of checks against a target URL and produces a report and screenshots.

## Features
- URL scanning via a web UI
- Generates a report at `reports/report.txt`
- Saves screenshots to `static/screenshots`
- Uses Selenium for proof screenshots and `wordlists/` for checks

## Prerequisites
- Python 3.10+  
- Google Chrome (or another Chromium browser) installed for Selenium
- Git (optional)

## Install
1. Clone or copy the repo into a folder.
2. From the project root run:

```bash
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS / Linux
source .venv/bin/activate
pip install -r requirements.txt

