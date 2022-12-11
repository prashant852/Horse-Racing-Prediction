# Horse-Racing-Prediction
Automated Horse Race winner prediction model

## **Dataset description**
Dataset contains two files: races.csv and runs.csv

races.csv contains data like date, distance, config, venue, etc. of the race

runs.csv describes the characteristics of one horse run, in one of the races given in races.csv like weight, type, rating, etc. of horse

>Original dataset can be found [here](https://www.kaggle.com/datasets/gdaley/hkracing)

## **Approach**
We scaled the data on race level such that the final data contains information of all horses, and the race details

Perform feature selection and took only those feature surpassing the threshold

Built 5 different models on different folds and took their average (ensemble modeling)
