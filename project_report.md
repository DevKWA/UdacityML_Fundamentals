# Report: Predict Bike Sharing Demand with AutoGluon Solution
#### Devin Almonor

## Initial Training
### What did you realize when you tried to submit your predictions? What changes were needed to the output of the predictor to submit your results?
TODO: I would recieve an error because the casual and registered columns were present in the test data; however, it was removed to train the initial model.
Additionally, the negative values were needed to output the predictor to submit the results.
### What was the top ranked model that performed?
TODO: WeightedEnsemble_L3

## Exploratory data analysis and feature creation
### What did the exploratory analysis find and how did you add additional features?
TODO: EDA found that there were new features that needed to be added to granularize the data set (years, months, days, and hours). Also, there were seasons and weathers that need to be accounted.



### How much better did your model preform after adding additional features and why do you think that is?
TODO: It performed better because I added more granularized features on which the model trained to give a more accurate number of its performance.The percentage increased from initial to final is 101%! A lower RSME score means better performance. 1.7 to about 0.7 is a great improvement 

## Hyper parameter tuning
### How much better did your model preform after trying different hyper parameters?
TODO: Hyper parameter tuning improved it by preventing overfitting and underfitting of the model data.The percentage increased from initial to final is 30%! A lower RSME score means better performance. 0.7 to about 0.4 is a great improvement

### If you were given more time with this dataset, where do you think you would spend more time?
TODO: I would spend more time in hypertuning because of the performance increase.
### Create a table with the models you ran, the hyperparameters modified, and the kaggle score.

![structured_table.png]
(structured_table.png)

### Create a line plot showing the top model score for the three (or more) training runs during the project.

TODO: Replace the image below with your own.

![model_train_score.png](model_train_score.png)

### Create a line plot showing the top kaggle score for the three (or more) prediction submissions during the project.

TODO: Replace the image below with your own.

![model_test_score.png](model_test_score.png)

## Summary
TODO: I learned a lot about testing and training datasets in the Bike Sharing project.
