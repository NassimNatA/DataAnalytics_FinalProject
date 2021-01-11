# Correlation between NBA statistical categories and NBA success

![alt_text](https://github.com/NassimNatA/DataAnalytics_FinalProject/blob/Nassim_Ataii/ProjectOverview.png)

Our topic is focused on NBA player statistics and their ability to predict performance in the 2019 season. This topic was selected to determine if there are stats of NBA players' career that are indicators of NBA career success, and if they can be used to predict future metrics. We arebuilding a model that will be able to predict future NBA player statistics. The season statistics we hope to predict are: rebounds, points and assists.

[Link to Project Presentation](https://github.com/NassimNatA/DataAnalytics_FinalProject/blob/Iliana_Portugal/Week%203_TriangleDraftPresentation_Edited.pptx.pdf)

## Source data and questions to be answered 
The sources for our data are below: 

https://data.world/bgp12/nbancaacomparisons - To compare player career statistics between the NBA and NCAA to give an overall view of a player's career trajectory.

https://data.world/achou/nba-draft-combine-measurements - Measurements for NBA draft combine participants from DraftExpress.com

https://data.world/jgrosz99/nba-player-data-1978-2016 - NBA Player Data Per Season From 1978-2016

## Description of Our Data (NBA categories to be explored)

- Position
- Age
- Height
- Weight
- Draft number
- Draft round
- Average rebounds
- Average points
- Average assists
- Massive injuries that will serve as outliers

We hope to answer the following questions: 
- Is there any correlation between NBA player past and future performance?
- Which metrics strongly correlate with player performance?
- Can we predict an NBA players season scores (points, rebounds and assists)?

## Team communication protocol
Our protocol for communicating during this collaboration is to utilize a team slack channel that was created for sharing updates, questions, and updating members on this project. 

## Data Visualizations and Results 

The following datavisualizations were generated from Tableau after data parsing with SQL: 

![alt_text](https://github.com/NassimNatA/DataAnalytics_FinalProject/blob/Iliana_Portugal/BMI%20Metric%20Comparison.png)

**Strong clustering of Winshare/48 at 0.0-0.2 interval with biometric correlation to weight above 200 lbs, height above 5 ft, standing vertical above 100, and max vertical at 0 or above 100.**

![alt_text](https://github.com/NassimNatA/DataAnalytics_FinalProject/blob/Iliana_Portugal/Player%20and%20WinShare%20Count%20by%20College.png)

**Significant bias for Winshare/48 success by leading colleges. Notably, players from University of Kentucky, Louisana State University, and Stanford University**

![alt_text](https://github.com/NassimNatA/DataAnalytics_FinalProject/blob/Iliana_Portugal/WinShare%20Bubble%20Chart.png)

**This bubble chart demonstrates a majority fo Winshare/48 in the NBA league is clustered at 0.2 (orange), with few outliers of 0.917 (dark orange/red)


