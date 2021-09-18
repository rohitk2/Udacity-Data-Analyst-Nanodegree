# NBA Data Visualization Project by Rohit Kumar

# Project Details
This project was done as a part of Udacity's Data Analyst Nanodegree. The purpose of this project was use python to explore a dataset. The analysis begins with single variable analysis, bivariate and then multivariate.

Following the presentation is a presentation showing the important findings using explanatory data analysis. A slide deck was also prepared.

# Dataset
This is a dataset I pulled from an NBA API. Here is the source code: https://github.com/swar/nba_api

Each entry is the overall performance of a team in the last 30 years. The statistics go from 1990-2019 seasons. There are 906 obsevations in the dataset with 17 features. Most variables are numeric in nature, but the variables there are 2 qualitative variables (TEAM_NAME and NBA_FINALS_APPEARANCE). For more details on how I pulled this I included the actual code in 'NBA Data Gathering.ipynb'. 

# Summary of Findings
The questions I explored were:
-Which statistics are important and which statistics are not important when it comes to winning?
-Which teams have NBA Finals appearances in the last 30 years and how many?
-Which teams have dominated each decade (win percentage and titles)?
-What are some of the surprise winners in the NBA Finals (underdogs who won the conference title or NBA Championship)?

- statistics with strong correlation with win percentage: field goal percentage
- statistics with moderate correlation with win percentage: defensive rebounds, turnovers, points scored, rebounds, personal fouls, and blocks
- statistics with weak correlation with win percentage: Free Throw percentage, offensive rebounds and defensive rebounds
- Lakers, Bulls and Spurs were the main dominators in last 30 years with 6 rings, 6 rings and 5 rings respectively. 
- 17 other teams besides those 3 made finals (8 of which won atleast 1 time)
- bulls dominated in the 90's with 6 rings
- Lakers and Spurs dominated in early 2000s with 4 and 3 rings respectively
- the last decade had the most turnover, with 7 different teams winning titles (3 rings won by Warriors)
- teams with the highest consistent win percentage by decade were:
        - 90s: Trail Blazers, Suns, Bulls, Thunder, and Jazz
        - early 2000s: Pistons, Suns, Lakers, Mavericks, and Spurs
        - last decade: Heat, Warrior, Thunders, Clippers and Spurs
- some surprising NBA finals winners were 2005 Heat and 1994 Rockets
- some surprise NBA Conference Winners were 1998 Knicks, 2002 Nets, 2019 Heat, 2009 Celtics, 2001 Nets and the Cavaliers (2006, 2014, 2016, and 2017)

# Key Insights for Presentation
The plots included bar graphs, a table and scatterplot with correlation lines to highlight all the different findings. For more details you can view the presentation.
