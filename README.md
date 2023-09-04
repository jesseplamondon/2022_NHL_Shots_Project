# 2022_NHL_Shots_Project
In this project I created a model of the quality of all shots taken in the 2022-23 NHL regular season and determined, for each goalie, their save percentage above the average for each shot quality (sq).
From these Save Percentages Above Average per Shot Quality (SPAAsq) I determined each goalies Goals Saved Above Average (GSAA) per shot quality group, and from there, their overall GSAA; the result has been output to "goalies_GSAA.csv".
Based on this model, the function "get_GSAR_by_names(df, averages, name1, name2)" returns the GSAA of the goalie with name2 over the goalie with name1, based on the shots that goalie1 faced in the season (i.e. GSAA if goalie1 were replaced with goalie2).
Additionally, a test has been conducted by replacing Brian Elliott with Jonas Johansson, and an analysis is described in the jupyter document.
