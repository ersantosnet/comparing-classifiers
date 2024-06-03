# practical_app_17_1
Practical Application Assignment 17.1: Comparing Classifiers

## Results

After carefully analyzing the dataset and modeling the data in order to best predict which customer profile would be best suit to accept the bank's campaign so the efficiency of the same could be improved with lesser effort. I have found after testing many classifier models using scikit learn such as KNN, DecisionTree, LogisticRegression, and SVC that all of them provide better accuracy than the baseline model.

Therefore, all of themm are good to be used in terms of predictability. However, given that interpretability and explainability are also important in this task the best suitable model here might not be the one with the best overall accuracy. Also, I found very different fitting times as well which might increase cost and complexity to productionize the model.

Here are the final comparison between the many models tested:

![image](https://github.com/ersantosnet/practical_app_17_1/assets/77124166/f1a6b057-d34b-4ef2-b2f7-af2f8e5b5120)

As of the best model I would recommend is the DecisionTreeClassifier given the simplicity to explain and interpret, high accuracy in test and great fitting time.

## What can be done to improve efficiency proactively?

![image](https://github.com/ersantosnet/practical_app_17_1/assets/77124166/605ea6b3-3536-4166-8d56-43058bcb5243)


The duration of the call between bank's operator and customer is the most predictive feature found. That means that the longer customer speaks with the operator, the more likely they will accept the offer. However, this is not something that can be used to find the best customer beforehand because you have to have started to place calls to actually know it. Therefore, this can be used as a operational hint to improve the bank's odds.

The most suitable customers for this campaign are:

nr.employed, month, euribor3m, pdays, contact, default, and campaign.

For more details on the problem statement and the features mentioned here please open the jupyter notebook.
