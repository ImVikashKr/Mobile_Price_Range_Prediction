# Mobile Price Range Prediction

This project aims to predict the approximate price range of a smartphone based on its key features using historical data. The dataset used for this purpose includes 21 different parameters and 2000 observations. The dependent variable to be predicted is the price range, which is a multi-class categorical value with 4 classes (0,1,2 and 3). The data is well balanced with 500 observations for each class and minimal missing values.

# Algorithms and Techniques used
1. Random Forest Classifier
2. XGBoost
3. Logistic Regression

# Evaluation Metrics
1. Precision
2. Recall
3. F1 scores
4. AUC_ROC scores
5. AUC_ROC curves

# How to Run
1. Clone the repository
2. Install the required libraries by running pip install -r requirements.txt
3. Run the jupyter notebook Mobile_Price_Range_Prediction.ipynb

# Results

The results showed that XGBoost algorithm performed the best among the three algorithms with the highest F1 scores and AUC_ROC scores. Based on the accuracy, XGBoost algorithm is used to predict the prices of the smartphone.

# Deployment

This model can be deployed as an API to predict the price range of a smartphone based on its key features, which can help customers make informed decisions when purchasing a smartphone and help manufacturers determine the appropriate pricing for their products.

# Future Scope
The future scope of the project includes incorporating more data, adding more features, using ensemble methods, comparing other algorithms, deploying the model in real-world scenarios, and addressing the limitations of the model.



