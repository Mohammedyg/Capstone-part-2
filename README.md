The model predicts the likelihood of machine failure. LightGBM algorithm was considered. The main metric used was F1-score for each class (which is: how well can a class be predicted). LightGBM was used because the dataset is imbalanced (minority class is only 339 instances out of 10,000). This means that when training the model, LightGBM gives more weight/importance to the minority class, which may balance the data. Hence, the LightGBM model showed an acceptable F1-score for the minority class on both validation and test sets, 63% and 69% respectively. Thus, for a very imbalanced data, achieving 69% on test set can be convenient.  

Reference: 
the dataset is from Kaggle (https://www.kaggle.com/datasets/shashanknecrothapa/machine-failure-predictions/data)
