This is the process of how I built this Project.

1.Loading the dataset
    used pandas to load the dataset from local drive!
    Note: if you wish to execute this code change the path of the file accordingly)

2.Checking if the features have the prediction power!
    checking for correlation between features and the targetVaribale

    after find the least correlation values (correlation almost zero)
        removed those features from the dataset
    
3.encoding the Categorical feature of the given dataset
    used different encoding t4chnoques for different data features

4.Dropping the missing values

5.checked fro imabalced data
    used simple sum of values of target valriable(0/1)..sum was very less compared to the total rows(tuples)    
    used SMOTE to balance the data


6.used the train test split method and split the dataset into .2 for testing and remaining for training

7.from sklearn library I imported:
    logistic regression
    RandomForestClassifier
    Xgboost
    gradient boosting classifier

    used all 4 model and fiited them with the traning data

    checked the accuracy of each model
    checked the classification report of each model

8.ROC curve and AUC Score:
    plotted the ROC curve for each model
    calculated the AUC score for each model
    compared the models based on AUC score and ROC curve

9.the accuracy of all 4 model is greater than 85% and the recall is highest is .75
