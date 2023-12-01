# PredictingMinorityVotingTurnout
A method for looking at past voting turn out of minorities in order to predict future voting trends, and in what areas to increase voting education and outreach.

This project takes data from the US Census (https://www.census.gov/topics/public-sector/voting/data/tables.2022.List_1863097513.html#list-tab-List_1863097513) to look at how minorities voted in each state. 

The cleanData.py was used to merge and clean data from the census tables. 

The Main.py script was used to run the multi-class logistic regression, and create a graph showing the ten current worst state and race voting turnout, along with predicting what will change in 2025. This is in the hopes that voting outreach techniques could be implemented in areas with poor prognoses.  
