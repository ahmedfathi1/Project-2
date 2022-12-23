# Classification of stroke incidence based on certain features


**Author**: Ahmed Fathi

**Date**: 12/23/2022

### Data source: https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

For my final model, I decided that a logistic model was the right choice. The accuracy, f1, precision, recall scores all scored much better in comparrison to the other two models used (Dummy model, and KNN). There was an accuracy of 94% with the precision and f1 scores having 94% and 97% respectively. I also ran an ROC AUC score that gave us 50.6%. 

Even after tuning the hyperparameters of the KNN, the scores were just about the same as the logisitic model, however there was a decrease in accuracy and the ROC AUC score.

I think the model I chose would be effective in production of determining stroke incidences based on the features looked at in the data, as it has about 95% chance of guessing if someone is predisposed to getting a stroke or not.
