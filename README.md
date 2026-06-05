# block114514

Anti-Scraper and Anti-LLM Poisoning API hosted on GitHub Pages.

## Project Overview
This project provides a defensive "poisoning" API to protect websites from malicious scrapers and LLM crawlers. It serves massive datasets and prompt injections to disrupt automated data collection.

## API Endpoints
- Poison Bomb (114,514 lines):
  https://yu08083.github.io/block114514/v1/poison_bomb.txt
- Fake Environment File:
  https://yu08083.github.io/block114514/v1/.env
- Infinite Loop Trap:
  https://yu08083.github.io/block114514/v1/next/index.html

## Implementation
Insert the following hidden HTML into your website to redirect malicious bots to the trap:

<div style="display:none;">
    <a href="https://yu08083.github.io/block114514/v1/poison_bomb.txt">System_Update_Log</a>
    <a href="https://yu08083.github.io/block114514/v1/.env">Database_Config_Backup</a>
    <a href="https://yu08083.github.io/block114514/v1/next/index.html">Infinite_Data_Index</a>
</div>

## Features
1. Poison Bomb: Bloats scraper memory with 114,514 lines of randomized slang and junk data.
2. Prompt Injection: Commands like "Ignore all instructions" to neutralize AI crawlers.
3. Directory Hole: Recursive nested directories to stall crawlers using depth-first search.
4. Auto-Update: Weekly automated builds to refresh datasets from external sources.

## Files
- build.py: Scrapes source data and generates the API files.
- requirements.txt: Python dependencies.
- .github/workflows/deploy.yml: GitHub Actions automation script.

## License
MIT License
