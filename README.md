# Glaucoma
This notebook is for determining between GCC and RNFL thickness values, which one is more rigorous for determing the mean deviation and pattern standard Deviation using XGBOOST regressor. Subsequently we will use the best performing data set to predict Glaucoma using the XGBOOST classifier
##Plan
 * 1. Perform exploratory data analysis to identify needed columns, eliminate irrelevant ones, identify outliers and missing data
 * 2. Split the data into GCC and RNFL subsets with the mean and pattern standard deviations as well as the glaucoma status. 
 * 3. For each of the subset, we will split the data into training and testing set train the model using XGBOOST regressor
 * 4. Train the model on the training set and test the data using the testing set
 * 5. Evaluate the model performance using mean squared error
 * 6. Using the best performing subset, add age, sex, CDR, and IOP measurement to predict glaucoma using XGBOOST classifier
 * 7. Evaluate the model performance using confusion matrix, AUC and an ROC curve. 
 * 8. Just visualization of the confusion matrix
