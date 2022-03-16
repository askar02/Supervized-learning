# Supervized-learning
Dataset Description:
- types.csv - reference of transaction types
- codes.csv - reference of transaction codes
- transactions.csv - transactional data on banking operations
- train_set.csv - training set with client gender marking (0/1 - client gender)
- test_set.csv - no need to use.


transactions.csv columns description:
- client_id - client is id
- datetime -transaction date (format - ordered day number hh:mm:ss - 421 06:33:15)
- code - transaction code
- type - transaction type
- sum - sum of transaction

I. Explore the dataset. Do the descriptive statistics.<br>
II. Explanatory data analysis. Exploring the features, visualizations etc. <br>
III. Feature engineering. Encodings, generating the features from date-time, sum and
from other columns. <br>
IV. Supervised learning. Build model for prediction the gender of the clients. Decision
Trees, KNN, Random Forest. Tune the hyper parameters, grid search, cross validation
etc. Visualization of the models etc..<br>
V. Analyze models, Result comparison, ROC/AUC, precision and recall curves, deep
analyzing.<br>
VI. Conclusion.
