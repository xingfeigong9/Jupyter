# Jupyter
step by step illutration how to train/test/submit 

Take care of missing data:
1.first need to check if in train set, target SalePrice has nulls
2.Comnbie train and test sets, remove those with more than 10% of missing data.
3.For categorical columns, drop all features that more than 90% of rows belongs to One category.
4.For numerical columns, check if there're numbers but acutally are categoricals and drop if >90%
5.Imputing missing values

Feature selection/engineering:
1.Encoding categorical features
2.Removing outliers
