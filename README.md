# fraudDetectionSparkML
The purpose of this project is to detect fraud in banking transactions. The model is trained on a credit card Dataset using multiple classifiers in spark. NumPy and Pandas are used for some preprocessing of the data then built-in functions of machine learning are used to train the model. 

Dataset is taken from Kaggle which contains credit card transactions, the features contain transactional data, amount charged, time of the transactions etc. and the output is the label of 1 (fraud) or 0 (normal). The original dataset had more than 100K rows which is then reduced to 10K rows for the model to be trained faster. The data is extremely uneven so it is processed and its labels are distributed equally for model to be trained properly.

After training the dataset on multiple algorithms (Linear, logistic, Decision Tree and Random Forest), we find that the accuracy is almost same on every model and all test data is predicted correctly. We can check any bank transactional data in same order as this dataset with these models and find the result as either fraud or normal transaction.
