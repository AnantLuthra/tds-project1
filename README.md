# GitHub Users in Berlin

This repository contains data about GitHub users in Berlin with over 200 followers and their repositories.

## Files

1. `users.csv`: Contains information about 609 GitHub users in Berlin with over 200 followers
2. `repositories.csv`: Contains information about 60853 public repositories from these users
3. `data_scraping.py`: Python script to fetch user data from GitHub API
4. `analysis.zip`: Contains the python files for the analysis.

## Data Collection

- Data collected using GitHub API
- Date of collection: 2024-10-29
- Only included users with 200+ followers
- Up to 500 most recently pushed repositories per user

## 3 Insight Points
- Fetch user data from GitHub API, filter by location 'Berlin', and clean the data.
- Append cleaned user data to a list and increment the page number for pagination.
- Return the list of users after fetching and cleaning data from multiple pages.
