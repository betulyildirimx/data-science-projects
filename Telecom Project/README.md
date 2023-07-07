# Project description
Build a model to forecast churn of customers based on contract information, the client's personal data, etc.

# Data Description

The data consists of files obtained from different sources:

- contract information
- the client's personal data
- information about Internet services
- information about telephone services


In each file, the column 'customerID' contains a unique code assigned to each client.

The contract information is valid as of February 1, 2020.

Target feature: the 'EndDate' column (renamed as 'churn' column)

Metric: AUC-ROC.

# Libraries used
_lightgbm_

_sklearn_

_pandas_ 

_NumPy_ 

_matplotlib_
