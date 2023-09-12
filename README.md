# CodSoft-Tasks
Contains the task files I completed during my internship at CodSoft. I completed 4 tasks out of 5 from the task list (minimum requirement = 3). 

# SPAM-DETECTION:
Link to the dataset - https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset
I trained multiple models on this task and I found out that Support Vector Classifier provides the best Accuracy Score so I included 
that only in the file. 

# BANK-CUSTOMER-CHURN-PREDICTION:
Link to the dataset - https://www.kaggle.com/datasets/shantanudhakadd/bank-customer-churn-prediction
In this file, I have trained multiple models and I have tried my best to improve the Accuracy Score, Precision Score, Recall Score 
and F1-Score as much as possible. 

# MOVIE-GENRE-PREDICTION:
Link to the dataset - https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb
Here, since some of the genres have more weightage in the dataset i.e. due to imbalance in the dataset (both train and test sets), 
the accuracy is very high but the precision, recall and f1 scores are low for the genres with low weightage. Since the test set is 
not supposed to be resampled, hence, the imbalance is the cause of low scores but quite high accuracy. 

# FRAUD-PREDICTION:
Link to the dataset - https://www.kaggle.com/datasets/kartik2112/fraud-detection
Similar to the Movie-Genre-Prediction dataset, this dataset also contains a whole lot of imbalance between the fraudulent cases (~2% of the dataset)
and the non-fraudulent cases (~98% of the dataset). Due to this, the accuracy is quite high but it also has the same problem of low 
precision, recall and f1 scores. 
