# Job Trends Analyzer

A Python-based project to scrape job listings (e.g., from Naukri), store them, extract useful data like skills and trends, and display it all in a visual dashboard.

## Features
- Scrapes job postings using BeautifulSoup
- Extracts title, company, location, salary, experience, post date, job description
- Stores jobs in SQLite with deduplication using hash
- Skill extraction from job descriptions
- CLI interface for scraping jobs
- Error logging
- Ready to integrate with Streamlit dashboard

## Getting Started
1. Install requirements: `pip install -r requirements.txt`
2. Run scraper: `python cli/run_scraper.py --role "data scientist" --pages 3`
3. Check saved data in SQLite or CSV
