<a name="br1"></a> 

# **Global Peace Index**

Three ML models ,i.e, Simple Linear Regression, Decision Tree Regression, Random Forest

Regression have been trained to calculate the GPI (Global Peace Index) of a country based on 3

domains. Then the results obtained on using each model are compared and plotted.

## Libraries used :

Numpy and Pandas are used to extract and analyse dataset and convert it into desired arrays.

Sklearn is used to train the regression models and Matplotlib is used to plot the graphs.

## Dataset:

The official dataset of 2022 has been used which contain scores of 3 domains affecting the GPI

and the overall GPI score.

## Process:

First, the dataset is scanned, converted into desired arrays,splitted into 80:20 ratio of training and

testing data. The training data is used to train three different ML models and then testing data is

used to predict the GPI score. Then the r2 score and mean squared error of each model is taken

out. Finally, the predicted values of GPI, r2 score and mean squared error of each model are

compared and plotted.

## Outcomes:

r2 score of Linear Regression model : 0.9914942867713249

r2 score of Decision Tree Regression model : 0.9473528127034585

r2 score of Random Forest Regression model : 0.9724067211560283

Mean squared error of Linear Regression model : 0.0019502817032950829

Mean squared error of Decision Tree Regression model : 0.012071515151515163

Mean squared error of Random Forest Regression model : 0.0063268846969697055



<a name="br2"></a> 

