# Task statement
Prepare a prototype of a machine learning model for Zyfra. The company develops efficiency solutions for heavy industry.
The model should predict the amount of gold recovered from gold ore. You have the data on extraction and purification.
The model will help to optimize the production and eliminate unprofitable parameters.

The data is stored in three files:
- gold_recovery_train.csv
- gold_recovery_test.csv
- gold_recovery_full.csv
  
Data is indexed with the date and time of acquisition (date feature). Parameters that are next to each other in terms of time are often similar.

Some parameters are not available because they were measured and/or calculated much later. That's why, some of the features that are present in the training set may be absent from the test set. The test set also doesn't contain targets.

The source dataset contains the training and test sets with all the features.

# sMAPE Formula
![Image-2](https://github.com/betulyildirimx/my-repository/assets/112573830/cf689605-e03f-4999-8794-3151b15393ac)
![Image-3](https://github.com/betulyildirimx/my-repository/assets/112573830/249b01e4-a5da-4008-88dc-441ebbd267f3)

# Libraries used
_matplotlib_

_sklearn_

_numpy_

_pandas_
