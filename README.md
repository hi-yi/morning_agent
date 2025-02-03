# morning_agent

## Purpose
### To stay informed with AI trend


## Steps
### 1. Extract news contents published yesterday
1) Filter out only credible news providers
- Among all news providers in news api, filter out only factual reporting, high credible, and high traffic generating news
- Crawl credibility data for each news website


2) Extract news contents from news api
- Title, url, description, content relating AI in U.S published yesterday


### 2. Summarize news using LLM
- Based on news extracted (around 100), group similar contents and summarize them
- Enable to check all contents if needed by providing representative url
