# CST383_SportsData

* Nick Anderson
* Oscar Ochoa
* Juan Duarte

## Intro
-Football is one of the most popular sports worldwide, that generates a vast amount of interest in betting and selecting winning teams. We will make predictions of which teams will win based on data from previous games results and data.

### Data Description, Preciction Goals, Features as Predictors
Data Description:
The dataset we are using contains information for the National football League’s bettings odds from 1979 up until 2013. The information in this dataset was collected from websites such as ESPN, NFL, Pro Football reference, while the weather information was collected from NOAA. Some of the information in this dataset includes columns with team scores, the location of the game, the style of the stadium, the weather during game day, and stadium capacity. The information contained in this dataset can help analyze trends to develop better betting strategies. We plan to add more features to the existing features. We can add win and loss columns based on the team’s scores.

Prediction Goals:
Using our dataset we aim to build a predictive system for NFL games, this system will estimate the probability of winning or losing between two NFL teams when they face off. We will analyze historical performance, so our model can provide valuable insights into game outcomes.

Features as Predictors:
Our predictive system will use several features to enhance accuracy. We’ll use team scores along with wins and losses , which will provide an overall record for each team. Additionally, we’ll analyze wins against other teams, which will take into consideration the performance between different opponents. Also, we’ll explore the relationship between team wins at home versus away games, along with the weather of the stadium where the games are played. These features together will create great predictors.

Data Sets From [NFL scores and betting data](https://www.kaggle.com/datasets/tobycrabtree/nfl-scores-and-betting-data)

## Outcome

## Best model
### Decision Tree
Our best model was the Decision Tree model
With a test score of 67.36% and a train score of 68.89%
After tuninig our model this was the best accuracy we were able to achieve
### Suggestions
Adding more features to our predictors could've helped with our predictions
More data was needed other than just historical data to predict outcomes of matches
It is possible to predict whether a team is going to win, but there are many other factors not present in our data the could potentially allow us to create a better model.
Some could be injuries, more weather data ie. rain, fog, and humidity, amount of starters playing, and coach information
Overall we concluded that with the data we chose it would've been more suitable for a linear regression problem predicting how much points a team was going to score.
