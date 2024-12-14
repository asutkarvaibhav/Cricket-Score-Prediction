# Cricket-Score-Prediction



This project aims to predict the final score of T20 cricket matches based on various features such as batting team, bowling team, city, current run rate, wickets left, and more. The dataset used contains historical T20 match data, and various machine learning models were employed to make predictions.

***Dataset***
The dataset used in this project is the T20I Cricket Dataset, which contains information about several T20 cricket matches. The columns include:

* battingTeam: The team that is batting.
* bowlingTeam: The team that is bowling.
* city: The city where the match was played.
* score: The score achieved by the batting team.
* CurrentRunRate: The current run rate during the match.
* wicketsLeft: The number of wickets left for the batting team.
* Run_In_Last5: The runs scored in the last 5 overs.
* Wickets_In_Last5: The number of wickets lost in the last 5 overs.
* innings: The innings of the match (1 or 2).
* Final_Score: The target final score that needs to be predicted.
  

***Features***

* Data Preprocessing: Handled missing values, duplicates, and outliers.
* Exploratory Data Analysis (EDA): Visualized categorical and continuous variables to understand trends and patterns.
  
Modeling: Implemented several models including:
* Linear Regression
* Random Forest Regressor
* Support Vector Regressor (SVR)
* XGBoost

***Key Insights***

* Most matches were played in Dubai and Colombo.
* India and England had the highest batting team scores.
* Zimbabwe's bowling team had the highest average score allowed.
* Random Forest and XGBoost performed the best with accuracy scores of 0.86 and 0.91, respectively.
