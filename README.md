# GitHub Users in Boston

- Using GitHub API, data on users in Boston with 100+ followers and their repositories were collected.
- Analyzed repositories to find surprising trends in programming languages and popularity metrics.
- Suggested developers consider audience engagement factors when designing repositories.

## Files

1. `users.csv`: Contains information about 471 GitHub users in Boston with over 100 followers
2. `repositories.csv`: Contains information about 42747 public repositories from these users
3. `gitscrap.py`: Python script used to collect this data

## Data Collection

- Data collected using GitHub API
- Date of collection: 2024-10-31
- Only included users with 100+ followers
- Up to 500 most recently pushed repositories per user
