# LahmansBaseball
Connects to an SQL database file and queries for all players who have played at least 50 games and are still active. 
Converts the data into either an R data frame or a pandas data frame. Adds a calculated column with the player’s age and a calculated column with each player’s first and last name concatenated. 
Deletes any rows with missing values.

Answers the following question:
Which active player had the most runs batted in (“RBI” from the Batting table) from 2015-2018? How many double plays did Albert Pujols ground into (“GIDP” from Batting table) in 2016?
