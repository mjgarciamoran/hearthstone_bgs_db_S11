# Hearthstone Battlegrounds Leaderboard Database - Season 11 - 08/2025

Hearthstone is an online card game developed by Blizzard Entertainment.  
Data related to player rating is publicly published in public leaderboards on their website. There's an API to access it.
Players and their rankings are distributed between two gamemodes and three regions.
Data is fetched every 6 minutes for each combination of gamemode and region.

In each database file there's a table for each day, where each row represents a different player and each row a different fetching instance (i.e. every 6 minutes).

Early days of the database are missing due to my own incompetence.

## Previews

Here are some previews to showcase the information inside the dataset. All of them for the "US" region, "bgs" gamemode leaderboard. They show data for the 5 top players for the first 7 days.  

### Raw csv
This is taken from the first day 250824.  
![Raw csv](./previews/pics/inputdataexample.png)  
[View the preview](./previews/USbgs_inputdataexample.csv)  

### Daily record
![Daily record](./previews/pics/recordpreview.png)  
[View the preview](./previews/USbgs_recordpreview.csv)  

### Daily total
![Daily total](./previews/pics/sumpreview.png)  
[View the preview](./previews/USbgs_sumpreview.csv)  

## Considerations
- Early days of the database are missing due to my own incompetence.
- Season 11 corresponds to season 16 internally in Hearthstone's API.
