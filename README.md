# Glaucoma
This notebook is for determining between GCC and RNFL thickness values, which one is more rigorous for determining the pattern standard Deviation using the XGBOOST regressor. Subsequently, we will use the best-performing data set to predict Glaucoma using the XGBOOST classifier
 * Plan
   *  Perform exploratory data analysis to identify needed columns, eliminate irrelevant ones, identify outliers and missing data
   *  Split the data into GCC and RNFL subsets with the mean and pattern standard deviations as well as the glaucoma status. 
   *  For each of the subsets, we will split the data into training and testing sets to train the model using the XGBOOST regressor
   *  Train the model on the training set and test the data using the testing set
   *  Evaluate the model performance using mean squared error
   *  Using the best-performing subset, add age, sex, CDR, and IOP measurement to predict glaucoma using the XGBOOST classifier
   *  Evaluate the model performance using a confusion matrix, AUC, and a ROC curve. 
   *  Just visualization of the confusion matrix
