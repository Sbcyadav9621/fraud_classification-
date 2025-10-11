# fraud_classification-
model to predict a customer is fraud or not on transaction details
# Step by step process 
1. Data Extraction
2. Data audit
     - column checking
     - size of the data
     - data type mismatches
3. Data Cleaning & EDA
     - missing value check/treatment
         - Mode for categorical variables
         - Mean/Median for numerical variables
         - KNN for both
    - duplicate check
        - if duplicate are present, drop them
    - univariate analyis
    - correlation
    - outlier check
        - using Box plot
        - use IQR Method for outlier treatment
    - multicollinearity check using VIF
        - drop variables which has high VIF value
4. Data preprocessing
     - Encoding
         Converting categorical variable into numerical variable using OneHotEncoder,LabelEncoder
     - Scalling
         normalizing the data, by arraning all values into one scale(based on algorithm)
         - StandardScaler, MinMaxScaler
5. Splitting the data
     - training set
     - testing set
6. Feature engineering
     - RFE method to select significant features
7. Model implemantation
     - DecisionTreeClassifier(),
     - RandomForestClassifier()
     - KNN
8. Fit the model to training set
9. Make predictions on testing set
10. Evaluate the model performance using evaluation metrics
    - Classification report
    - Confusion matrix
    - accuracy
    - precision
    - recall
    - F1_score
    - Roc_curve
11. Hyper tuning to improve accuracy
    - use GridSearchCV to find best combinations
12. ensure the model performance by comparing accuracy score in both training & testing.
This  is all about the model .

