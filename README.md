# Mobile_Price_Range_Prediction
Multi-class Classification.

When a smartphone is purchased, many factors like the Display, Processor, Memory, Camera, Thickness, Battery, Connectivity and others are taken into account . One factor that people do not consider is whether the product is worth the cost. As there are no resources to cross validate the price, people fail in taking the correct decision. This paper looks to solve the problem by taking the historical data pertaining to the key features of smartphones along with its cost and develop a model that will predict the approximate price of the new smartphone with a reasonable accuracy. The dataset used for this purpose has taken into consideration 21 different parameters for predicting the price of the phone.

Random Forest Classifier, XGBoost and Logistic Regression have been used. Hyperparameter tuning is performed for each model.

Different metrics like precision, recall, f1 scores, Auc_roc scores and auc_roc curves have been plotted for different algos. Since this is a multi-class classification problem, one vs rest technique was used to calculate scores for each class whenever required.

XGBoost came out to be the perfect winner. For multiclass F1 scores and Auc_Roc scores one vs rest technique was used to get the metrics for each class.

Based on the accuracy, the appropriate algorithm has been used to predict the prices of the smartphone. This not only helps the customers decide the right phone to purchase, it also helps the owners decide what should be the appropriate pricing of the phone for the features that they offer.
