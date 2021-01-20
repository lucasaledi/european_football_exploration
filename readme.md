# European Soccer Database Exploration
## by Lucas Aledi

# Dataset Overview
This is the second project of the Data Analyst Nanodegree on Udacity. This time, we have been asked to investigate a dataset of our choosing from a previously selected list. For this project, I have chosen to look into a [soccer database which can be found on Kaggle](https://www.kaggle.com/hugomathien/soccer) and is well suited for data analysis and machine learning. It contains information on +25,000 matches, +10,000 players, 11 European Countries with their lead championship from seasons 2008 to 2016, players and teams' attributes sourced from EA Sports' FIFA video game series, including the weekly updates, team line up with squad formation (X, Y coordinates), betting odds from up to 10 providers, detailed match events (goal types, possession, corner, cross, fouls, cards etc…) for +10,000 matches.


# Summary of findings
After reviewing the information available in this analysis, one could come to the following conclusions:

* 1\. Except for the Scotland Premier League and the Switzerland Super League (which have had 12 and 10 teams, respectively), the majority of leagues range from 16 to 20 teams per season;
* 2\. Spain Liga BBVA is the one with the most goals scored (8412 goals over 8 seasons), but Netherlands Eredivisie takes the lead when it comes to the average number of goals scored per match (3.1).
* 3\. Teams playing at home tend to, on average, score more goals than those playing away. And, on this matter, Real Madrid CF and FC Barcelona cap the top teams in terms of goals scored home and away, respectively.
* 4\. Specifically about Spain Liga BBVA, it seems that the number of victories, defeats and goals difference are more closely related to the number of points scored at the end of any given season, as one would expect.
* 5\. Still specifically about Spain Liga BBVA, it is important to highlight the existence of 3 teams which stand-out of the crowd (FC Barcelona, Real Madrid FC and Atlético Madrid) and that, it seems that they cause some distortion on the correlation coefficient of different pairs of variables. For instance:
    * 5.1. Home victories ($r_{w}= 0.92$ and $r_{w/o}= 0.83$) seem to be more closely related to points than away victories ($r_{w}= 0.9$ and $r_{w/o}= 0.71$).
    * 5.2. Without the ouliers, being defeated at home ($r_{w}= -0.81$ and $r_{w/o}= -0.72$) seems to affect more a team's overall performance when compared with away losses ($r_{w}= -0.86$ and $r_{w/o}= -0.67$), and draws ($r_{w}= -0.46$ and $r_{w/o}= -0.15$) have a weak, negative relationship with points.
* 6\. *Atlético Madrid* (21 points difference) is the team that improved the most over the years in terms of points scored by the end of the season.

# Key Insights for Presentation
A presentation for this project has not yet been made. We'll look into it after further investigating the database for some ML models.


# Credits
github.com/lucasaledi

udacity.com
