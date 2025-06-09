# credit_default_predictionmodel
Credit Card Behaviour Score Prediction
OBJECTIVE
The project will focus on improving the credit risk management framework of a bank by developing a forward looking Behaviour Score, that is, a classification model that predicts whether a credit card customer will default in the following month.Based on the historical behavioral data of over 30000 customers a binary classification model has to be set up which helps to predict whether a customer will default in the next billing cycle. Such a model would allow the bank to flag potential defaulters in advance, allowing the bank to adjust the credit exposure, trigger early warnings systems and prioritize risk based actions

PROJECT WORKFLOW
1. Data Preprocessing
Data Cleaning : All the missing values in age column were replaced by mean and datatype changed to int.
2. EDA AND FINANCIAL INSIGHTS
Visualisation : Using matlobplit.pyplot and seaborn to generate heatmap,histogram,countplot etc to find correlation between data and influence on default.
Financial insights : The plots and patterns allowed us to understant how some key behavioral variables influence default risk.
3.FEATURE ENGINEERING
Used some transformation techniques to generate some financially meaningful features like deliquency count,utilisation ratio and max delay.
4. CLASS IMBALANCE
Handled using downsampling and class weighting
5. MODEL TRAINING AND SELECTION
Various classification models like logistic regression,decision tree,xgboost and lightgbm were trained.
Based on the performance on evaluation metrics, XGBOOST was chosen as it had the best F2_SCORE;
classification cutoff was set below its default value of 0.5.
AUTHOR
Eisa Hasan
