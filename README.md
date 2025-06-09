# QSS 20 Final Project

**Group Members:** Evan McDermid, Paul Waxman 

## Project Overview

We are analyzing the correlation between Philadelphia crime incidents and Philadelphia Eagles football game results.

The questions we want to answer:

- How do Philadelphia Eagles games impact crime rates before, during, and after games?
- Do domestic abuse reports change around wins and/or losses?
- How do yearly crime rates correlate with the team’s success?
- Is this impact unique to Philadelphia? How does it compare to:
  - Other sports (e.g., Philadelphia 76ers)
  - Other cities (e.g., Chicago Bears)
- Where in the city does crime occur in relation to game outcomes?
- What types of crimes (e.g., domestic abuse, arson, assault) are most affected?


## Related Work

We draw inspiration from [Football, Alcohol, and Domestic Abuse](https://www.sciencedirect.com/science/article/pii/S004727272300213X)

We also used data from this study [Sports Viewership In Philadelphia](https://d101vc9winf8ln.cloudfront.net/documents/49536/original/Sports_Viewership_in_the_Philadelphia-Camden-Wilmington__PA-NJ-DE-MD_Metropolitan_Area.pdf?1714499267)

## Notebook Descpritions 

- [Functions File](https://github.com/pwax1120/mcdermid_waxman_final_project/blob/main/code/utils.ipynb) - contains import statements and functions to be called on in the other notebooks
- [0 - Eagles Game Day Analysis](https://github.com/pwax1120/mcdermid_waxman_final_project/blob/main/code/00_eagles_gameday_analysis.ipynb) - Inputs: Years, Kaggle Eagles Game Data, Philadelphia crime data and Stadium Coordinates. Function: cleans the data, filters it to home games and correct time window, calculates the crime delta by distance. Output: Bar Graph that compares the crime deltas by distance. 
- [1 - Bears Game Day Analysis](https://github.com/pwax1120/mcdermid_waxman_final_project/blob/main/code/01_bears_gameday_analysis.ipynb) - Inputs: Chicago Crime Data, Kaggle Bears Data, Stadium Coordinates. Function: cleans the data, filters it to home games and correct time window, calculates the crime delta by distance. Output: Bar Graph that compares the crime deltas by distance. 
- [2 - 76ers Game Day Analysis](https://github.com/pwax1120/mcdermid_waxman_final_project/blob/main/code/02_sixers_gameday_analysis.ipynb) - Inputs: Years, Kaggle 76ers Game Data, Philadelphia crime data and Stadium Coordinates. Function: cleans the data, filters it to home games and correct time window, calculates the crime delta by distance. Output: Bar Graph that compares the crime deltas by distance. 
- [3 - Philadelphia Case Studies](https://github.com/pwax1120/mcdermid_waxman_final_project/blob/main/code/03_philly_casestudies.ipynb) - Inputs: Philadelphia Crime Data, Dates of selected events. Function: Calculates the crime deltas from normal on the day of the event chosen and the next day. Output: Table containing the results for Philadelphia
- [4 - Chicago Case Studies](https://github.com/pwax1120/mcdermid_waxman_final_project/blob/main/code/04_chicago_casestudies.ipynb) - Inputs: Chicago Crime Data, Dates of selected events. Function: Calculates the crime deltas from normal on the day of the event chosen and the next day. Output: Table containing the results for Chicago
- [5 - Win/Loss Analysis](https://github.com/pwax1120/mcdermid_waxman_final_project/blob/main/code/05_win_loss_analysis.ipynb) - Inputs: Preproccessed Crime Data, Kaggle Data Set. Function: Tags the games as wins or losses, calculates crime data for wins vs. losses and then run's a t-test on them. Output: Bar graph showing the average and deviations, and a T-test value. 

  
