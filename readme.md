# Premier League Dataset Explanatory
## by Omar Farouk


## Dataset

> The dataset contains data and stats about Priemer League matches stats from 2011 to 2019. it has 3327 matches, each row describe a match's stats like the two teams(Home, Away) score, the winner, the number of attendance in the stadium, also ball possession number of shots and passes for each team in the match.<br>
This shape of the dataset is good for some kinds of visualization about the result and comparing bewteen the wins of home and away teams. But, there are columns describe the same features as home_shots and away_shots, so we need to make new dataframe in an efficient way.

- The First Shape for the dataset
> There are 3327 matches from the Premier League matches from 2011 to 2019, it has 22 feature which are season, match week, stadium, attendance, home_team, away_team and also the scored goals, shots , passes, yellow and red cards for each team (home and Away) in the match, most of features are numeric, but features as season, stadium, home_team, away_team and result are categorical.

- The modified Shape for the datatset
> This dataset has twice the number of rows of the first shape dataset, because every match was splitted into two rows, each row describe the stats of one oof two teams (Home / Away), but it has less columns. It has 6654 rows, each columns will be described below.
- Columns:
    1. season: The year of the season. {Categorical}
    2. match_week: The match week number. {Numeric}
    3. stadium: The name of the stadium where the match was played in. {Categorical}
    4. attendance: The number of fans attended the match at the stadium. {Numeric}
    5. team: Name of the team. {Categorical}
    6. result: The result of the match realative to the team (win, lose, tie). {Categorical}
    7. scored: The number of goals to the mentioned team. {Numeric}
    8. shots: The number of shots of the mentioned team. {Numeric}
    9. shots_on: The number of shots on target of the mentioned team. {Numeric}
    10. posse: The percentange of ball possession of the mentrioned team. {Numeric}
    11. passes: The number of passes in the match related to the mentioned team. {Numeric}
    12. yellows:  The number of yellow cards to the montioned team. {Numeric}
    13. reds: The number of red cards to the montioned team. {Numeric}
    14. team_hospitality: it Tells that the match is Home or Away to the mentioned team at team column. {Categorical}

**To download the data, here is the <a href='https://github.com/jokecamp/FootballData/tree/master/EPL%202011-2019'>Source</a> of the data.**

## Summary of Findings

> Summarize all of your findings from your exploration here, whether you plan on bringing them into your explanatory presentation or not.


## Key Insights for Presentation

> Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.
