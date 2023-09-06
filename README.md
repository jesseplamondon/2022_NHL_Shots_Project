# 2022_NHL_Shots_Project
- In this project I created a model of the quality of all shots taken in the 2022-23 NHL regular season and determined, for each goalie, their save percentage above the average for each shot quality (sq).
- From these Save Percentages Above Average per Shot Quality (SPAAsq) I determined each goalies Goals Saved Above Average (GSAA) per shot quality group, and from there, their overall GSAA; the result has been output to "goalies_GSAA.csv". This csv file can be used to precisely determine the value each goalie brings to their team, as well as if the goalies' value is being propped up by low percentage shots resulting from strong defensive play/structure by their teammates. This data can additionally used to determine the best shot locations against opposition goaltenders, as well as areas of improvement/emphasis for goalies/team defensive structures.
- Based on this model, the function "get_GSAR_by_names(df, averages, name1, name2)" returns the GSAA of the goalie with name2 over the goalie with name1, based on the exact shots that goalie1 faced in the season (i.e. GSAA if goalie1 were replaced with goalie2).
- By using the get_goalie_SPAAsq (to determine specific save percentages in shot quality areas without involving shot volumes) and get_all_GSAA (to evaluate goalie performance based on all of the shots faced in the season) the model gives a variety of tools for evaluating the plethora of factors that affect goalie performance and determining the impact of each goalie on their team's success.
- Additionally, a test has been conducted by replacing comparing the performance of Brian Elliott on the shots faced by Andrei Vasilevskiy.
