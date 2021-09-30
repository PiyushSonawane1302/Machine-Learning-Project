
![](https://i.pinimg.com/564x/f3/d1/22/f3d122cabf32e379906a7fbfab3ab224.jpg)
  
# First Inning IPL Score Prediction

 • Created a model that predicts the score (in terms of range)
  of IPL matches.

## Resources Used

* Dataset by Kaggle 
* [Dataset Download Link](https://www.kaggle.com/yuvrajdagur/ipl-dataset-season-2008-to-2017)


### Libraries Used 

* pandas
* numpy
* sklearn
* seaborn

### Tested Models

* Linear Regression
* Decision Tree Regressor
* Random Forest Regression


## Demo

* Give name for Batting team 
`batting_team = 'Mumbai Indians'`
* Give name for Batting team 
`bowling_team = 'Kings XI Punjab'`
* Then use the method Predict Score
* Parameters (batting_team,bowling_team,overs,runs,wickets,runs_last_5,wickets_last_5)
`final_score = predict_score(batting_team,bowling_team,overs=14.1,runs=136,wickets=4,runs_last_5=50,wickets_last_5=0)`
* Print the results
`print("The final predicted score (range): {} to {}".format(final_score-10, final_score+10))`

* E.g 
```
batting_team = 'Mumbai Indians'
bowling_team = 'Kings XI Punjab'
final_score = predict_score(batting_team,bowling_team,overs=14.1,runs=136,wickets=4,runs_last_5=50,wickets_last_5=0)
print("The final predicted score (range): {} to {}".format(final_score-10, final_score+10))
```
* Output : The final predicted score (range): 177 to 197
