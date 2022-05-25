# Kaggle_competition

Kaggle-Competition
The aim of this project, was to predict the price of diamonds based on its other features through Supervised Machine Learning.

The featrues were:

id
carat
cut
color
clarity
depth
table
x
y
z

Preprocessing:

I have found there is a very high correlation between x, y and z so I eliminated this features

I have also eliminated the depth and table features because the was a very low correlation between these features and the price

I have tries to normalize the price, but it was nos possible, so I decide it to leave it as it was

I did some encoding:

Since cut color clarity are of type object, LabelEncode all three columns.

Traning Model

Testing Models: I found out the RMSE for various models, trying to work out which of them was better.

Linear Regression:
RMSE: 0.488042

Decision Tree I:🌟
RMSE: 0.20218

Decision Tree II (using GridSearch):
RMSE: 0.246883	

KNeighbors Regressor
RMSE: 0.230207

Random Forest:
RMSE: 0.236776	
