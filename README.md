# League of Legends Predictive Model
League of Legends is one of the most played and viewed games in the world. It has around 115 million monthly active players and also has a large presence in e-sports. 
This model was created using a dataset with information from the first 10 minutes of League of Legends games. 
The goal of the model is to be able to accurately  predict the outcome of a game before it ends.
League of Legends is a popular game in  e-sports, so knowing the outcome of a game before it is over offers a chance for coaches to train their team to have a better chance of winning.
This tool also gives coaches insight into what factors are most impactful in the game.

The data set was already fairly clean, however, there were several features that could not be accessed or calculated by players or coaches at the 10 minute mark of a League game. This severely hurt the models performance as those unaccessible features were the most predictive. 


![](images/Feature_Importances_1.png)

The knn base line model gave a 69% accuracy score on the test data.

![](images/KnnGraph.png)

After removing innaccessible features, we were left with the following features.

![](images/feature_importance.png)

The final model was a adaboost that gave a 72.7% accuracy score on the test data.

![](images/adaboost.png)
