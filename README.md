# Most Valuable Player (MVP) for a Season - CMPE 138 Group 14

## Abstract
This project aims to analyze the `ncaa_basketball` dataset from the BigQuery public data repository to identify the Most Valuable Player (MVP) for a season. By leveraging knowledge of complex queries and analytics techniques, we will extract valuable insights from the data to determine which player contributed the most to their team's success.

The dataset involves multiple tables, including:
- `mbb_games_sr`
- `mbb_teams_sr`
- `mbb_players_games_sr`

These tables contain detailed information about tournaments, games, players, and statistics. The project will focus on preprocessing the data, cleaning it to ensure quality, and analyzing it using a scoring algorithm based on key player attributes such as points (2 pointers, 3 pointers), fouls, blocks, and other game statistics. Our ultimate goal is to identify and validate the Most Valuable Player for the tournament season.

## Project Steps
1. **Data Exploration & Selection**: We will explore the `ncaa_basketball` dataset from BigQuery to identify the most relevant tables for our analysis.
2. **Preprocessing & Cleaning**: Using SQL queries, we'll clean the dataset, handling missing data, removing outliers, and standardizing data formats.
3. **Algorithm Design**: A custom algorithm will be designed to score players based on various statistics like points, fouls, and blocks. This score will determine the MVP for each team and the overall season.
4. **MVP Selection**: Using the designed scoring algorithm, we'll select the MVP for each team and the overall season by analyzing game statistics across the season.

## Methodology
- **Data Preprocessing**: Handle missing values, standardize data formats, and remove irrelevant or inconsistent data points.
- **Algorithm Design**: Evaluate player performance using different attributes like points, fouls, and blocks.
- **Query Optimization**: Optimize complex queries for faster data processing and analysis.

## Findings and Presentation
The final deliverable will be a comprehensive report detailing the methodology, analysis, and results. The project will highlight the algorithm used to score players and the selection of the MVP. Additionally, it will include recommendations for future improvements in data analysis for sports datasets.

## Weekly Schedule
| Week        | Activity                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------|
| **03/4 - 10/4** | - Explore the datasets from the BigQuery public data repository.                           |
|             | - Brainstorm and finalize project ideas based on the dataset.                                 |
| **11/4 - 17/4** | - ERD creation and algorithm design to score players.                                      |
|             | - Create queries for data preprocessing and cleaning.                                         |
| **18/4 - 24/4** | - Write queries to select the MVP for each team based on the algorithm.                    |
|             | - Query optimization and performance improvement documentation.                               |
| **25/4 - 02/05** | - Complete the final report.                                                              |
|             | - Prepare for the final project presentation.                                                 |

## Dataset
- The dataset used in this project comes from the `bigquery-public-data` repository, specifically focusing on the `ncaa_basketball` dataset, which provides detailed data on NCAA basketball games, teams, and player statistics.

## Tools and Technologies
- **BigQuery** for data access and SQL queries.
- **SQL** for data preprocessing, analysis, and MVP selection.
- **Analytics Techniques** for scoring and ranking players.

## Conclusion
This project demonstrates the use of data analytics to identify the Most Valuable Player (MVP) for a basketball season. Through the careful selection and analysis of NCAA basketball data, we aim to highlight the player's performance using well-defined metrics and statistical analysis.

## License
This project is part of the CMPE 138 course and is intended for academic purposes.