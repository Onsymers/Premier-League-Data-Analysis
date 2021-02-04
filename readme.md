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

**To download the data, here is the <a href='https://github.com/jokecamp/FootballData/tree/master/EPL%202011-2019'>Source</a>.**

## Summary of Findings

> The dataset is rich with alot of usefull data about Premier League matches. it is noticed that percentage of teams that played the match at home stadium and won is **45.5%**, and for lost home teams is **30.3%**(the rest of percentange is about Tie -24.2%-), the distribution for goals scored for each teams in a match is condensed in range between 0 to 3 goals. There are alot of sparks in attendance of fans distribution,  The predicted number of shots to a team in a match is between 8 to 16 shots, and for the number of shots on target of course the number is lower than the all shots, it is between 2 and 7 shots on target. The number of passes for a team in a match is condensed between 300 and 500. There are a strong relation between the ball possession and number of passes, also between ball possession and number of shots. The difference between means of ball possession to the result (win, tie, lose) is very small but the ball largest mean is for the winning team, the same case for numbr of shots and passes. About the mean of shots through the season from 2011/12 to 2019/20 decreased, there is not a large difference between year and the next year, but at season 2011/12 the mean of shots is 14.25 for a team in the match, but at season 2019/20 the mean is 12.5. it is not a big differnce but it is a good point to investigate in. The comparison between number of passes and the number of shots for the winning team and the losing team, describes that the wining team have chance to have more passes and shots.



## Key Insights for Presentation

> When you are looking to the stats of the match, you can ask yourself many questions like does the stats really matter? or does any of the stats affect the result of the match?. this what will be investigated in the presentation.