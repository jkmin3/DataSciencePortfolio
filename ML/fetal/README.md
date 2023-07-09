# Fetal-Health-Prediction  

## Fetal Health Dataset
This dataset contained a variety of features on newborns and it had its classification of 1-Normal, 2-Suspect, 3-Pathological.

## Random Forest
I used many different models with scikit-learn to predict the outcome of the health of a fetus and ended up using a random forest. I got a result of a 94% accurate model using GridSearchCV to get the best parameters. The only problem is that the grid search take a while, so play around with it. It makes the model a little better, but it may not be computationally worth it.

Feel free to use my code and the [dataset](https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification)!
