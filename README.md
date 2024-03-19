# Welcome to the Golf Predictor Project

**Video Demo: https://youtu.be/KwKQHAUoarQ 

**Here is a high level overview of our project:**

**Our big question**
* Can we accurately predict the winner of an upcoming tournament? Can we see how much money we would have won if we used our model to place bets on winner, top 5 and top 10 finishers?

**Storage**:
* The data is stored in a downloadable CSV file that we transfered to Github so it can be accessed directly from a link. It was accessed from Kaggle.com

* We will use almost all of the elements from the CSV file that pertain to how a player played on a course and certain factors such as which tournament and weather, but will omit irrelevant data such as unnamed columns.


**Cleaning**
* The first dataset is very complete however it will need to be modified to fit the regression model such as using dummies for categorical variables and shaving off extreme outliers. Otherwise, the dataset is in a good format, as it is in a csv file that is comma separated.


**Integration**
* We have multiple sources of data, so we will need to integrate the data. In order to do this, we plan to match the player/date/tournaments so that we can have all of the data from a given match.
* In order to match find difficulty, we will have to match the player data set to the course dataset and evaluate based on given factors


**Analysis**
* With the data, we plan to set up a regression model that can use the data we have to make a prediction about who will win upcoming tournaments, and see if its a good model to use to betting predictions.


**Communication**
We will communicate our findings with pandas DataFrames and Matplotlib to plot our data findings
