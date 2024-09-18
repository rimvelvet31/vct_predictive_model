# Valorant Champions Tour Predictive Model

![cover image](cover.jpg)

# Problem Framing

To develop a predictive model that forecasts the outcomes of sports events or gaming matches
based on historical data, player statistics, and other relevant factors. The model can be used to
inform betting strategies and improve user engagement on the platform.

- The project will be scoped to VALORANT, particularly its esports matches (VCT)
- Data is ranges from the years 2021 to 2024
- The predictive model will be primarily focused on predicting the outcomes (win/loss) of individual games (by map)
- Optionally, the model could also predict the scoreboard of the game (high-risk bets)
- To simulate a betting environment, the model will be used to predict the game outcomes from Champions 2024 matches

# Data Collection

The dataset used in this project was the [Valorant Champion Tour 2021-2024 Data](https://www.kaggle.com/datasets/ryanluong1/valorant-champion-tour-2021-2023-data/data), which was sourced from Kaggle and created by Ryan Luong. We chose this dataset because it included the most comprehensive statistics we found that are crucial for predictive analytics.

The dataset includes matches, agents, and player data from VCT 2021–2024. This was obtained via data scraping from [vlr.gg](https://www.vlr.gg/). Each year contains four folders: `agents`, `matches`, `player_stats`, and `ids`.

The `agents` folder contains agent pick rates, map pick rates, attacker and defender side win/loss percentage, team pick rates on an agent, and win/loss rate.

The `matches folder` contains team picks and bans, their economy on each round of a match, their economy stats on a match, players kills performance on other players, players kill stats, maps that were played on a match, the scores from the map, players overview stats, a player kills performance on players and their agent on a specific round, matches scores and their results, a list of abbreviated team names with their full names, the count of the method that occurred for a team for a match they played and its round number.

The `player_stats` folder only contains player stats.

The `ids` folder contains the ids for the teams, players, tournaments, stages, match types, matches, and games.

The `all_ids` folder contains all the IDs, and the abbreviated team name with their full name.
