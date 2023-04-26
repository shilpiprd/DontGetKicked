# DontGetKicked
This is a dataset from kaggle, on which I performed Exploratory Data Analysis to see if the car is a BadBuy or not. </br>
The dataset has features like, vehicleage, purchdate, model, submodel, wheeltype, size etc. </br>
The steps I performed were (in this order) : </br>
1. Load and Analyze the dataset. (No. of missing values, Cardinality of features)</br>
2. Remove the columns which have a large percentage of null values. </br>
3. Remove columns with very high cardinality.</br>
4. Fill the missing values in the column. (median for numerical features & mode for categorical features. ) </br>
5. Perform Feature Engineering. (break down some features into simpler columns such as : purchdate), create some new_features by combining 2 existing features. </br>
6. Perform StandardScaler operation on numerical_features . </br>
7. Encode values from categorical features( both train & test data). </br>
8. Check target_feature distribution, if imbalanced, perform SMOTE. </br>
9. Evaluate Models. </br>
10. Perform Hyperparameter Tuning.</br>
11. Create the final submission file. </br>

