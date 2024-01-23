# A Statistical Analysis of the FIFA World Cup 2022 Player Data

## Project Overview: 
This project focuses on using Python, the unidecode module and the pandas Data Analysis library to explore and analyse player data from the World Cup 2022, aiming to answer the following questions:

- Who scored the most goals?
- Who got the most assists?
- Who got the most goals and assists combined?
- Who was the player with the most goals and assists per 90 minutes?
- Who played the most minutes?
- Who were the youngest and oldest players?
- Who were the youngest and oldest players to score?
- Who was the most red carded player?
- What country scored the most goals?

The project code and results are contained in the Jupyter Notebook `fifa-world-cup-2022-analysis.ipynb`, with a summary of the conclusions below.

## Data: 
The data used in this project is spread across two CSV files stored in the `datasets` directory:
- `player_stats.csv` contains match results for over 44,000 international football matches
- `fifa_wc_2022_player_stats.csv` contains the results of matches that ended in penalty shootouts

Credit: Both datasets can be obtained from Kaggle using the following links
- https://www.kaggle.com/datasets/swaptr/fifa-world-cup-2022-player-data/datainternational-football-results-from-1872-to-2017
- https://www.kaggle.com/datasets/rhugvedbhojane/fifa-world-cup-2022-players-statistics/data

Thank you to the authors of these datasets for making this data available to the public domain.

## Conclusion: 
In summary, this project provides valuable insights into the performances of players during the last World Cup. Here are the key findings from the analysis:
- The highest scorer was Kylian Mbappé (8 goals)
- The best playmaker was Bruno Fernandes (0.758 assists per 90 minutes)
- The player with the most goals and assist was tied between Lionel Messi and Kylian Mbappé (10 goals and assists)
- The player with the most goals and assists per 90 minutes was Hattan Bahebri (22.5 goals and assists per 90 minutes)
- The player with the most minutes played was tied between Emiliano Martínez, Dominik Livaković, Nicolás Otamendi, Lionel Messi and Joško Gvardiol (690 minutes)
- The youngest and oldest players were Youssoufa Moukoko and Atiba Hutchinson, respectively (18 years and 28 days, 39 years and 313 days respectively)
- The youngest and oldest players to score were Gavi and Pepe (18 years and 110 days, 39 years and 283 days, respectively)
- The most red carded player was Walid Cheddira (1.406 red cards per 90 minutes)
- France was the highest scoring country (17 goals)

## Python Version and Library Dependencies
- Python (3.11.5)
- pandas==2.1.4
- unidecode==1.3.8