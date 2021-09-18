# Car-Price-Prediction

In this project we have used the folowing libraries: Numpy, Pandas, Matplotlib, Seaborn, Sklearn etc

This following dataset was taken from kaggle where our task is to determine those factors which influences the car price and how strong those factors are to detemrine the business startegy etc.

At first we perform data analytics were we plot multiple graphs syuch as: bar, line, box etc

Then we also discovered that our data contain the outliers and some names were incorrect as well and some features were not useful.

In the feature Engineering we dealt with the outliers and standarize our features especially: categorical.

Then we did the feature selection by the help of lasso module and then selected randomforestregressor to train and test our model.

Final evaluation are as follows:
MAE: 0.10320876965860341,
MSE: 0.019345941249296474,
RMSE: 0.13908968778919764,
R_square score:  0.9178940607125717
