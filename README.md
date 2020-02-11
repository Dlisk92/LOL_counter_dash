# LOL_counter_dash

## I gather the data used in this project from kaggle.com

It is data from ranked League of Legends games from season 4-8.
It has a ton of daata from each game for each player(10 players total). 
Most of the data isn't usable for predictive purposes however as you wont know things such as gold earned and items bought before a game.

## Modeling 

After running xgboost and logit using just teams champion picks it became apparent that either the game is very balanced  or just hard to model as the models proforamce was not good.

## How then can I get some use out of this data?

Lets try to build something useful. I can tell people which picks counter there opponent in lane.
