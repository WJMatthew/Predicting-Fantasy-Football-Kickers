# Predicting Fantasy Football Kickers

[Work in progress]

Choosing the right kickers in fantasy football can be the key to winning a league but they are notoriously hard to predict. Kickers score points by kicking PATs and field goals, obtaining 1 point for PATs and 3-5pts per FG depending on the distance.
FG <=39yds : 3pts, 40yds<= FG <= 49yds : 4pts, FG >= 50yds : 5pts.

Clearly having a kicker that can kick long FGs is beneficial but having a high powered offense and facing a mediocre defense can have just as much of an effect. Some people also prefer kickers that play in domed stadiums so weather does not come into play.

In this project I combined data from three sources to analyze correlations and make predictions: 

1. NFL game data - Here I calculated the game and kicker statistics along with moving averages.
2. Vegas odds data - I compiled Over/Under and money line odds for games.
3. Weather data - I also added weather data for games up to and including the 2013 season.

I chose a 5 game rolling window to calculate averages for numeric values to use in the model.
