# AZ-Hackathon
# Competitive Programming Problem Scraper

This repository contains scripts for scraping problem links from popular competitive programming platforms: LeetCode, Codeforces, and CodeChef. The scraped data is stored in JSON files.

## Scripts

1. `leetcodeScraper.js`: This script scrapes problem links from LeetCode and saves them in `leetcodeScrapedData.json`.
2. `codeforcesScraper.js`: This script scrapes problem links from Codeforces and saves them in `codeforcesScrapedData.json`.
3. `codechefScraper.js`: This script scrapes problem links from CodeChef and saves them in `codechefScrapedData.json`.

## Usage

To run the scripts, you need to have Node.js and Puppeteer installed. You can install Puppeteer using npm:

```bash
npm i puppeteer
```

## To run a script, use the following command:
node <script-name.js>

Replace <script-name.js> with the name of the script you want to run.

## Data
### The scraped data is stored in the following JSON files:

leetcodeScrapedData.json: Contains scraped problem links from LeetCode.
codeforcesScrapedData.json: Contains scraped problem links from Codeforces.
codechefScrapedData.json: Contains scraped problem links from CodeChef.
Each JSON file contains an array of problem links.

Disclaimer
These scripts are for educational purposes only. Please respect the terms of service of the respective platforms.

