# PUBG-Finish-Placement-Prediction

This notebook runs a Random Forest on a kaggle dataset from https://www.kaggle.com/c/pubg-finish-placement-prediction/overview. 

We are predicting player's finishing placement based on various stats in the mobile game PUBG. 

PUBG Exploration Script outlines the different exploratory techniques that I have attempted. This includes the removal of outliers (e.g. hackers),feature engineering, plotting of feature importance, removal of redundant variables and partial dependence plots. 

PUBG submission script puts all of the learned techniques together, for the final submission. We now run a Random Forest on 4.4 million observations, attaining a 92% R^2 on our validation set. 
